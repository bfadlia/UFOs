# UFOs

## Project Overview

The purpose of this project is to have a webpage that presents a dynamic table of UFO sighting data.  The webpage provides an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria. The users will be able to interact with the webpage and filter the data based on the date, city, state, country, and shape of the UFOs sighted.

## Resources
- Data Source: data.js
- Software used: HTML, Javascript, CSS, Bootstrap, D3


## Results


### The webpage provides the UFO data in organized in the following table format:
-  Date
-  City	
-  State	
-  Country	
-  Shape	
-  Duration	
-  Witness comments


### Nice styling is achieved with CSS as seen below

![IMAGE_DESCRIPTION](/static/images/screen.png)


## Summary
### Drawback
Due to Javascript's case sensitivity, users have to enter their search criteria exactly how it is spelled in the data. For example state: mn not MN. Thus the user may wrongly think there were no sightings in Minnesota if they didn't write it as mn in the filter. A lot of extra code is needed to fix this issue.

### Recommendations
- As with all free text input to any site or program, there is big potential that the user may input invalid filter values or not know how to exactly match how those items are spelled in the data. A good improvement would be to replace the input search fields with dropdown menus containing the only valid values for each search criteria.
- An improvement that will be really useful is to give the user a count of how many records matched his filter criteria and place that above the table of data. Right now The user has no way to quickly know if there were more sightings in California than Florida for example without scrolling through trhe full table and counting manually.
