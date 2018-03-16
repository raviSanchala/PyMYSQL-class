# PyMYSQL-class
A Pymysql class for developers to connect python with mysql

### Min  Requirement :
  PyMySQL
  
PyMySQL can be installed by following command
```
$ pip install PyMySQL
```
## Running the tests
```
db_obj = db() //Cretae a object


inserting_arr = {"key1":"value1", "key2":"value2" ....}
// To insert Data into database
db_obj.insertTable('table_name', inserting_arr)


// get multiple data from table 
db_obj.fetchAll('table_name', collum_arr, Where_arr)

// get single row from table
db_obj.fetchRow('table_name', collum_arr, Where_arr)

// update collum in the table
db_obj.db_obj.updateTable('table_name',updated_arr, Where_arr)

// delete row from table
db_obj.deleteTable('table_name', Where_arr)


table_name = Table Name from where you want to retrive data
collum_arr = collums you want to retrive for example : ['id','name']
Where_arr = array for where conditions for example :{"id":"3"}
updated_arr = collums you want to update for example : {"name":"paul"} 
```

Please fill free to use it and let me know in-case of any modification/corrections are required.
