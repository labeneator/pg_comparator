PG_COMPARATOR
==============

PG comparator is a perl script that compares tables between two databases instances, generates a diff and applies it on the destination table.


Example use
-----------

./pg_comparator  --checksum-function=md5  -S -D  “pgsql://UUUUUUU:XXXXXXXX@10.1.200.2/DBNAME/TABLENAME?id” pgsql://uuuuuuu:xxxxxx@testdb.1234.eu-central-1.rds.amazonaws.com:5432/testdb

