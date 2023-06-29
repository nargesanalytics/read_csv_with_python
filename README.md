# ReadCsvWithPython
Using code python to read csv file instead of using pandas library,
This process reduces storage in memory and 
increases the speed of the code reading process
through the SQL database.


## Table of Contents
* [Introduction](#Introduction)
* [Installation / Usage](#Installation--Usage)
* [code](#code)


  # [Introduction](#Introduction)
  NumPy’s high level syntax makes it accessible and productive for
  programmers from any background or experience level.For ease of work and
  easy access to data by connecting to SQL, you can use this method to avoid the large amount of work and
  the delay in reading information in the Numpay library.


# [Installation / Usage](#Installation--Usage)

* conda list -e > requirements.txt
# install 
  pip install pymysq



# [code](#code)
  
  
 # Establish MySQL connection
    connection = pymysql.connect(host='host', user='user', password='password', database='database_db')

 # Create cursor object
    cursor = connection.cursor()
