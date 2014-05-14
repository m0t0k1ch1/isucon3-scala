isucon3-scala
=============

a copy of the application used at ISUCON3 final, built with [Scalatra](https://github.com/scalatra/scalatra)

## Build & Run

``` sh
$ cd isucon3-scala
$ ./sbt
> container:start
```

Before you open the application, you have to create database named `isucon` in mysql.
In order to create tables, access the following URL;

[http://localhost:8080/db/create-tables](http://localhost:8080/db/create-tables)

Then, you can open the application.

[http://localhost:8080](http://localhost:8080)
