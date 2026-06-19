# SQL_Pentagon_Space

## * **Data :-** 

* It is a rawfact which describes attribute of an object or entity.

* **Attribute :-** It is a properties of an object.

* **Entity :-** Anything which is physically present is called as object or  entity.

## * **Database :-**

* Database - It is used to store the data in a systematic and organized manner.

## * **DBMS :-**

* DBMS - It is a software used to maintain and manage the database.
* Data is stored in the file format.
* To communicate with DBMS we use Query Language.

### * **Features of DBMS :-**

 1. Security(Protection)
 2. Authorization/Validation

* ***Types of DBMS :-***

1. Network DBMS
2. Object oriented DBMS
3. Hierarchical DBMS
4. RDBMS

#### **1. Network DBMS :-**

* The data is stored in the form of *network*.

* ***Drawback :***

1. Cost of building network is more.
2. No security of data.

#### **2. Object-oriented DBMS :-**

* The data is stored in the form of *object*.

* ***Drawback :***

1. It is very difficult to build connections between multiple objects. (In the era of 2010)

#### **3. Hierarchical DBMS :-**

* The Data is stored in the form of *tree - like structure*.

* ***Drawbacks :-***

  1. It consumes more time to retrieve a single value data.

#### 4. ***RDBMS :-***

* Here the data is stored in the form of *table(rows and columns)*.
* RDBMS - Relational Database Mangaement System.
* Whenever the DBMS follows either *relational model* or *EF. Codd Rules* than it is considered as RDBMS.
* To communicate with RDBMS we use SQL (Structured Query Language).
* *EF. Codd is an Employee of IBM.*
* *SQL was first provided by IBM.*

* Difference between DBMS and RDBMS.

<table>
  <tr>
    <td><b>DBMS</b></td>
    <td><b>RDBMS</b></td>
  </tr>
  <tr>
    <td>Data is stored in the form of file format.</td>
    <td>Data is stored in the form of table.</td>
  </tr>
  <tr>
    <td>DBMS is communicated using Query Language.</td>
    <td>RDBMS is communicated using Structured Query Language.</td>
  </tr>
</table>

#### * **EF. Codd Rules :-**

1. Data entered into a cell must be a single value data.
2. We can insert the data into multiple tables also we can built connections between the tables using key/attribute.
3. We use datatype and constraints to validate the data.
4. For a table datatype is mandatory but constraints are optional.

#### **Relational Model :-** 

* It is invented by EF(Edgar Frank) Codd in 1970.
* It is used to store data and metadata.

#### * *Metadata :-*

* Metadata - It is the data about the data.

## **Datatype :-**

* It is used to specify the type of data which we are storing inside the memory location.
* They are of 3 types :
   1. Character Format Datatype.
   2. Number Format Datatype.
   3. Date Format Datatype.
      
#### **1. Character Format Datatype :-**

* It is used to store character data values.
* They are of 4 types:
    1. char
    2. varchar
    3. text
    4. binary large object
 
  *1. char :-*
  
  * It is used to store character data values.
  * Here we can store:
      * uppercase
      * lowercase
      * special characters
      * numbers
  * Declaration inside Quotes is mandatory.
  * We can store upto 255 characters.
  * We can't send back unused memory.Hence it is also called fixed length memory.
    
  *Syntax:-*

      char
  
  * *Drawback :-*
 
  * Wastage of memory.

  *2.varchar :-*

  * It is used to store character data values.
  * Here we can store:
      * uppercase
      * lowercase
      * special characters
      * numbers
  * Declaration inside Quotes is mandatory.
  * We can store upto 65535 characters.
  * We can send back unused memory.
  * Hence it is also called variable length memory.
    
  *Syntax:-*

      varchar
  
  * *Drawback :-*
 
  * No Wastage of memory.
 
  *3. text:-*

  * It is used to store large character data values.
  * Here we can store:
      * uppercase
      * lowercase
      * special characters
      * numbers
  * Declaration inside Quotes is mandatory.
  * We can store upto 64kB characters.
  * They are of 2 types:
       *1. mediumtext*
       *2. longtext*

       1. *mediumtext :-* It is used to store character values.
          *Syntax:-*

              mediumtext
          
       3. *longtext.py :-* It is used to store character values.
 
                                                                                                                                                                                                                                                             
       5. 
 
