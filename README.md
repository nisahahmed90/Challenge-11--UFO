## Overview
The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

## Filter on landing page

<img width="1274" alt="Screen Shot 2022-05-25 at 10 36 06 PM" src="https://user-images.githubusercontent.com/100812308/170404079-84558867-142e-4e92-80ed-52bde5d47011.png">

## Filters when being used

By typing in the suggested placeholder elements as the filters, the result returns 2 matches. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website.

<img width="1296" alt="Screen Shot 2022-05-25 at 10 37 45 PM" src="https://user-images.githubusercontent.com/100812308/170404227-dd1f997a-e2eb-4cbf-a34c-bbc1c2037a88.png">

## Summary

### Drawback
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations:
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.

2. A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.
