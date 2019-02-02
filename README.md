![CuseyHub](https://github.com/cusey/ImageForWiki/blob/master/Logos/CuseyHub_Banner_Small.jpg)

# ServerJsonExamples

## Built With
* Toad Data Modeler
* Toad for Oracle   
* server-json 
* Hortonworks

## File Location   

Folders |File|Description
----------| ----------| -------------------------------------------
DataGrip/SQL| ```bank_*.sql``` | SQL scripts to generate TABLES data.
ToadDataModeler| Generate.sql | SQL script to generate TABLES, PRIMARY KEY, FOREIGN KEY, INDEX, and CONSTRAINT
ToadDataModeler| JerseyNationalBank.jpeg |Entity Relationship Diagram (ERD)


# MySQL   

First you need to ceate a scheme   
```
CREATE SCHEMA `bank` ;
```
Then run the SQL script ["Generated.SQL"](https://github.com/cusey/DatabaseExamples/blob/master/ToadDataModeler/Generated.SQL) that was generated by Toad Data Modeler.

# Setting JSON Server

Install JSON server
```
~/Desktop/server/ServerJsonExamples $ npm install -g json-server
```

Create a db_bank.json file with some data


Start JSON Server
```
~/Desktop/server/ServerJsonExamples$ json-server --watch db_bank.json
```
## Authors
* John Cusey - CuseyHub  

## License   
This project is licensed under the MIT License
