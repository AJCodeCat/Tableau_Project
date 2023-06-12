# Final-Project-Tableau

## Project/Goals
This project utilized Tableau to investigate and describe factors associated with prices and the number of reviews received by more than 30,000 AirBnB listings in New York City from 2008-15, based on a dataset from Inside AirBnB. My goal was to create interactive visualizations to aid a prospective AirBnB host in forming expectations and making business decisions based on the location and type of unit they might list.

## Process
### Step 1
The first step was exploring the data. Right off, mapping the locations revealed a number of listings from outside New Yrok, whether in nearby communities in New York State and New Jersey all the way to units in Washington State on the opposite side of the continent. Then I calculated means and medians for the numerical options like the number of beds (which is different than bedrooms) and how 
### Step 2
Step 2 was creating visualizations to demonstrate relationships between variables. I made them interactive so users could investigate differences by variables lke wihich of the five NYC burroughs, postal ZIP codes for a more narrow location, and type of room listing. I also created a variable, Time Hosting, to reflect how many months a host had been with AirBnB, calculated as the date they joined AirBnB (the Host Since variable) subtracted from January 1, 2016.
### Step 3
My final step was selecting the visualizations to use in my Dashboard, where the desire to provide a lot of information competes with needs such as visual appeal and trying not to overwhelm, both of which demand a lot of winnowing.

## Results
I chose Option 2 and the AirBnB option with the Inside AirBnB's NYC dataset. I am someone who knows AirBnB as a renter, but chose to examine the data with questions that might be asked by someone interested in becoming a host. What type of prices are listed for units in my area? What about for my type of unit, such as a room in a unit versus the entire unit? Can I look forward to being able to raise my prices as my tenure as a host increases? Will my price increase if I get a number of positive reviews? 
The main results I would convey to a prospective host are emphasizing things they probably know, such as how important the location and type of room they list are prime determinants of both the price they can command and the volume of guests they might attract, and the smaller factors over which they have more control, such as the number of beds a unit offers. The number of beds was the only variable that notably correlated with price at r = 0.30 and on its own in a simple linear regression accounted for R^2 from 10% to 15% in each burrough, with higher R^2 in the outer burroughs, particularly Staten Island, compared to Manhattan and Brooklyn, as seen in the scatterplot I created with a trendline for the linear regression.
The Cluster analysis reinforced these ideas in that Neighborhood and Room Type were at the root for cluster formation no many how many other variables I added or removed from the model.

Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

## Challenges 
The challenges revolved around wishing for additional data, such as dates units were rented, duration of the rental period, and how many units hosts own to better understand the competition new hosts face, particularly in the form of market power the biggest players might leverage. I used the number of reviews as a proxy ceiling for the number of times a unit had been rented, but how good that a proxy that is remains unknown.

## Future Goals
(what would you do if you had more time?)
