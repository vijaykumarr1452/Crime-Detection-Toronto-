# Crime-Detection-Toronto

## Dataset : Toronto Police

Utilizing data obtained from the Toronto Police (http://data.torontopolice.on.ca/pages/open-data), I developed a multi-class classification model employing a Random Forest classifier. The aim was to predict the type of major crime committed, considering various factors such as time of day, neighbourhood, division, year, and month. The dataset encompasses all major crimes committed in Toronto from 2014 to 2017*, providing detailed information on the location and time of each offense. Since the dataset comprises solely categorical variables, the modeling process involved testing both numeric encoding and OneHot encoding, with the latter approach showing some improvement.

The model demonstrates reasonably good performance on the F1-score (precision and recall) for a five-class classification problem. Despite the dataset being somewhat unbalanced, with a higher volume of assaults, balancing class weights does not significantly impact the model's performance.
