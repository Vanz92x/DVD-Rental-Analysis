# Datamart DVD Rental Database Analysis Using CTE with SQL

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
The DVD store manager has been given a case to analyze, and the analysis uses CTE to form a Datamart, and answers several questions as follows:

### 1. Viewing rental income from films based on:

#### a) Film Title

![Film Title Image](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/65302146-813f-44bb-a9eb-d6968da6f4fe)

#### b) Film Rating

![Film Rating Image](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/5a6883db-3224-4f18-86e0-4aaa2603395e)


#### c) Film Category

![Film Category Image](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/7858b229-ef3c-4626-904d-c12efcf55c75)

### 2. Customer segmentation

#### a) Rental Frequency

![Rental Frequency](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/a7784b0c-3061-41b7-81b4-93d50a112b72)

#### b) Total Rental Cost

![Total Rental Cost](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/2d555c2a-4427-4756-9645-e4e3d22393d0)

#### c) Type of films rented (film category and film rating)

![Type of films rented (film category and film rating](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/82598344-15f4-4481-9a27-7ed03c1cddfe)


### 3.Information on rental delays such as

#### a) The films most frequently returned late

![The films most frequently returned late](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/40e0433e-01d6-4ffd-b354-dacf496f6be7)


#### b) Number of cancellations within a specific period

![Number of cancellations within a specific period](https://github.com/Vanz92x/DVD-Rental-Analysis/assets/165736197/b7fc35c2-c965-4cc4-849b-ee62cbc5d2b0)
