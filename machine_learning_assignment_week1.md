# SQL
## Problem 1
Query all columns for all American cities in CITY with populations larger than 100000. The CountryCode for America is USA.
### Input Format
The CITY table is described as follows: 
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/revising-the-select-query/hackers/imdangodaane/download_solution
## Problem 2
Query the names of all American cities in CITY with populations larger than 120000. The CountryCode for America is USA.
### Input Format
The CITY table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/revising-the-select-query-2/hackers/imdangodaane/download_solution
## Problem 3
Query all columns (attributes) for every row in the CITY table.
### Input Format
The CITY table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/select-all-sql/hackers/imdangodaane/download_solution
## Problem 4
Query all columns for a city in CITY with the ID 1661.
### Input Format
The CITY table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/select-by-id/hackers/imdangodaane/download_solution
## Problem 5
Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.
### Input Format
The CITY table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/japanese-cities-attributes/hackers/imdangodaane/download_solution
## Problem 6
Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
### Input Format
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/japanese-cities-name/hackers/imdangodaane/download_solution
## Problem 7
Query a list of CITY and STATE from the STATION table.
### Input Format
The STATION table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/weather-observation-station-1/hackers/imdangodaane/download_solution
## Problem 8
Query a list of CITY names from STATION with even ID numbers only. You may print the results in any order, but must exclude duplicates from your answer.
### Input Format
The STATION table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/weather-observation-station-3/hackers/imdangodaane/download_solution
## Problem 9
Let N be the number of CITY entries in STATION, and let N' be the number of distinct CITY names in STATION; query the value of N - N' from STATION. In other words, find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.
### Input Format
The STATION table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/weather-observation-station-4/hackers/imdangodaane/download_solution
## Problem 10
Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.
### Input Format
The STATION table is described as follows:
![Image of Table](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/weather-observation-station-5/hackers/imdangodaane/download_solution
# Python
## Problem 1
We add a Leap Day on February 29, almost every four years. The leap day is an extra, or intercalary day and we add it to the shortest month of the year, February.
In the Gregorian calendar three criteria must be taken into account to identify leap years:

The year can be evenly divided by 4, is a leap year, unless:
The year can be evenly divided by 100, it is NOT a leap year, unless:
The year is also evenly divisible by 400. Then it is a leap year.
This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300 and 2500 are NOT leap years.Source

Task
You are given the year, and you have to write a function to check if the year is leap or not.

Note that you have to complete the function and remaining code is given as template.
### Input Format
Read y, the year that needs to be checked.
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/write-a-function/hackers/imdangodaane/download_solution
## Problem 2
A newly opened multinational brand has decided to base their company logo on the three most common characters in the company name. They are now trying out various combinations of company names and logos based on this condition. Given a string s, which is the company name in lowercase letters, your task is to find the top three most common characters in the string.

* Print the three most common characters along with their occurrence count.
* Sort in descending order of occurrence count.
* If the occurrence count is the same, sort the characters in alphabetical order.

For example, according to the conditions described above,
GOOGLE
 would have it's logo with the letters G, O, E.
### Input Format
A single line of input containing the string S.
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/most-commons/hackers/imdangodaane/download_solution
## Problem 3
Read an integer N.

Without using any string methods, try to print the following:
123...N.

Note that "..." represents the values in between.
### Input Format
The first line contains an integer N.
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/python-print/hackers/imdangodaane/download_solution
## Problem 4
You are given an integer, N. Your task is to print an alphabet rangoli of size N. (Rangoli is a form of Indian folk art based on creation of patterns.)

Different sizes of alphabet rangoli are shown below:
```
#size 3

----c----
--c-b-c--
c-b-a-b-c
--c-b-c--
----c----

#size 5

--------e--------
------e-d-e------
----e-d-c-d-e----
--e-d-c-b-c-d-e--
e-d-c-b-a-b-c-d-e
--e-d-c-b-c-d-e--
----e-d-c-d-e----
------e-d-e------
--------e--------

#size 10

------------------j------------------
----------------j-i-j----------------
--------------j-i-h-i-j--------------
------------j-i-h-g-h-i-j------------
----------j-i-h-g-f-g-h-i-j----------
--------j-i-h-g-f-e-f-g-h-i-j--------
------j-i-h-g-f-e-d-e-f-g-h-i-j------
----j-i-h-g-f-e-d-c-d-e-f-g-h-i-j----
--j-i-h-g-f-e-d-c-b-c-d-e-f-g-h-i-j--
j-i-h-g-f-e-d-c-b-a-b-c-d-e-f-g-h-i-j
--j-i-h-g-f-e-d-c-b-c-d-e-f-g-h-i-j--
----j-i-h-g-f-e-d-c-d-e-f-g-h-i-j----
------j-i-h-g-f-e-d-e-f-g-h-i-j------
--------j-i-h-g-f-e-f-g-h-i-j--------
----------j-i-h-g-f-g-h-i-j----------
------------j-i-h-g-h-i-j------------
--------------j-i-h-i-j--------------
----------------j-i-j----------------
------------------j------------------
```
The center of the rangoli has the first alphabet letter a, and the boundary has the N(th) alphabet letter (in alphabetical order).
### Input Format
Only one line of input containing N, the size of the rangoli.
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/alphabet-rangoli/hackers/imdangodaane/download_solution
## Problem 5
You are asked to ensure that the first and last names of people begin with a capital letter in their passports. For example, alison heck should be capitalised correctly as Alison Heck.


Given a full name, your task is to capitalize the name appropriately.
### Input Format
A single line of input containing the full name, S.
### Solution
https://www.hackerrank.com/rest/contests/master/challenges/capitalize/hackers/imdangodaane/download_solution