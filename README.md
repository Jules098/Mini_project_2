# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
#### Gather and create a database of Points Of Interest (POI) in my neighbourhood. 
#### Include bars, restaurants, and other places of interest (parks, tourist locals, neighbourhood sights).
#### Compare and contrast the quality of the API coverage of the area.

## Process
## Step 1: 
### Pull Foursquare API data for my neighbourhood.
### Organize, analyze and store Foursquare API data.
## Step 2:
### Pull Yelp API data for my neighbourhood.
### Organize, analyze and store Yelp API data.
## Step 3: 
### Create SQL database schema.
## Step 4:
### Organize, analyze and store API data into SQL database schema.
## Step 5:
### Evaluate and assess data coverage from both APIs.


## Results
The Foursquare API pulled in more unique values for every category with the exception of Cafés.  That being said, upon closer inspection many of the values in certain categories are inaccurate or are too broadly applied.  For example: the 5 most common bars within a 5km radius of my house according to the Foursquare API are:

1. Boulangerie Première Moisson        3
2. St-Viateur Bagel                    2
3. Boulangerie les Co'Pains d'Abord    2
4. Boulangerie Guillaume               2
5. Mamie Clafoutis                     2

All of these would better be categorized as bakeries or cafés and some of them do in fact show up again in bakeries.
Overall I would say the Yelp API had better coverage of my area as it is more accurately categorized.

## Challenges 
Getting used to the yelp API probably took me longer than it should have.  Once I did however it felt like smooth sailing.  I would say the biggest challenge has been the end process of taking all the data I have accumulated and turning it into something.

## Future Goals
With more time I would like to gather different dimensions from the API calls.  Ratings would be good
