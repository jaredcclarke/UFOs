# UFOs

## Overview of Analysis
The purpose of this analysis was to provide an in-depth analysis of UFO sightings data that is displayed in a table on a webpage, by allowing webpage users to filter multiple criteria, which are the following: date, city, state, country, and shape of the UFO.

### Data Tools and Resources
* HTML
* JavaScript
* VS Code 1.51.1
* ../static/data.js

## Results
* In order to use the filter feature of the webpage, scroll down the page and focuse on the left hand side
* On the left hand side of the page, there is a 'Filter Search' section where the user can input specific dates, cities, states, countries and UFO shape.
* Faded text in the multiple search bars show the format the user should use in order for the webpage to understand. 

![](https://github.com/jaredcclarke/UFOs/blob/main/static/images/unfiltered.png)

* Visibile in the picture below, a search for a specific state, in this case "ca" (California). 


![](https://github.com/jaredcclarke/UFOs/blob/main/static/images/filtered.png)

* "ca" was entered in the 'Enter a State' search bar and I hit enter on my keyboard in order to fiter.
* All results that had UFO sightings in California now populate the table.
* Clear the "ca" in the search and the table will repopulate to show all available data. 

## Summary

### Drawbacks
*  A drawback of the webpage is the need to correctly spell the search criteria. So if you misspell the city or shape, or do not inputthe date in the correct format, you will not get a result. 
* There are a lot of results on one page

### Recommendations
* Possibly alter the code to account for misspellings
* Have multiple pages, so the page does not have too much data
* Possiby an auto-fill element 
