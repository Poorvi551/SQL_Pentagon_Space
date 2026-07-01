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

      char(size)
  
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

      varchar(size)
  
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

       1. *mediumtext :-* It is used to store character values. Stores upto 16mB.
          
          *Syntax:-*

              mediumtext
          
       2. *longtext.py :-* It is used to store character values.Stores upto 4GB

          *Syntax:-*

              longtext

    *4. Binary large object :-*

    * It is used to images,videos, audios, pdf's etc..
    * We can store upto 64kB.
      
    * *Syntax:-*
   
          blob
      
    * They are of 2 types:
        *1. mediumblob*
        *2. longblob*
      
     1. *mediumblob :-* It is used to store character values. Stores upto 16mB.
          
          *Syntax:-*

              mediumblob
          
       2. *longtext.py :-* It is used to store character values.Stores upto 4GB

          *Syntax:-*

              longblob
          
 2. Number Format Datatype :-

    * It is used to store number values datatype.
    * They are of 2 types:
        *1. Integer*
        *2. Decimal*

      *1. Integer:-*

      * It is used to store number value datatype.
      * They are of 2 types:
           *1. int*
           *2.bigint*
        
           *1. int:-*
        
        * It is used to store number value datatype.
        * We can store upto 16mB.
           
        * *Syntax:-*

              int

        *2.bigint:-*

        * It is used to store number value datatype.
        * e can store upto 4GB.
          
        * *Syntax:-*

              int

     *2. Decimal:-*

    * It is used to store numbers.
    * *Syntax:-*

              decimal(precision,scale)
      
    * precision - total number of digits.
    * scale - number of digits after decimal
    * Here, in precision i 
      
    * Ex:-

      case 1 :
   
        decimal(5)
      -> +- 99999

      case 2: p>s
   
         decimal(6,3)
      -> +- 999.999
      
      case 3: p<=s

         decimal(2,5)
      -> +-.ooo99
      
    ***Formula(used in case 3 only):-***

      zeroes=precision-scale

3. Date Format datatype :-

   * It is used to store the date values.
   * They are of 4 types:
         *1. date*
         *2. time*
         *3. datetime*
         *4. timestamp*
     
   *1. date:-*

   * It is used to store the date values.
   
   * *Syntax:-*
  
   * Date SQL format -> "YYYY-MM-DD"
  
   *2. time:-*
   
   * It is used to store the time values.
   * *Syntax:-*
  
   * Time SQL format -> "HH:MI:SS"
  
   *3. Datetime:-*

   * It is used to store date along with time.
   * *Syntax:-*
  
   * DateTime SQL format -> "YYYY-MM-DD HH:MI:SS"
  
   *4. Timestamp:-*

   * It is used to store date along with time basd on the timezone.
   * It follows UTC (Universal Coordinated Time).

   * *Syntax:-*
  
   * DateTime SQL format -> "YYYY-MM-DD HH:MI:SS"

## Constraints 

* It is a rule or condition given to a column.

### * Types of constraints :

1. UNIQUE constraints.
2. NOT NULL constraints.
3. CHECK constraints.
4. PRIMARY KEY constraints.
5. FOREIGN KEY constraints.
6. DEFAULT constraints.
7. AUTO INCREMENT constraints.
8. ENUM

### 1. UNIQUE cnstraints :

* It is used to avoid duplicate values which are entered into a column.

### 2. NOT NULL Constraint :

* It is used to avoid an empty cell i.e the column must be filled with values.

* ***NOTE:- In RDBMS two NULL's are not same.***

### 3. CHECK Constraint :

* It is used to give additional condition or user defined condition for a column.
* *Syntax :*   

      CHECK(CONDITION)

  * *Ex :*

        CHECK(LENGTH(CONTACT)=10)

 ### 4. PRIMARY KEY Constraint :

 * It is used to uniquely identify records from the table.
   
 * *Characteristics of Primary key constraint :-*
   
     1. Primary key is used to represent the table among the scheme.
     2. A Primary key must be a combination of unique and not null.
     3. As per the database standards we can have only one primmary key.
     4. it is not mandatory to have prrimary key for a table but design wise preferrable.
  
 ### 5. FOREIGN KEY Constraint : 

* It is used to establish the connection between multiple tables.
  
* *Characteristics :-*

  1. A primary key of a table can eligible to become foreign key in another table.
  2. Foreign key can accept duplicate values and also null values but it is not mandatory.
  3. A table can have multiple foreign keys.
  4. A foreign key is present in child table but always belongs to parent table.
  5. A foreign key is also known as ***'Referential Integrity constraint'***.
  6. Foreign key is not mandatory for a table but design wise preferable.

 ### 6. DEFAULT Constraint :

 * To assign the default values for a column, we use default constraint.
 * *Ex :*
      DEFAULT "VALUE";

### 7. Auto-Increment Constraint:

 * It is used to generate unique values automatically.
 * By default auto-increment is 1, but it can be changed.
 * We can assign auto-increment only for primary key constraint.

### 8. Enum :

* It is used to assign a specified set of values for a given column.

## SQL Statements :

1. Data Definition Language[DDL] :
     1. CREATE
     2. ALTER
     3. RENAME
     4. TRUNCATE
     5. DROP
        
2. Data Manipulation Language [DML] :
     1. INSERT
     2. UPDATE
     3. DELETE
        
3. Data Control Language [DCL] :
     1. GRANT
     2. REVOKE

 4. Transaction Control Language[TCL] :
      1. COMMIT
      2. ROLLBACK
      3. SAVEPOINT

  5. Data Query Language [DQL] :
     1. SELECT
     2. PROJECTION
     3. SELECTION
     4. JOINS
    
###  MySql Installation


 
























































                                                                            
        
        
          
 
