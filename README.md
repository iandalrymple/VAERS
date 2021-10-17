Set up requires the following:

- Set the directory variable in the first cell to the directory containing all the years of the VAERS data from https://vaers.hhs.gov/data/datasets.html.
- The advanced API is not being used for the manufacturer data so no need to create a config file at this time. 

The project will read in all the VAERS data and join it together for your own manipulation. It will also read in the manufacter data and then get the last 
day since this is cumulative data set and only the last is needed. 