Snaps used
FILE READER- To read the data from file
CSV PARSSER- To read the data from the file in csv format
MAPER- To transform incoming data using the given mappings
SORT- to sort the data 
JOIN- to join two or more data files
CSV FORMATTER - to convert  and save the document in csv format
FILE WRITER - to write and save the new data

Additional notes
In this pipeline first we read two csv documents. 
Then i use mapper to transform incoming data. The next step is to sort the data from the files. 
With the snap JOIN-merge those two documents in one document, and at the end we save them in one new csv document.
