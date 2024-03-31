# Movie-Rental-Analytics
This Is My Capstone Project

## Dataset Description

The dataset described is a comprehensive database that appears to represent a video rental store or movie rental service. It comprises multiple tables, each representing different entities and their relationships. Taking a closer look at the key components of the dataset:

Table Explanations
Actor Table
The actor table lists information for all the actors, including first name and last name of actors.

Address Table
The address table contains address information for customers, staff, and stores.

Category Table
The category table lists the categories that can be assigned to films.

City Table
The city table contains a list of cities.

Country Table
The country table contains a list of countries or regions.

Customer Table
The customer table contains a list of all customers.

Film Table
The film table lists all the films that may be in stock in the store.

Film_text Table
The content of the film_text table is kept in synchrony with the film table by means of triggers on the film table INSERT, UPDATE, and DELETE operations.

Film_actor Table
The film_actor table is used to support many-to-many relationships between films and actors.

Film_category Table
The film_category table is used to support many-to-many relationships between films and categories.

Inventory Table
A row in the inventory table represents a copy of a given film in a given store.

Language Table
The language table lists all possible values for the film language and original language.

Payment Table
The payment table records every payment made by the customer, including information such as the amount and rent paid.

Rental Table
The rental table contains a row for each rental of each inventory item, which contains information about who rented what, when it rented it, and when it was returned.

Staff Table
The staff table lists all staff information, including email addresses, login information, and pictures.

Store Table
The store table lists all stores in the system.
