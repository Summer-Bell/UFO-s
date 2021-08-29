#UFO Sightings Analysis

## Overview of the UFO Sightings Analysis
Dana has developed a dynamic webpage titled "The Truth is Out There."
It allows users to perform in-depth analysis on UFO sightings.
Users can filter the UFO table by multiple criteria.
It allows users to determine if UFO sightings are fact or fancy based on sightings data.
This interactive webpage was created using JavaScript and HTML.

### Purpose
The JavaScript file [data.js](js\data.js) contains a dataset of nearly 100 hundred different UFO sightings.
To make this data easy to navigate requires coding to loop through the dataset and only keep the results that matched specific search criteria entered on the webpage by a user.
The code to filter the dataset is in [app.js](js\app.js) file.
It contains an event listener to detect changes in the filter.
The updateFilters function saves the element, value and id of the filter that has been changed.
Then the FilterTable function loops through all the filters and only keeps data that matches the filter values.
The file [index.html](index.html) builds the UFO webpage and utilizes both JavaScript files.

## Results
### Steps for Using the UFO Sightings Webpage:
- When UFO enthusiasts navigate to Dana's webpage they are able to enter criteria in a filter search.
	- The filter criteria are:
		- Date
		- City
		- State
		- Country
		- Shape 

- To help users enter criteria correctly there are examples of entries displayed in each search criteria
	-	[Blank_Filter.PNG](images\Blank_Filter.PNG) shows the filter search users see when opening the webpage along with search entry examples.
	
- Users can enter multiple search criteria then hit enter to execute the search.
	-	[Filter_mulitple.PNG](images\Filter_multiple.PNG) shows the filter results for the state of California with a triangle shapes.


## UFO Analysis Summary

- One Drawback of Current Design

The user could miss search results due to typing the searching criteria incorrectly. 
For example the results for New Mexico will only populate if the user types "nm" in lower case letters.
If they type "NM" in uppercase letters no data will populate in the search table.

- Two Recommendations for Further Development

Add code that will make the search parameters not case sensitive would be very beneficial.
A drop-down list for the state and country would also help users enter in filter criteria correctly.
Having a button that clears filters would make performing multiple searches quicker and easier.
Currently users have to delete the filter criteria they have entered if they no longer want to use it.

