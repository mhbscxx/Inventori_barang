# Inventori Barang
Desktop-based Java Inventory Application.

# Version
The version I used to create this application is:

- NetBeans 12.1 Apache IDE
- Java 11
- MySQL 8.0.21

# Configuration
To use this application, please set up the database first. Open the project in Apache NetBeans - **inventory_goods** > **Source Packages** > **inventory_goods**
then change the **connection.java** file and adjust it to what you are using, as follows:

- connURL = URL of the connection that connects to the database, for example if the database name is inventori then the URL becomes “jdbc:mysql://localhost:3306/inventori?autoReconnect=true&useSSL=false”
                    + “&useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC”
- user = user name in the database
- password = password for the user in the database

Default username and password used for login: 
- Username : **mhb**
- Password : **123**

# Application Features
The features available in this application are as follows:

- Manage master data in the form of:
  - Supplier
  - Customer
  - Employee
  - Goods
  - Goods Category
- Incoming Goods Transaction
- Outgoing Goods Transaction
- Print Report:
  - Goods Inventory
  - Goods In
  - Outgoing Goods
- Change name, username, status and password

  


