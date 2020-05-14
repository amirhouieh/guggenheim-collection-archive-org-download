# Guggenheim collection bulk downlod from archive.org
List of 205 document identifiers from https://archive.org/ of 205 exhibition catalogs of Guggenheim Museum.


To download in bulk, clone/download this repo. And then simply run the follwoing wget command in Terminal on your MacOs Or Linux:

`wget -r -H -nc -np -nH --cut-dirs=1 -A .pdf -e robots=off -l1 -i ./list.txt -B 'http://archive.org/download/` 

*make sure you are in the same directory when running the command*

Technical help, requirements and/or for Windows users please see http://blog.archive.org/2012/04/26/downloading-in-bulk-using-wget/ 


More about the collection: http://www.noshelfrequired.com/guggenheim-museum-offers-200-exhibition-catalogs-for-free-download/


