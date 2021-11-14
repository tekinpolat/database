## databases 
## table 
## kolon(column)
## data types
## constraints (kısıtlama)
   -- veri eklerken, veri güncellerken, veri silerken
   - NOT NULL (boş olmamalı)
   - UNIOUE (tekrar eden veri olmamalı)
   - CHECK (kontrol)
   - DEFAULT (varsayılan)
   - PRIMARY KEY (ana anahtar)
   - FOREIGN KEY (yabancı anahtar)

CREATE TABLE users (
    user_id INTEGER PRIMARY KEY AUTOINCREMENT,
    name VARCHAR(50) NOT NULL,
    surname VARCHAR(70),
    email VARCHAR(100) UNIQUE,
    year YEAR1 CHECK(year < 2011),
    description TEXT DEFAULT 'işlem',
)


#SQL 
---- 
user_id  name    surname  email                           year   description
1        Tekin   POLAT1   tekin.polat.dpu@gmail.com       1990   izmirde yaşıyorum
2        Ali     POLAT    tekin.polat.xyz@gmail.com       2001   MERHABA
3        Yiğit   ERSÖZ    yigit@gmail.com                 2000   işlem
4        Tekin   YILMAZ   tekin.yilmaz@hotmail.com        1990   hello