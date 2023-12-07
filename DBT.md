## Getting started

1. Run `task install-core`
2. Run `task setup`
3. Run `dbt test`
4. Run `dbt run`

## What happened?

```
duckdb -readonly jaffle_shop.duckdb
# schemata
set search_path='main,jaffle_shop_raw,analytics'
```



5. Run `dbt docs build`
6. Run `dbt docs serve`




