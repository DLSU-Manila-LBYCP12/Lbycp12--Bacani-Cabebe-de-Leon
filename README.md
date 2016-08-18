# Project Proposal

## MoviéDex
– In this project, we will be designing a movie ticketing system where users can view movies that are showing and movies that are coming soon. Users will also be able to reserve tickets through the app and it will compute for the total price of the purchase. Users can also comment on the movies and give their reviews and ratings of the movie. 


#### A)	Home – Movie Selection
These movies are in a tree data structure with genre as the hierarchy. Clicking the posters directs to the movie descriptions.
![1](https://cloud.githubusercontent.com/assets/16644615/17390153/fa103514-5a3c-11e6-9e52-adffb307986b.png)


#### B)	Movie Description
This displays the poster, synopsis, rating, and comments on the movie. Ratings and comments are in a stack data structure .There is also a button to buy tickets.
![2](https://cloud.githubusercontent.com/assets/16644615/17390155/fa37e42e-5a3c-11e6-9082-a20855b78fad.png)


#### C)	Ticket reservation
This shows the seats available for a certain movie. Once the seat is already reserved, the picture is changed to grayscale using opencv commands.  Since the seat arrangement is like a 2D array, it can be implemented using a list of array where the index in the list is the row number and the in the index in the array is the column number. The values in the array determines if the seat is reserved or not (0 or 1).
![3](https://cloud.githubusercontent.com/assets/16644615/17390156/fa5f386c-5a3c-11e6-8e04-1be0d7198c8d.png)

#### Division of labor
- Each of the members will help in creating the GUI and will each be given a data structure to create.

	
#### General significance 
- Easier for users to evaluate which movie to watch because of user reviews
- Will help the user to find movie based on genre
- Easier reservation of tickets

#### Interest 
- OpenCV
	- Opencv will be used for the main GUI of the app 
- Queue – Recent  Searches
	- Movies are added and deleted based on which came first.
- List of lists – Reservation
	- First come first serve basis on reserving tickets.
- Stack – Rating
	- Reviews are averaged based on the number of reviews given.	
- Tree – Movies
	- Movies are going to be divided into categories which will be in a tree
	![untitled diagram](https://cloud.githubusercontent.com/assets/16644615/17397394/777ad324-5a6a-11e6-9045-6043d5d9028c.png)

#Progress Report

##CHECKLIST:
###GUI: 	
####HOME 
![14081439_10206627293313205_2084078476_n](https://cloud.githubusercontent.com/assets/16644615/17769803/0cf79182-656d-11e6-91a1-d21c276ff668.png)
#####DONE
	- TITLE 
	- MOVIE POSTERS AND TITLES
#####IN PROGRESS
	- GENRE FILTER (IN TREE)
	- SEARCH (QUEUE FOR RECENT SEARCHES)

####TICKET RESERVATION
![14017953_10205565602499812_1800503450_n](https://cloud.githubusercontent.com/assets/16644615/17769808/116c9cee-656d-11e6-848a-bf0ee6d03a02.png)
#####DONE 
	- RESERVATION SCREEN WITH 24 SEATS
#####IN PROGRESS
- CONVERT TO GRAYSCALE WHEN CLICKED, USING OPENCV
- DISPLAYS SEATS IN SHOPPING CART
- PROCEED BUTTON TO DISPLAY RECEIPT AND FINISH RESERVATION

####MOVIE DESCRIPTIONS
#####IN PROGRESS
- SHOWS BIGGER POSTER WITH MORE DETAILS FOR THE MOVIES
- RATINGS AND COMMENTS FOR THE MOVIES
			
DATA STRUCTURE


