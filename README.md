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
db_obj.fetchAll('table_name', collum_arr[], Where_arr)

table_name = Table Name from where you want to retrive data
collum_arr = collums you want to retrive for example : ['id','name']
Where_arr = array for where conditions for example :{"id":"3"}
```
