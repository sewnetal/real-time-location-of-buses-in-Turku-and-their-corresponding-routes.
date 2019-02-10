# real-time-location-of-buses-in-Turku-and-their-corresponding-routes.
# Föli APIs
# The real-time VM - Vehicle Monitoring data
 http://data.foli.fi/doc/siri/v0/vm-en
 http://data.foli.fi/doc/siri/v0/vm-en
 http://data.foli.fi/doc/gtfs/v0/index-en



# Requirements

The list of bus routes in the drop-down list created based on the data provided by the ‘routes’ API

http://data.foli.fi/doc/gtfs/v0/routes-en

When clicking the “Show route” button you draw on the map the route for the bus line selected from the drop-down list 

https://developers.google.com/maps/documentation/javascript/examples/polyline-

When clicking on the “Show bus” button indicates on the map the current location of all buses operating on the route (bus line) selected from the drop-down list

The API (http://data.foli.fi/doc/siri/v0/vm-en) is made such that the returned data contains the position of all buses. 

When clicking on the “Refresh” button, the location of all buses operating on the selected route is refreshed

