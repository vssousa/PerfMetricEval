# How to configure Chiron for performance evaluation
----
## Postgres' database configuration
1. Download and install [PostgreSQL](https://www.postgresql.org) Database Management System (DBMS).
2. Create a user and set a password.
3. Create a database for this created user.
4. Run database.sql script to set up the Chiron's database schema.

----
## Configuration of workflow files
1. Configure the following files to configure the (directory) paths: chiron.xml and input.dataset.
2. Configure the database name, DBMS user and password in chiron.xml file.

----
## Submission of a synthetic workflow execution using Chiron
> Run the following command line:

    ./submit.sh
