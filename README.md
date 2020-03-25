# Predict_travelpattern_ML

To build a classifier that would predict the conversion-likelihood of a user

# Data

 Sample of events collected from an online travel agency, containing:
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

- Notebook1 : Data Preparation i.e a data format that is suitable for the analysis
- Notebook2 : Exploratory data analysis for given variables and extracted features from given information

# Module

# References

- https://www.movable-type.co.uk/scripts/latlong.html

- https://kanoki.org/2019/12/27/how-to-calculate-distance-in-python-and-pandas-using-scipy-spatial-and-distance-functions/
