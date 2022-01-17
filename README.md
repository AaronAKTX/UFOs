# UFOs

## Overview
UFO sightings across the globe have been tracked and recorded. Using a dataset of UFO findings we have created a webpage with a dynamic table of UFO sightings and descriptions. The data that is displayed in the table can be filtered using five different criteria: Date, City, State, Country, and Shape of the UFO. 

## Results: 

The result of this project is a webpage that includes a dynamic, filterable table of UFO sightings. That looks like this:
<img src = "https://github.com/AaronAKTX/UFOs/blob/main/static/images/webpage.PNG">

The table can be filtered by Date, City, State, Country, and Shape. <br />
<img src = "https://github.com/AaronAKTX/UFOs/blob/main/static/images/filters_only.PNG">
<br /> 
If the text box of one of the filters is updated, once the user clicks out of the updated text box, the table will dynamically update to only show records that include the value(s) in the populated filter text boxes, 
For example, if the Date filter was updated to 1/1/2010 and then that field was clicked out of, the table would update like so:
<img src = "https://github.com/AaronAKTX/UFOs/blob/main/static/images/date_filter.png">

If the user then updated the State filter to CA, the table would be filtered to show UFO sightings on 1/1/2010 in California. The table could then also be filtered by city or shape to further narrow down the records shown. Examples below:
<img src = "https://github.com/AaronAKTX/UFOs/blob/main/static/images/filter_date_state.png">

<img src = "https://github.com/AaronAKTX/UFOs/blob/main/static/images/filter_date_state_city.png">

You may see some light gray text in the filter text boxes. That text does not update the table, it is there as an example for the user to understand what type of data should be entered in the field.

## Summary

I believe the overall goal of the project was met with the creation of the functioning webpage with a dynamic table. There are many improvements that could be made to the page though. Here are some examples:
- The date field could be updated to allow for different date formats. Right now, if a user entered 01/01/2010 or 1-1-2010 for example, nothing would be returned. Only 1/1/2010 will return data for January 1st, 2010.
- The city, state, and country should work regardless of capitalization. Currently, the data is all in lowercase and the filter is matching exactly with the data. This should be updated so that lower and upper case entries return the same results.
- The table could be cleaned up to have a limit of rows and the ability to look at one page of data and then move to the next page instead of all the data showing in an ever-growing table.
