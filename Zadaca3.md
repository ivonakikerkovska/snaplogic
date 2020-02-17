Snaps used

File Read- To read files from a given  file
CSV Parser- To read the csv data from the file 
Maper- To transform incoming data using the given mappings
Filter- To filter a document data by given expression
Router- to split the file datas in two outputs
Sort- to sort the data
CSV Formatter - to convert the document in csv format
File Write - to write and save the new data

Additional notes
First we read the file and parse it into csv file than with mapper  we transform the data for example one of the given data is transformed from string to integer. Than we filter the data who are even. With router we split those data into two files the firts otput are data with index below 15 and in the second file are data above 15. We sort the data from both files and write them into two separated csv files.
