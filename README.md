# This github repo includes all the replication code for the my Undergraduate dissertation 

## Data Collection
The data was scraped from the PushShift using the pmaw package in python. The file to collect the data is SubredditDataCollection.ipynb (not recommended to try and run the whole script, the whole process of data collection would take no less than 30 hours of continuous running of the code, assuming a good and stable connection  -  please get in touch at my anonymous email ffmc2016[at]gmail[dot]com if you need the entire dataset  (3.5GB).

Some values (necessary for the analysis) from the scraped data are encoded in Base36 (for unknown reasons, possibly a bug in the API wrapper), so I wrote a function to decode them. This is in DECODER.ipynb. All the "comments" files should be run through that first.

The selection of subreddits is in "Randomlychosensubs.R"
## Data Cleaning

The data cleaning process is in DataProcessing.Rmd.
The creation of network models is in DataCleaning.Rmd
The Analysis is in Analysis.Rmd

I have done my best to comment most of the code, though I might have missed something. Please get in touch at ffmc2016[at]gmail[dot]com if there are any perplexities about the code.

