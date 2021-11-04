## veri tipleri    +
## constraints


name    --> string 
age     --> int
price   --> float(double)





# mysql, postresql
# oracle                 => tüm veri tipleri öğrenecez

people   (table)
-----------
name  (column)          => VARCHAR(size), CHAR(size)  == STRING
surname (column)        => VARCHAR(size), VARCHAR2(size)
plaka_id    (column)    => INT, INTEGER, TINYINT, SMALLINT, MEDIUMINT, BIGINT
salary (column)         => FLOAT, DOUBLE, DECIMAL(size,size)
sex (column)            => VARCHAR(1)     'E', 'F'   1, 0,  'Male', 'Famele' => VARCHAR(6)
is_married (column)     => VARCHAR(1)     'T', 'F'   1, 0   'True', 'False'
age(column)             => YEAR1           1990
create_date (column)    => DATE            2021-10-30   (yyyy-mm-dd)
create_date (column)    => DATETIME        2021-10-30 12:00:00   (yyyy-mm-dd hh:mm:ss)
create_time (column)    => TIME            12:00:00     (hh:mm:ss)
islem_tarihi            => VARCHAR(20)     '30-10-2021'

INT, INTEGER, TINYINT, SMALLINT, MEDIUMINT, BIGINT
INTEGER, SHORTINTEGER, LONGINTEGER  

LONGINTEGER     --> (-2**63) to (2**63)-1   => -9223372036854775808 to 9223372036854775807  8 byte  
INTEGER         --> (-2**31) to (2**31)-1   => (-2147483648) to (2147483647)                4 byte 
SHORTINTEGER    --> (-2**15) to (2**15)-1   => (-32768) to (32767)                          2 byte




---- 
name    surname  sex    is_married  age create_date
Tekin   POLAT    


--- con


For each seller, their name, contact email, and postal address.
seller
----- 
name            => varchar(25)
email           => varchar(100)
postal_address  => varchar(150)


For each product, its name, price, and number available.
product
-------
name                => varchar(100)
price               => DECIMAL(10,2)     # 543.12   
number_available    => SHORTINTEGER



E-R  var olma sebebi databaseciler E-R bakıpta tablo, kolonları ne olduğu görsün

