# Release GitCall 2.4.0

## Summary

* Concurrent task execution in a single pod.
* Resource utilization improvements.
* Do not mount K8S API token into usercode pod.
* Result size could be configured via polices.
* Task execution time could be configured via polices.

## Corezoid

* Minimum: 5.6.1

## Changelog

[Changelog](CHANGELOG.md)

## Install

```
curl --tlsv1.2 --output cz "https://repo.middleware.biz/deps/cz/darwin/amd64/1.4.4/cz" && chmod +x cz

cz release list-available
cz release new gitcall/2.4.0 gitcall --vv
cd gitcall
cz valid
```

Fix all TODOs in release.yaml file and issues reported by `cz valid`.

Deploy:
```
cz deploy
```

## Upgrade
* Change `release.repositories.gitcall_migrations.git.path` value to `migrations/component`
* Change `release.repositories.gitcall_migrations.git.repo` value to `https://github.com/corezoid/gitcall.git`
* Migrations config has changed
Old:
```yaml
gitcall_migrations:
    config:
        migrator_username: "a_migrator_user"
        migrator_password: 'a_migration_pass'
        host: "a_db_host"
        port: 5432
        db: 'gitcallv2'
```

New:
```yaml
gitcall_migrations:
    config:
        migrate:
            migrator_username: "a_migrator_user"
            migrator_password: 'a_migration_pass'
            app_username: 'gitcall_user'
            owner_username: 'gitcall_owner'
            host: "a_db_host"
            port: 5432
            db: 'gitcallv2'
```
* Remove `gitcall.config.dundergitcall.global_policy.usercode_body_size_limit_bytes`.
* Add `gitcall.config.dundergitcall.global_policy.usercode_timeout_msec`. Default value `2000`
* Add `gitcall.config.dundergitcall.global_policy.usercode_wait_timeout_msec`. Default value `5000`
* Add `gitcall.config.dundergitcall.global_policy.usercode_concurrency`. Default value `10`
* Add `gitcall.config.dundergitcall.global_policy.usercode_result_size_bytes`. Default value `2097152`

## Migrations

* No migrations
