# Mod 2 Project- Broadway Grosses


Link to presentation slideshow: https://docs.google.com/presentation/d/1beP4vmAZb8woGX66PM23OxgjV7xkgTauPFcvcqPEUYM/edit?usp=sharing


## Project Goals

* Create a model that will predict the success of a Broadway show, and figure out what possible attribute contribute to that success. 

## Data

* First used a CSV data set of weekly box office reports from 1993-2006.
* Decided to create my own data set.
* Web-Scraped weekly box office reports from https://www.broadwayworld.com/.
* Final data from over 1,200 broadway shows in a span of 35 years. 


## Data Cleaning

* Narrowing the data to a period of 10 years (2008-2018):
<img src="./Images/Image1.png">

* Cleaning up missing data:
<img src="./Images/Image2.png">

Luckily the data from 2008-2018 was consistently reliable, so there wasn't too much data clenaing to be done.

* Creating new column for new variable (Season):
<img src="./Images/Image3.png">

I wanted to see if seasonality affects the success of the show. 

## Initial Observations

<img src="./Images/Image4.png">



The model aims to predict the success of a possible Broadway show. The independent variables in the model consist of the following:

* `Gross Potential`- The maximum amount an engagement can possibly earn based on calculations involving ticket prices, seating capacity, and the number of performances. 
* `Average Paid Ticket`
* `Top Ticket Sold`
* `Total Seats` 
* `Capacity`- The percentage of the theatre that was filled during that week (seats Sold / total Seats).
* `Type`- Whether it is a "Musical" or a "Play".




