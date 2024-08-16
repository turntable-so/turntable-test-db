# turntable-test-db

To repopulate the database run the following commands:

```bash
export POSTGRES_TEST_DB_HOST=localhost 
export POSTGRES_TEST_DB_PORT=6543 
rye run dbt seed
rye run dbt run