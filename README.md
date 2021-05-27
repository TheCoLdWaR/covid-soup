# covid-soup
Example Project. Get data from worldometer covid statistics with Python BeautifulSoup!


* Requirements
from bs4 import BeautifulSoup
import requests
import pandas as pd
import xlwt
from xlwt import Workbook
import docx
from docx.shared import Pt
import csv

* What is the covid-soup ?
 
-> Getting countries and continents statistics via worldometer.com statistics.

* What statistics are there ?

-> For countries : Total Cases, Total Deaths, Total Recovered and Last 24 hours statistics.
-> For continents : Total Cases, New Cases, Total Deaths, New Deaths, Total Recovered, New Recovered, Active Cases, Serious(Critical).

* How many countries and Continents are there ?

-> 195 countries, 6 continents(Europee, North America, Asia, South America, Africa, Oceania).
-> And World Total Statistics.

* What can i do with this information ? 

-> .docx .xls and csv files ca be printed.



