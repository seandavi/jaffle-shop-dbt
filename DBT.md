## Getting started

1. Run `task install-core`
2. Run `task setup`
4. Run `dbt run`

## What happened?

In the terminal:

```
duckdb -readonly jaffle_shop.duckdb
```

In duckdb:

```
# schemata
set search_path='main,jaffle_shop_raw,analytics'
show tables;
select * from customers;
```

## tests

```
dbt test
```

Out of the box, dbt ships with four generic tests already defined: unique, not_null, accepted_values and relationships.

## Packages

- https://hub.getdbt.com/
- https://github.com/dbt-labs/dbt-utils


## Documentation

5. Run `dbt docs build`
6. Run `dbt docs serve`




