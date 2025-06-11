# Notes_DataEngineer
Basic keywords for DE roles

------------------------------------------------------------------------------------------------------------------------------------------------------------------

### **Surrogate Key**

A surrogate key is an artificial or synthetic key used in a database table to uniquely identify a record when a natural key (from the actual data) is either Not unique, Too large or complex, Or subject to change. 
- It has no business meaning.
- Used as the primary key of a table, especially in data warehousing and dimensional modeling.
- Customer_Key (Surrogate)	Customer_ID (Natural)	Name	Country
Customer_Key is surrogate key here.
- Common use cases - Slowly Changing Dimensions (SCD Type 2) – where you keep track of historical changes in dimension tables. Data Warehouse – to decouple analytical systems from changes in operational systems.
- Joining Tables Efficiently – smaller numeric keys perform better in joins than long strings.
