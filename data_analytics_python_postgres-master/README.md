# Python with PostgreSQL example

### Setup

1. Change content of the '.env' file with database credentials, e.g.:

FLASK_DEBUG=True
DBNAME=app
DBHOST=localhost
DBUSER=app_user
DBPASS=app_password

2. Run the migrations:

    ```shell
    python3 -m flask db upgrade
    ```

### Run the example

Run the Jupyter notebook 'jupyter_postgres_db.ipynb'
