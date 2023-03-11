# Analysis-of-Restaurants-Registered-with-Zomato-Bengaluru-
This dataset is a collection of restaurants that are registered on Zomato in Bengaluru City. 
In this dataset, there are more than 50000 rows and 17 columns.

PYTHON VERSION: Python 3.9.12
PYTHON LIBRARIES USED:
#For Importing and Cleaning Data
pandas
NumPy
#For Data Visualization
matplotlib.pyplot
seaborn

ANALYSIS DONE IN THIS PROJECT:
(I) Restaurant Type.
    Observations :
      1) In restaurants most of the types of meals are for delivery i.e. 25579 i.e most of people tries to order food from restaurants
      2) Then 17562 number of meal types are Dine-out i.e. means lot of peoples loves to eat outside from home i.e. in restaurants
      3) 3559 number of meals types are in Desserts or sweets
      4) 1703 number of types of meals are from cafes
      5) 1084 numbers are of Drinks & nightlife data
      6) 869 numbers are of buffet type of meals
      7) 689 numbers of pubs and bars present in datset of banglore

(II) Restaurant Location.
     Observation :
      1) As BTM place has above 5000 plus number of restaurants
      2) That means BTM is place where most of the people tries to go there or order some cuisines.
      3) And Other location means lovcation which have less than 500 restaurents in dataset are quite high counts i.e. almost 8000 number of places are              there which having <500 restaurants.

(III) Analysis of 'cuisines' feature.
      Observation
        1) from cuisines column we say that most of the food items in restaurants are north indan types.
        2) then north indian chinese is having 2351 types of items.
        3) Also there are lot of such styles of cooking presents which having less in numbers
        4) so for good analysis we can groups these cuisines which have less than 100 counts of items in variable "less_num_cuisines"

(IV) Analysing cost of plate per cuisines in restaurant i.e. ¶ "approx_cost(for two people) feature.
     Observation :
      1) Now we have successfully perform operation on approx_cost feature
      2) loweset cost per plate price is Rs. 40 in restaurant
      3) highest cost per plate price is 6000 in some restaurants
(V)  Analysing listed_in(type) i.e. types of meals.
     Observations :
      1) In restaurants most of the types of meals are for delivery i.e. 25579 i.e most of people tries to order food from restaurants
      2) Then 17562 number of meal types are Dine-out i.e. means lot of peoples loves to eat outside from home i.e. in restaurants
      3) 3559 number of meals types are in Desserts or sweets
      4) 1703 number of types of meals are from cafes
      5) 1084 numbers are of Drinks & nightlife data
      6) 869 numbers are of buffet type of meals
      7) 689 numbers of pubs and bars present in datset of banglore
(VI)  Restaurants way of delivery for cuisines.
      Observations :
       1) In Dataset 30228 restaurents have online delivery facility
       2) 20814 restaurants are not having online delivery service.
       
(VII) Checking wheater restaurants have Booking Table facility or not.
      Observation :
       1) As we can see that Most of the restaurants (i.e. 44626 ) has no facility like booking table.
       2) And in 6416 restaurants has book table facility.

(VIII) Checking how much Ratings are given by peoples to restaurants online delivery.
       Observations from rating for restaurants online delivery :
         1) whether restaurants having online delivery or not the average rating to restaurants given by the customers is 3.70142
         2) maximum rating for online delivery of restaurants by people is around 4.9
         3) minimum rating for online delivery given by customer is around 2.1
         4) And when people go directly to restaurants they give maximum of ratings around 4.9
         5) And when people go directly to restaurants they give minimum of ratings around 1.8

(IX) Checking From which Location of restaurants recieving most online orders
     Observations :
      1) As we have allready seen that most of the restaurant are present in BTM area and it is obvious things that most of there restaurant will have              online delivery facility.
      2) In HSR location around 2000 restaurants have online delivery facility.
      
(X) Restaurants types and there rating.
    Observations :
      1) So Drinks and nightlife Restaurants types has maximum avg rating around 4.2 among other 6 types of restaurants
      2) Then Buffet restaurants have avg rating around 4.0
      3) worst Rating for restaurants types are Delivery, Desserts, and Dine-out.
      
(XI) Checking which location got most of votes.
     Observations :
       1) Here in graph Votes are in 10^6
       2) So highest number of votes are from location "Koramangala 5th Block" is 2214083
       3) and least number of votes are from "Banaswadi" location
       
(XII) Checking which cuisines got how much votes.
      Observations :
        1) from bar plot we see that for "North indian" foods restaurants gets more number of votes i.e. 516310
        2) for "north indian chinese" restaurants gets 258225 votes
        3) For "mithai" food items restaurants gets lowest votings.
