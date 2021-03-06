# CLI

## Alias (incluying auth)

Ref: https://docs.cloudbees.com/docs/admin-resources/latest/cli-guide/config-alias

```sh
alias jenkins-cli='/path/to/jenkins-cli.sh'
```

## Adding Plugin catalog

Ref: https://docs.cloudbees.com/docs/admin-resources/latest/plugin-management/configuring-plugin-catalogs#adding-a-plugin-catalog-to-operation-center

```sh
$> jenkins-cli -webSocket plugin-catalog --put < plugin-catalog-file.json
{"id":"additional-funny-plugins","message":"Catalog updated correctly","status":"SUCCESS"}
```

jenkins-cli plugin-catalog --push additional-funny-plugins --master crodriguezlopez

## Files

* plugin-catalog-file-2.1.json - Validated with CloudBees CI Managed Master 2.235.2.3-rolling

## Ref

* [Jenkins CLI](https://www.jenkins.io/doc/book/managing/cli/)