# CPS510
DBMS
/* USER INFO Table */
CREATE TABLE user_info(
    user_name VARCHAR(100) NOT NULL UNIQUE,
    pass_word VARCHAR(30) NOT NULL,
    first_name VARCHAR(30) NOT NULL, 
    last_name VARCHAR(30) NOT NULL,
    phone_number INTEGER NOT NULL UNIQUE, 
    gmail VARCHAR(100) NOT NULL UNIQUE);


