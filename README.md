# Outages

Both of the projects listed in this repository revolve around the dataset from the website ("https://engineering.purdue.edu/LASCI/research-data/outages/outagerisks") and each column is explained on this website ("https://www.sciencedirect.com/science/article/pii/S2352340918307182"). The dataset is about the major power outage events in the US from January 2000 to July 2016, with major being defined as either from affecting 50,000 customers or from causing an unplanned firm load loss of atleast 300MW(Megawatts).

In the first file (outages), I clean the dataset and use exploratory data analysis (EDA) for possible aggregations, then find a column
which is not missing by design or NMAR, and finishing up with a hypothesis test.

In the second file (outages2), I used the same cleaning procedures on the dataset as the previous file, then created a Baseline model, then
a final model and evaluated the fairness of the final model using Scikit learn throughout the entire file.

