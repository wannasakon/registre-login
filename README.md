# registre-login 
CREATE TABLE users ( \
  id int(12) NOT NULL AUTO_INCREMENT PRIMARY KEY, \
  username varchar(100) NOT NULL, \
  email varchar(100) NOT NULL, \
  password varchar(100) NOT NULL\
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
