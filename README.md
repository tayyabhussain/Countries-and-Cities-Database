# Countries-and-Cities-Database
Repoository containing sql files of countries and cities table for developers.
First create tables in your database
#Cities Table
---
CREATE TABLE `cities` (

  `id` int(10) NOT NULL DEFAULT '0',
  
  `country_id` int(10) NOT NULL,
  
  `state_id` int(10) NOT NULL,
  
  `city_name` varchar(200) NOT NULL
  
);

#Country Table 
---
CREATE TABLE `countries` (

  `id` int(10) NOT NULL DEFAULT '0',
  
  `country_name` varchar(200) NOT NULL,
  
  `alpha2_code`	char(2) NULL,
  
  `alpha3_code`	char(3) NULL,	 
  
  `numeric_code`	smallint(4) NULL,	
  
  `country_icon`	char(7) NULL
  
);



