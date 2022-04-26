# Release DBCall 1.6.0

## Summary

* Internal refactoring.
* Go and 3rd part modules update.
* Optimized CPU and memory consumption in dunderdbcall.
* Dunderdbcall result hard limited to 2Mb.

## Corezoid

* Minimum: 5.5.1

## Changelog

[Changelog](CHANGELOG.md)

## Install

```
curl --tlsv1.2 --output cz "https://repo.middleware.biz/deps/cz/darwin/amd64/1.4.1/cz" && chmod +x cz

cz release list-available
cz release new dbcall/1.6.0 dbcall --vv

cd dbcall
cz valid
```

Fix all TODOs in release.yaml file and issues reported by `cz valid`.

Deploy:
```
cz deploy
```

## Upgrade

Since 1.6.0 DBCall uses cztool for deployment. 
You have to install this version in another k8s namespace. 
It could work with dbcall already installed. 
Prior version has to be deleted with `helm uninstall` command.

## Migrations

* No migrations
