# Restaurant Data with Consumer Ratings
### Objective
This dataset was obtained from a recommender system prototype. The task is to generate a top-n list of restaurants according to the consumer preferences. Two approaches can be used: a collaborative filtering technique and a content-based approach. 

### Data
The data were originally from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data). There are a README and nine csv files in the [data](data/) directory, including five for the restaurant information, three for the consumer information, and one for the ratings:

Restaurants
- chefmozaccepts.csv
- chefmozcuisine.csv
- chefmozhours4.csv
- chefmozparking.csv
- geoplaces2.csv

Consumers
- usercuisine.csv
- userpayment.csv
- userprofile.csv

Ratings
- rating_final.csv

Three ratings (rating, food rating, and service rating) with values of 0, 1, or 2 are given for a restaurant-consumer pair. More detailed descriptions of the data can be found in the README.

### Results

A collaborative filtering approach is shown in ``collaborative_filtering.ipynb``. Data exploration and visualization in preparation for a content-based approach is shown in ``exploration.ipynb``.

### Acknowledgements
Creators:
<br> 
Rafael Ponce Medellín and Juan Gabriel González Serna
<br> 
rafaponce@cenidet.edu.mx, gabriel@cenidet.edu.mx
<br> 
Department of Computer Science
<br> 
National Center for Research and Technological Development CENIDET, México
<br> 

Donors of database:
<br> 
Blanca Vargas-Govea and Juan Gabriel González Serna
<br> 
blanca.vargas@cenidet.edu.mx, blanca.vg@gmail.com, gabriel@cenidet.edu.mx
<br> 
Department of Computer Science
<br> 
National Center for Research and Technological Development CENIDET, México

### Reference
[Vargas-Govea et al. 2011](http://ceur-ws.org/Vol-791/paper8.pdf)
