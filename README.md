# UFOs

## Overview

The purpose of the UFO Sightings project is to gather a table of data concerning UFO sightings and relevant details. The table is displayed on a website where users can filter the data by various criteria, such as date and location. JavaScript was utilized to provide the code that filters the table within the website. List elements were added to the HTML to create the form with filter options, and functions were created in JavaScript to loop through the data and gather the data that matches the inputted filters. 

## Results

The website is simple and functional to use. At first, the entire table is displayed with all of the UFO sighting data. This includes the data, city, state, country, the shape of the sighting, the duration, and any relevant comments. The filter search form on the side allows the user to filter by date, city, state, country, or shape. The user may filter the table by multiple attributes at a time. Examples are displayed in each entry box (such as “us” for country) so that the user has a basis on which to input filters. After inputting the search, the table automatically updates with the filtered search results. 

Here is an example of a search filtered by “ca” as the state and “triangle” as the shape.

![UFO filtered.png](https://github.com/noorsami12/UFOs/blob/2e45cb1ddba76c8332b75c562fc8da15a75c40ea/UFO%20filtered%20table.png)

## Summary

One drawback of this new design is that there is no way to filter for the duration. The problem with adding duration to the filter search is that the duration category in the table is not consistent; some variations in listings include “3 minutes” versus “20” versus “4min.” Before adding a search option for duration, the data itself would need to be cleaned up and unified. 

Additionally, the user is unable to filter by a portion of the date; they are required to enter the full month, day, and year. If the user wished to sort the table by all UFO sightings in 2010, they would be unable to do so. In order to allow the date to be filtered to further detail, we would have to split up the date column in the table of data so that the month, day, and year are able to be separately searched for. 
