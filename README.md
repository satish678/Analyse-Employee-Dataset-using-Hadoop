# Analyse-Employee-Dataset-using-Hadoop
Analysis on Employee Data-Set using big data technologies like Hadoop and  Hive.

1) Using Hadoop command move all those employees data into HDFS directory "/user/your_user_name/employees_data" directory

2) Create an external Hive table "employees_Table" representing this "employees_data". This table will have 4 fields id,age,gender,role and    salary.

3) create a new bucketed table "Consultant_Table_Bucket" having 4 buckets on the field salary. This table should store the data into          columnar format ORC

4) Insert all those employees whose salary is greater than 5000 into bucketed table "Consultant_Table_Bucket" from "employees_Table" table.    While inserting into "Consultant_Table_Bucket" table you need to convert "consultant" role into "BigData Consultant" role.

5) Write a Hive query to find out Max, min salary of "BigData Consultant" from the "Consultant_Table_Bucket" table
