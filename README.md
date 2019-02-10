# real-time-location-of-buses-in-Turku-and-their-corresponding-routes.
#Föli APIs
# The real-time VM - Vehicle Monitoring data:
- http://data.foli.fi/doc/siri/v0/vm-en
# http://data.foli.fi/doc/siri/v0/vm-en
- http://data.foli.fi/doc/gtfs/v0/index-en



Requirements:
 The list of bus routes in the drop-down list should be created based on the data provided by the ‘routes’ API:
o http://data.foli.fi/doc/gtfs/v0/routes-en
 When clicking the “Show route” button you should draw on the map the route for the bus
line selected from the drop-down list
o Have a look at how to draw simple polylines on google map here:
https://developers.google.com/maps/documentation/javascript/examples/polyline-
simple
 When clicking on the “Show bus” button you should indicate on the map the current location of all buses operating on the route (bus line) selected from the drop-down list
o The API (http://data.foli.fi/doc/siri/v0/vm-en) is made such that the returned data contains the position of all buses. You will need to parse the data to extract only the buses corresponding to the selected route (checking the values for ‘publishedlinename’). (To visualise the server response in a human readable way use following url: http://data.foli.fi/siri/vm/pretty )
 When clicking on the “Refresh” button, the location of all buses operating on the selected route is refreshed

