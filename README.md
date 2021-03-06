# Yelp
iOS bootcamp 2017 project 2 

This is an iOS demo application for displaying and querying restaurants informaton using the [The Yelp Search API](https://www.yelp.com/developers/documentation/v2/search_api).

Time spent: 22 hours spent in total

Completed user stories:

Search results page
 * [x] Required: Table rows should be dynamic height according to the content height.
 * [x] Required: Custom cells should have the proper Auto Layout constraints.
 * [x] Required: Search bar should be in the navigation bar.
 * [x] Optional: Infinite scroll for restaurant results
 * [ ] Optional: Implement map view of restaurant results
 
Filter page
 * [x] Required: Implemente the follwoing filters : category, sort (best match, distance, highest rated), distance, deals (on/off).
 * [x] Required: The filters table should be organized into sections as in the mock.
 * [x] Required: Use the default UISwitch for on/off states. 
 * [x] Required: Clicking on the "Search" button should dismiss the filters page and trigger the search w/ the new filter settings.
 * [x] Optional: Implement a custom switch
 * [x] Optional: Distance filter should expand as in the real Yelp app.
 * [x] Optional: Categories should show a subset of the full list with a "See All" row to expand.
 * [ ] Optional: Implement the restaurant detail page.

 
Notes:
Extra features implemented:
 * [x] User sees loading state while waiting for Yelp API. 
 * [x] Filters view cateogries section shows currently the number of options selected when the section is collapsed. 


Walkthrough of all user stories:

![Video Walkthrough](Yelp.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).
