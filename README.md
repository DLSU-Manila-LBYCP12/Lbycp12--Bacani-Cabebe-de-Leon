### Proposal for proj 

## Description 
– In this project, we will be designing a movie ticketing system where users can view movies that are showing and movies that are coming soon. Users will also be able to reserve tickets through the app and it will compute for the total price of the purchase. Users can also be able to comment on the movies and give their reviews and ratings of the movie. 


# A)	Home – Movie Selection
These movies are in a tree data structure with genre as the hierarchy. Clicking the posters directs to the movie descriptions.

# B)	Movie Description
This displays the poster, synopsis, rating, and comments on the movie. Ratings and comments are in a stack data structure .There is also a button to buy tickets.

# C)	Ticket reservation
This shows the seats available for a certain movie. Once the seat is already reserved, the picture is changed to grayscale using opencv commands.  Since the seat arrangement is like a 2D array, it can be implemented using a list of array where the index in the list is the row number and the in the index in the array is the column number. The values in the array determines if the seat is reserved or not (0 or 1).

# 
