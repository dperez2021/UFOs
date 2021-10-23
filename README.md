
## Project Overview

THis project focuses on building a dynamic html webpage that accepts users inputs and filters accordingly to display information about UFO sightings during January 2010.
In order to perform their analysis, users will be able to input data that will display a filter on mulitple criteria's that include event data, city, state, country, and shape.

## Resource
- Data Source:  [UFO data](https://github.com/dperez2021/UFOs/blob/main/static/js/data.js)
- Software: HTML/CSS, JavaScript, Visual Studio Code, BootStrap

## Results

### Link to UFO Sightings webpage

The depoloyed webpage is accessible at https://dperez2021.github.io/UFOs/

### Page Layout

The index.html for this module displays the following:

![PAGE_LAYOUT](https://user-images.githubusercontent.com/88256967/138566690-7db53af5-4ca0-4783-a66d-5aa0148ad6a3.PNG)

The user can re-initialize the page by clicking the navbar "UFO Sightings" at the top left corner of the page.

### Page Filtering

The page can be filtered by different criteria's. For purposes of presentation I will filter by state using abbreviation 'fl' which is Florida and hit 'Enter' on keyboard and the website will display the results below:

![Search_by_fl](https://user-images.githubusercontent.com/88256967/138566751-0eb4c72e-2bdd-4b01-8107-b3a99b9631ea.PNG)

In addittion all filter parameters can be entered simultaneously.

## Summary

Some drawbacks include:
  - Webuser must press 'Enter' to display filtered data, instead of having a 'Filter' button present to click.
  - User cannot use UpperCase letters in filtering only lowecase.
  - User must click navbar 'UFO Sighting' to refresh page, but no instructions let them know.
Some way's to fix these drawbacks include:
  - Implementing a Filter button to display filtered data inputed.
  - Implement drop down lists for each criteria attempting to filter through.
  - Implement filtering via Upper or Lower case not stricltly lowercase.
  - Implementing a buttong to clear filtered inputs.
