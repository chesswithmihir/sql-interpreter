# A SQL Interpreter
## By Mihir Mirchandani

---
# Before Starting the Project 

### Introduction
I want to try building a SQL Interpreter in Java. This interpreter will have very minimal functionality and will not cover the full depth of the SQL language, but it will give me a fundamental understanding of how to approach the querying of relational databases.

### The Design Architecture
I'm thinking of using either JSON or in-built Java data structures to support the storage of data. If I were to use Java Data Structures, I would have to persist this data through object serialization. I could also persist the data into JSON files, but since I am using Java to build this, I would need the JSONObject Maven Dependency to work with. I would use either for the saving of tables. To query my *database* would simply mean querying my data structures. If I were to go down the JSONArray path, I would probably find it better to make an JSONArray of JSONObjects and provide column names as keys and column values as values in each JSONObject. 

### Functionality
First I will start with the basic SELECT and FROM clauses and then move onto WHERE and maybe even INSERT. I really forgot a lot of SQL so this project would really refresh my memory there. 

---

# During the Project 

--- 

# End of Project / Conclusions

