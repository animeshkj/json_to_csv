Overview:
This project aims to convert a json file to a csv file
The json files in general don't follow any particular schema
This leads to some values being left blank as some documents may not contain that field
While converting such files to comma separated files (csv), it is of utmost importance to consider filling up the null values with a mean value of that respectiuve column
This will help in getting an appropriate summary of the document for each column in the csv file
This project saves the raw and cleaned data files in the default working directories of python