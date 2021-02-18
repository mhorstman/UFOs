# UFO Sigtings Website

## Overview
The purpose of the website is to catalog UFO sightings and allow users to dynamically filter on multiple criteria to get a customized list of sightings.

### Resources
**Input**: data.js <br/>
**Software**: Javascript, HTML, VSCode <br/>
**Output**: index.html <br/>

## Results
The website contains background information on UFO sightings and enables users to dynamically filter on the list of UFO sightings. Users are able to filter on any combination of date, city, state, country, and UFO shape. To filter user simply needs to enter a value into one of the search fields. As soon as a value is entered the list will automatically update to show the desired result. To reset the filters the user simply needs to refresh the page or click on the "UFO Sightings" link in the top navigation bar. 

The screen shot below shows and example of a filtered list. In this case the user filtered on date = 1/4/2010, state = ca and shape = light. The city and country filters were not used in this example, however they show example values to help guide the user input should they choose to use them.  
![Filter Example](https://github.com/mhorstman/UFOs/blob/main/static/images/filter_example.png)

## Summary
The website is a good start provide users a tool to search through the large list of UFO sightings data, however additional enhancements are recommended to add functionality to the site and make it more user friendly. One main drawback to the current site is that the search is limited to one value per search field (e.g. only allows the user to search for one date at a time). The following are 2 recommendations for enhancements on future releases. <br/>
**Recommendations**
1. Update the search functions to accept multiple values, such as multiple states or a range of dates.
2. Make the search functions more robust to work with either upper or lower case letters.
