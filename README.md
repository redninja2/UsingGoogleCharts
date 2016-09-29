# UsingGoogleCharts
Test repository for testing google charts.

## generate_random.py
The main part of the program. This script generates 
a number of random numbers, writes them all to a file 
(random.txt) and creates an array with the same number of 
elements as the range of random numbers (so if the range
in which to generate random numbers was 1 - 100, the 
array would contain 100 elements) with each index
set to 0. The script then reads the file of random
numbers and counts how many of each random numbers have
been generated. So if the number 5 appeared seven times, 
the element at index 4 in the array would be 7 (index 4 because 
arrays start at index of 0). 
Once this is done, the script then generates an html file 
(tindex.html) which contains a google chart with the random number data. 


## index.html
Just a blank page at the moment, but it is the main page of the site. It is 
visitable by going to redninja2.github.io/UsingGoogleCharts/

## random.txt
The text file that contains all the random numbers that have been generated. 

##test.txt
Just a test file, which will likely be removed. 

##tindex.html