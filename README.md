# DVD Rental Database Analysis Using SQL

## Data Understanding
The DVD Rental database provides a comprehensive representation of the business processes involved in managing a DVD rental store. This well-structured database consists of 15 interrelated tables, each designed to capture various aspects of the store's operations, from managing inventory to tracking customer transactions. The relationships between these tables are illustrated in the following entity relationship diagram, which highlights how different entities within the database interact with one another.
<div align="center"><img src="https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/7c2ae9e6-a063-4aa3-8544-3dba14b83e79" /></div>

### Data Dictionary
* Customers: Contains customer information such as names, addresses, and contact details.
* Staff: Stores details about the staff members, including their roles and contact information.
* Stores: Information about the different store locations.
* Rentals: Tracks rental transactions, including the rental and return dates.
* Inventory: Manages the inventory of DVDs, linking to the film titles and their availability.
* Films: Contains details about the movies, including title, description, release year, and rating.
* Categories: Defines the genres of the films.
* Film_Actors: Maps actors to the films they have acted in.
* Actors: Stores information about the actors.
* Film_Categories: Links films to their respective categories.
* Payments: Records payments made by customers for rentals.
* Cities: Lists the cities relevant to customers, staff, and stores.
* Countries: Contains country information associated with cities.
* Addresses: Stores detailed address information for customers, staff, and stores.
* Languages: Details the languages available for the films.

## Question
The DVD store manager has been given a case to analyze, and the analysis uses CTE to form a Datamart, and answers several questions as follows: (Note, from the CTE can look detail at CTE Query)

### 1. Viewing rental income from films based on

a) Film Title

b) Film Rating

c) Film Category


### 2. Customer segmentation
a) Rental Frequency

b) Total Rental Cost

c) Type of films rented (film category and film rating)


### 3.Information on rental delays such as
a) The films most frequently returned late

b) Number of cancellations within a specific period
