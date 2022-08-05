# Trading-Stocks-App
System Requirement Specification (SRS) :
1. To run the project you must have python installed in your system (version 3 or
above)
2. To visualize the database you must have mysql workbench installed in your
system.





1. ER Diagram
![image](https://user-images.githubusercontent.com/83928126/183125482-95681cc2-66f1-4cd1-9557-78713920a477.png)



2. Schema Design
According to the project requirement we came out with a simple schema consisting of 6 tables

- Stock table
- Trader table
- Trades table
- Account table
- Login Table
- Portfolio Table

Trader table consists of all the relevant details consisting of the user who logs in to the system.
Stock table consists of all the details about companies Shares like no_of Available share
,Share price etc .
Login table consists of all the login which have been done

Trades Table consist of the transactions of type of . trade which user has done like buy,sell
no_of shares purchased etc.


3. Data Normalisation
The tables we made are all in 3NF which means that they are in 2NF , 1NF and also free from
transitive dependencies .
● Trader Table
Primary key is User_id
Using user_id we can determine the person.
And by solving the functional dependency relation we can find that the table is in 3NF




Stock Table
Primary key is StockId (which we are extracting from the google login object)
Using Stock we can determine the stock price,company name etc
And by solving the functional dependency relation we can find that the table is in 3NF.
![image](https://user-images.githubusercontent.com/83928126/183125403-788da454-2658-4b03-819c-579eaec6e8b6.png)
















