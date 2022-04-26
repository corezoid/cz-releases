# Release DBCall 1.6.0

## Summary

* Introduce new DBCall API.
* Old approach still there and works. Will be removed in 2.0 releaes.
* Deprecates dunderdbcall.
* Deprecates ServicesPIMP.

## Corezoid

* Old API: >= 5.5.1
* New API: >= 5.10.0

## Changelog

[Changelog](CHANGELOG.md)

## Install

```
curl --tlsv1.2 --output cz "https://repo.middleware.biz/deps/cz/darwin/amd64/1.4.1/cz" && chmod +x cz

cz release list-available
cz release new dbcall/1.7.0 dbcall --vv

cd dbcall
cz valid
```

Fix all TODOs in release.yaml file and issues reported by `cz valid`.

Deploy:
```
cz deploy
```

## Upgrade

New config sections (related to new API) are required and must be configured:
* `dbcall.config.query_consumer`
* `dbcall.config.query_reply_publisher`

New optional `dbcall.config.prometheus` section added. You can expose Prometheus metrics, if enabled.   

## Migrations

* No migrations
