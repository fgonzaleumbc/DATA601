The modifications below were made to the original data for educational purposes and to provide potential examples on issues that are typically found in data that has not been cleaned. Most datasets found on the web have been already cleaned and for data cleaning purposes are not necessarily the best examples. In cases the data may be fixable by looking for the information. In the case of the movie data it is easy as this is publicly available information however, in many cases it may not be as easy to fix the data points. Some errors may be avoidable in databases with a simple error checking routine when the data is being entered however, not all databases have error checking routines.

Line 60, ID 5174, modified the budget from 1.4E8 to -1.4E8. A negative budget would be impossible and this would be an example of a potential input error.

Line 71, ID 44826, modified the runtime from 126 to NAN. A nan value is a missing value. 

Line 4213, ID 74084, modified id from 74084 to 118340. The new ID also belongs to another movie. This is an example of where a unique ID has a duplicate which by definition should not be possible. Note the title in this movie is giberish as well. User may need to decide if deleting both or keeping one or the other data record or row and also which ID may be correct or incorrect and why.

Line 102, ID 4922, created a full duplicate of all values and inserted in as line 112.

Line 134, ID 19585, modifed runtime from 88 to 888. This would represent an error on the runtime as this would not be logical.

Line 3115, ID 53953, modified runtime to string 'three'. This would represent a data entry error as this should be a number (float or integer). In many cases the data entry user interface may have limits or a routine that checks that it uses the correct data type but in some other cases it does not.

Line 3672, ID 113406, modified runtime from 0 -124

Also the data file was divided into three. This is to represent multiple data files and demonstrate how the data from multiple datafiles can be combined. This can represent datasets that were collected in different timeframes. Three files were created with the format "XXXX-to-YYYY-ORIGINAL_FILENAME.csv" where XXXX is the first release date year in the range and YYYY is the last release date year. The three files are: "1916-to-1959-tmdb_5000_movies-Modified.csv" (i.e., blank release dates are included in this one), "1960-to-1989-tmdb_5000_movies-Modified.csv", and "1990-to-2017-tmdb_5000_movies-Modified.csv".