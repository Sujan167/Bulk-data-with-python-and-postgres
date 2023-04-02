
# Bulk-data-with-python-and-postgres

This project demonstrates how to fetch JSON data from an API and upload it into a PostgreSQL database using Python and the psycopg2 library.


## Prerequisites
Before running the script, make sure you have the following:

1. Python 3.x installed on your system.

2. PostgreSQL database installed on your system.

3. psycopg2 library installed. You can install it using the following command:

```bash
pip install psycopg2
```
## Usage
1. Clone this repository using the following command:


```bash
git clone https://github.com/Sujan167/Bulk-data-with-python-and-postgres.git

```

2. Navigate to the project directory.
#### NOTE: Database Connection
host = 'localhost',

port = '5432',

user = 'postgres',

password = '****',

dbname = 'postgres'

3. Run the script.py file using the following command:


```bash
python3 script.py
```
This will fetch the JSON data, create a table in the PostgreSQL database, and insert the data into the table.

