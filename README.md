# turntable-test-db

To repopulate the database,

1. Run the following commands:

```bash
export POSTGRES_TEST_DB_HOST=localhost 
export POSTGRES_TEST_DB_PORT=6543 
rye run dbt seed
rye run dbt run
```

2. Go through folder structure in `postgres_test_db_data` and add a `.gitkeep` file to each folder that is empty.

