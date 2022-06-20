# UFOs
## Overview of Project
### A simple webpage was created using JavaScript, Bootstrap, HTML, and CSS to display UFO sighting data from January 1 to January 13, 2010 across multiple countries. The webpage initially was capable of filtering solely on the date of the UFO sighting, but additional filtering options needed to be added to increase the functionality and interactivity of the webpage. Updates to the JS code and HTML file were performed to allow for these changes.
## Results
### To Perform a Search by Date
#### On the left hand side of the webpage screen, there is one box where the date can be entered to filter the table data by a specific date. The date must be within the range of January 1 to January 13 of 2010 and must be in the same format as that which is pre-populated yet not used as a filter. This format is as follows: m/d/yyyy or m/dd/yyyy for days 10, 11, 12, or 13. For example, 1/2/2010 returns eight results from various cities and states in the United States. See Figure 1.

FIGURE 1: UFO Sightings 1/2/2010
![1 2 2010_filter](https://user-images.githubusercontent.com/102757676/174505203-c99a4cc4-011a-43f3-b4a9-7a929c266245.jpg)


### To Perform a Search by Country, City, State, and/or Shape
#### Again on the left hand side of the screen, in the white boxes for country, city, state, or shape, lowercase text can be entered to filter data. The shapes available for filter include circle, light, triangle, fireball, unknown, formation, sphere, disc, chevron, cross, changing, oval, cigar, and more. If the data needed to be filtered by country, entering "ca" for Canada will return two results. See Figure 2. 

FIGURE 2: Canada UFO Sightings
![Canada_filter](https://user-images.githubusercontent.com/102757676/174505255-3ef993d7-fa19-4887-a1d6-f0b12e3a503a.jpg)

#### If an investigation into the sightings for the entire state of California was required, entering "ca" in the state filter would return many results. Adding on a date field, let's say New YEar's Day, 1/1/2010, fewer results are returned. Finally, filtering by shape "light" would return seven results. See Figure 3.    

FIGURE 3: Light-shaped UFO sightings
![Light_California_1 1 2010_filters](https://user-images.githubusercontent.com/102757676/174505599-dac9810f-7d15-42ca-9d49-78b839c384ed.jpg)

## Summary
### The new design of this webpage to be able to filter on in addition to the date has provided much improvement to the functionality and interactivity. However, there are still drawbacks. One of the largest drawbacks is having to type in all lowercase to return results. Since there are no directions provided on the webpage itself to type search parameters in all lowercase letters, a user may come to the inaccurate conclusion that there are no results for a particular search. Since JavaScript is case-sensitive, code would need to be added to ensure no matter the case of the search parameter the results would be returned. For example, Canada has the country code of "ca" and there are two search results for Canada. If a user were to type in "CA" instead, no results would be returned. Changing the code to accept "CA" to mean exactly the same as "ca" is one way to update the code and improve the functionality of the webpage. An additional development would be to change the search entries to drop-down menues for the available selections in the data. A user may spend all day trying to find search results for August of 2010 to no avail because the user was unaware the data only covered 1/1/2010 to 1/13/2010. Adding slectable drop-down menues would allow a user to more quickly search the data because they would have been given the available search parameters instead of randomly choosing values that do not exist in the data. There are myriad other changes that could be made to imporve the site, but these are the two that stand out the most.
