# nosql-challenge
Purpose: to evalutes various establishments across the United Kingdom for The UK Food Standards Agency <br>

Part 1: Database and Jupyter Notebook Set Up<br>
1. Import establishments.json file<br>
2. Import libraries <br>
3. Create an instance of the Mongo Client<br>
4. Confirm if the data loaded properly<br>
5. Assign the collection to a variable <br>

Part 2: Update the Database<br>
1. Insert a new restaurant data to Database <br>
2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields <br>
3. Update the new restaurant with the BusinessTypeID you found<br>
4. Delete data that related to Dover <br>
5. Convert latitude and longitude to decimal numbers<br>

Part 3: Exploratory Analysis <br>
answer the following questions:<br>
1. Which establishments have a hygiene score equal to 20?<br>
2. Which establishments in London have a RatingValue greater than or equal to 4? <br>
3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?<br>
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.<br>
