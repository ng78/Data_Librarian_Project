# Data_Librarian_Project
Automized query of bibliographic data by using the lobid API in a loop

This is a series of Jupyter Notebooks in which several Python libraries are used in order to create a multiple loop query of bibliographical information by importing data from a csv file, transform it into a list, get the entries of the list into a for-loop, iterating over a request for each entry by using the lobid API, sorting and analyzing the resulting metadata in json format to get an answer to the question how many owners every specific title has. The results are set to be transformed into two new csv files, one with the titles with only one owner (which shouldn’t be deleted in order to match the regulations of the North-Rhine Westphalian University Libraries Center (hbz)) and another with multiple owners (which can be deleted without further monotonous checking).  It should work in order to get rid of a lot of boring work by splitting potentially thousands of titles set to be deleted into two lists of either ignorable or deletable items.
By now, I haven’t found a real workable solution, whereas this may just be a matter of time, concentration and experience to get it done. Approaches have been made and progress is in the coming.
To support this project, please feel free to take a branch and work on a script you like to enhance.
This work is under CC0 licence, please feel free to use it, work with it and share it in each manner.

