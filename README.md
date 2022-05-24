#### Analysing the data from Sakila DVD Rentals

### Description of Project

The description from Udacity's project information page is given below:

In this project, you will query the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, you will be querying the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. To assist you in the queries ahead, the schema for the DVD Rental database is provided here.

(Note: One quirk you may notice as you explore this "fake" database is that the rental dates are all from 2005 and 2006, while the payment dates are all from 2007. Don't worry about this.)

#### Getting Started

### Dependencies

PostgreSQL version 14

Visualization tool (I used Microsoft Power BI Desktop)

64 Bit Windows Machine

### Description of Database

PostgreSQL Sample Database Tables

There are 15 tables in the DVD Rental database:


actor – stores actors data including first name and last name.


film – stores film data such as title, release year, length, rating, etc.


film_actor – stores the relationships between films and actors.


category – stores film’s categories data.


film_category - stores the relationships between films and categories.


store – contains the store data including manager staff and address.


inventory – stores inventory data.


rental – stores rental data.


payment – stores customer’s payments.


staff – stores staff data.


customer – stores customer data.


address – stores address data for staff and customers


city – stores city names.


country – stores country names.

### Setting up the environment

The information and tools required to set up the environment can be found in the link below:

https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/

### Executing the Program

You may follow the suggested steps below:

1. Create a schema with a description

2. Load the downloaded database into the schema

### Author

George Thomas

### Version

Version 1.0 (Initial Release)

### Credits

Mr. Derek Steer, CEO of Mode. I was under his tutelage during the #AdvanceAfricaScholarship (a partnership between Access Bank and Udacity)

PostgreSQL Tutorial: 
https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/


### Questions Solved with the project


1. Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.


2. Provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories.


3. Write a query that returns the store ID for the store, the year and month and the number of rental orders each store has fulfilled for that month. Your table should include a column for each of the following: year, month, store ID and count of rental orders fulfilled during that month.


4. Can you write a query to capture the customer name, month and year of payment, and total payment amount for each month by these top 10 paying customers?
