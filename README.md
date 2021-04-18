# UFOs
Using Javascript, bootstrap to make a UFO sightings page

## Overview
The purpose of this analysis was to build an HTML page that would allow us to pull different UFO signting information from a javascript data file using filters. I created filters to make this table fully dynamic, meaning that it will react to user input (depending on the area or type of shape of the sighting), and then place the table into an HTML file for easy viewing. I customized the webpage using Bootstrap, and equiped the table with several fully functional filters that will allow users to interact with our visualizations.

## Results

- ![truth](static/Images/Truth.png)

I wanted to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, I added table filters for the city, state, country, and shape. After entering the website details, the link will demonstrate a title, a picture at the top alongside a brief description about the visualization project (as shown in the image above).

- ![table](Images/table.png)

Using JavaScript, I replaced the handleClick() function in my app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, I created a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter". This is shown in the mage above.

## Summary

The webpage created looks immaculate and user-friendly. The filter makes the table dynamic with user input and helps interaction with our visualizations.

However, one drawback about our webpage is that it doesn't have enough data to validate the claims being made. For example, how many people were there during the sightings?

My recommendations for improving the webpage would be:
1. Researching more data that would help the credibility of the claims
2. Adding additional filters such as longitutde and latitude for accurate locations, and time of day the sightings were spotted.
