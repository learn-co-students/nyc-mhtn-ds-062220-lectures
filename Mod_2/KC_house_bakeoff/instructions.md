# Kings County Housing Bake-off:

For many machine learning projects, the goal is to create a model that best predicts the target variable on unseen data. In order to develop a model we have a general process that we will discuss this week, but there is a lot of flexibility within this process. Even when working with the same data, people can produce different models by engineering different features, or by selecting certain features to include in the models. There is no one correct way to create a model, and this week you will practice the process by creating a model that will predict the prices of homes sold in the Seattle, WA area.  

Working in pairs, you will develop a model using `kc_house_data_train.csv`.Then you will use that model/process to predict on the `kc_house_data_test_features.csv`. For example, if you created anew feature with your training data, you will need to do the same thing with the test data before using the model to prediction the test data.  

After using your model to predict the test data, you will submit those predictions as a `.csv` file to the instructional staff. We will then `grade` the submitted predictions using the RMSE of those predictions. While we will have a score that ranks each of the groups' submissions, the main goal of this is to become familiar with the modeling process. Please do not focus too much on your group's final rank, as there is some element of randomness that will separate  the submissions.

## Data Set Information:

This dataset contains information about houses that were sold in the Seattle area during the last decade. Below is a description of the column names, to help you understand what the data represents. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions relating to what the data means.

As you you go through this modeling process, think about what determines how much someone will pay for a house.  For example, the larger the house is, the more people will pay for it. If you understand why certain house cost more than others and represent that in your model, it will be a more accurate model.  

Have fun!

# Column Names and descriptions for Kings County Data Set
* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
