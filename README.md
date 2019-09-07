mysql> LOAD DATA INFILE 'D:\MySQL\tabel_nama.txt'
INTO TABLE tabel_nama
FIELDS TERMINATED BY ','  LINES TERMINATED BY '\r\n';
Query OK, 2 rows affected (0.06 sec)
Records: 2  Deleted: 0  Skipped: 0  Warnings: 0
 
mysql> SELECT * FROM tabel_nama;
+------------+----------------+------------+-----------+
| ID        |       name      | id work    |id_sallary |
+------------+----------------+------------+-----------+
| 01         | rebecca        |     01     | 01        |
| 02         | vita|          |     02     | 02        |
+------------+----------------+------------+-----------+
2 rows in set (0.00 sec)
 <br>
 
 mysql> LOAD DATA INFILE 'D:\MySQL\tabel_work.txt'
INTO TABLE tabel_work
FIELDS TERMINATED BY ','  LINES TERMINATED BY '\r\n';
Query OK, 2 rows affected (0.06 sec)
Records: 2  Deleted: 0  Skipped: 0  Warnings: 0
 
mysql> SELECT * FROM tabel_work;
+------------+----------------+------------+
| ID        |       name      | id sallary |
+------------+----------------+------------+
| 01         | frontend dev   |      1     |
| 02         | backend dev    |      2     |
+------------+----------------+------------+
2 rows in set (0.00 sec)
<br>

mysql> LOAD DATA INFILE 'D:\MySQL\tabel_kategori.txt'
INTO TABLE tabel_kategori
FIELDS TERMINATED BY ','  LINES TERMINATED BY '\r\n';
Query OK, 2 rows affected (0.06 sec)
Records: 2  Deleted: 0  Skipped: 0  Warnings: 0
 
mysql> SELECT * FROM tabel_kategori;
+------------+-----------+
| ID         |  sallary  |
+------------+-----------+
| 01         | 10.000.000|
| 02         | 12.000.000|
+------------+-----------+
2 rows in set (0.00 sec)
<br>

mysql> LOAD DATA INFILE 'D:\MySQL\tabel_query.txt'
INTO TABLE tabel_query
FIELDS TERMINATED BY ','  LINES TERMINATED BY '\r\n';
Query OK, 2 rows affected (0.06 sec)
Records: 2  Deleted: 0  Skipped: 0  Warnings: 0
 
mysql> SELECT * FROM tabel_query;
+------------+----------------+------------+
|    name    |      work      |   sallary  |
+------------+----------------+------------+
| rebecca    | frontend dev   |10.000.000  |
| vita       | backend dev    |12.000.000  |
+------------+----------------+------------+
2 rows in set (0.00 sec)
