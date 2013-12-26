SpringMVCDemo
=============
change the login credentials for database access in file - database.properties

and run following sql query

CREATE TABLE IF NOT EXISTS `Employee` (
  `empid` int(11) NOT NULL AUTO_INCREMENT,
  `empname` text NOT NULL,
  `empaddress` text NOT NULL,
  `salary` decimal(10,0) NOT NULL,
  `empAge` int(11) NOT NULL,
  PRIMARY KEY (`empid`)
) ENGINE=InnoDB;
