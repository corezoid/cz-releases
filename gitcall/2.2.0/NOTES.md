# Release GitCall 2.2

## Summary

* Run usercodes in a single k8s namespace
* Use gitcall without usercode network polices
* Language's runtime security update
* Performance optimizations (20% less CPU, 10% less memory)
* Fix migrations on RDS

## Corezoid

* Minimum: 5.5.0
* New features: 5.6.1

## Changelog

[Changelog](CHANGELOG.md)

## Install

```
curl -sSfL --output cz "https://repo.middleware.biz/deps/cz/darwin/amd64/1.3.3/cz"
chmod +x cz

cz release list-available
cz release new gitcall/2.2.0 gitcall --vv
```

## Upgrade 2.1 to 2.2

* Usercode network policies are disabled by default now. Apply these changes to keep 2.1 behavior (network policies enabled).  

```yaml
gitcall:
  config:
    dundergitcall:
      k8s:
        network_policy: true

gitcall_pimp:
  config:
    k8s:
      manage_networkpolicies: true

```

* Usercodes run in single namespace by default now. Apply these changes to keep 2.1 behavior (run in separate namespaces).

```yaml
gitcall:
  config:
    dundergitcall:
      k8s:
        # If set deploy all usercodes to this single namespace. If empty deploy usercodes to {owner_id} namespaces (2.1.0 behavior)
        single_namespace: ''

gitcall_pimp:
  config:
    k8s:
      manage_namespaces: true
```

* If you want to run all usercodes in a single namespace apply these changes

```yaml
gitcall:
  config:
    dundergitcall:
      k8s:
        # If set deploy all usercodes to this single namespace. If empty deploy usercodes to {owner_id} namespaces (2.1.0 behavior)
        single_namespace: 'usercodes'

gitcall_pimp:
  config:
    k8s:
      # must be true if single_namespace option empty
      manage_namespaces: false
```


## Migrations

* No migrations