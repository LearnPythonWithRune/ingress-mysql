# ingress-mysql
Ingress MySQL is a MySQL server for demonstration purposes.

## Description
This is a repository containing a Dockerfile, which builds a MySQL server with inserting the schema.sql.

The file `schema.sql` has the query to create an empty table.

## How to
To build the image have Docker Desktop (or Docker engine) running.

Then execute this command.
``` bash
docker build -t ingress-mysql .
```

To run it execute this command.
``` bash
docker run -dp 3306:3306 ingress-mysql
```