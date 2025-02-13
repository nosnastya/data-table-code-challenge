Use-case
We have a page in pur system called 'Flight Inspirations' where user can see suggestion for his upcoming travel.
You need to ceate an admin dashboard to view and edit the 'Flight Inspirations'.

What is already in the codebase:
Yu have Tanstack table. Each table cell is editable and after updating any cell (or multiple cells) you will see the editted cells in highlighted color. 
You are able to save the cells and the data in the table is persisted. This functionality should remain working.

Assignment:
I. Register on Amadeus Developer and get access to their free open-source APIs we will use in this challenge:
Step-by-step guide to get the keys https://developers.amadeus.com/register

II. Create a form with two inputs: one for the city code and another one for the date. Add a submit button or icon.

III. Using the values from the form do the API call to fetch Flight Inspirations 
http://developers.amadeus.com/self-service/category/flights/api-doc/flight-inspiration-search/api-reference

IV. Display the results of the call in the table you have in this codebase. Feel free to edit any code necessary, its just a blueprint.

V. After data is displayed make sure its styles nicely. 

VI. Add drag and drop functionality to the columns of the table. (You should be able to switch position of the columns: eg. 5 -> 1, 1 -> 2, etc).

VII. Add client side pagination on scroll.
