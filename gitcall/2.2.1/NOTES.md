# Release GitCall 2.2

## Summary

* Do not lint JS files in node_modules directory.
* Docker server HPA triggers at 50% (was 80%).
* Support 'ssh://' links in git clone
* Added description of error when js usercode return nothing

## Corezoid

* Minimum: 5.5.0
* New features: 5.6.1

## Changelog

[Changelog](CHANGELOG.md)

## Install

```
curl --tlsv1.2 --output cz "https://repo.middleware.biz/deps/cz/darwin/amd64/1.3.4/cz"
chmod +x cz

cz release list-available
cz release new gitcall/2.2.1 gitcall --vv
```

## Upgrade 2.1.0 to 2.2.1
* No action requried

## Migrations

* No migrations