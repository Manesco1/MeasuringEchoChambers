# This github repo includes all the replication code for the my Undergraduate dissertation.
# The data was scraped from the PushShift using the pmaw package in python. The file to collect the data is SubredditDataCollection.ipynb (not recommended to try and run the whole script, the whole process of data collection would take no less than 30 hours of continuous running of the code  -  please get in touch at my anonymous email ffmc2016@gmail.com if you need the entire dataset (3.5GB).
# Some values (necessary for the analysis) from the scraped data are encoded in Base36 (for unknown reasons, possibly a bug in the API wrapper), so I wrote a function to decode them. This is in DECODER.ipynb. All the "comments" files should be run through that first.
# The Data Processing 
