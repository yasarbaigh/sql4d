SQL4D provides SQL interface to query to various DDMS(Distributed Data Management System) such as CouchDB, Cassandra and HBase.

SQL4D can be split into three parts.
  1. SQL syntax analyzer : SQL syntax analyzer analyzes SQL from users and converts it to an appropriate form.
  1. Mediator between SQL and DDMS : Mediator interacts with DDMS by given SQL.
  1. JDBC driver for SQL4D.

Firstly, we will provide three major DDMSs.
  1. CouchDB
  1. Cassandra
  1. HBase