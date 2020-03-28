# Predict_travelpattern_ML

To build a classifier that would predict the conversion-likelihood of a user

# Data

 Sample of events collected containing:
  -  `ts` - the timestamp of the event
  -  `event_type` - either `search` for searches made on the site, or `book` for a conversion, e.g. the user books the flight
  -  `user_id` - unique identifier of a user
  -  `date_from` - desired start date of the journey
  -  `date_to` - desired end date of the journey
  -  `origin` - IATA airport code of the origin airport
  -  `destination` - IATA airport code of the destination airport
  -  `num_adults` - number of adults
  -  `num_children` - number of children

# Content

- Notebook1 : Data Preparation i.e a data format that is suitable for the analysis.
- Notebook2 : Exploratory data analysis for given variables and extracted features from given information.
Additionally, Feature Selection from given dataset.
- Notebook3: Solving issue of class imbalance and then applying Log. classifier to provide results' comparsion.
- Notebook4 : Applying multiple machine learning models and compare them with Neural network model performance.
- Notebook5 : Implementing model tuning techniques and also discussing different evaluation matrics in detail.

# Module

# References

- https://www.movable-type.co.uk/scripts/latlong.html

- https://kanoki.org/2019/12/27/how-to-calculate-distance-in-python-and-pandas-using-scipy-spatial-and-distance-functions/

- https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/

- https://towardsdatascience.com/predicting-hotel-bookings-with-user-search-parameters-8c570ab24805

- https://www.youtube.com/watch?v=U3X98xZ4_no
 
- https://www.youtube.com/watch?v=DQC_YE3I5ig

- https://github.com/coding-maniacs/over-under-sampling/blob/master/src/main.py
