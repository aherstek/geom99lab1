# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?avoid=highways&mode=bicycling&origin=place_id:ChIJ4ZhursSicVMR9Rd8yCJZ1wc&destination=place_id:ChIJc7hqMilUdFMRmOqqx5po2rU&waypoints=Calgary+Tower|Calgary+Central+Library&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```


Copy/paste the JSON results and save them into the empty file ```mydirections.json``` in this repository

## My URLs
From one silly landmark to the next! I love visiting quirky 'side of the road' attractions and here are 2 I have visited in Alberta. 

My directions are from the Okotoks Erratic to a statue of a pig named Francis. This route avoids highways and takes a bike route,
as I am an avid road cyclist myself. I have put two checkpoints while travelling through Calgary at the Central library (an awesome study spot!)
and the Calgary tower (I had to add an obligatory tourist stop, lol).

### Simple option:
Origin PlaceID: https://www.google.com/maps/place/?q=place_id:ChIJ4ZhursSicVMR9Rd8yCJZ1wc - Okotoks Erratic
Destination PlaceID: https://www.google.com/maps/place/?q=place_id:ChIJc7hqMilUdFMRmOqqx5po2rU - Francis the Pig Statue
### Efficient option
Orgin PlaceID: https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJ4ZhursSicVMR9Rd8yCJZ1wc&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
Destination PlaceID: https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJFfiCrdo4Qm0RqPwuOAVtaj8&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE


____
## Rubric

Note: MarkDown (.md) documents are not HTML and therefore are best viewed in the github.com website, not on the pages github.io page. Marking will occur using the github.com source. 

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown and results in the JSON file with a unique origin and destination in directions earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%. Explore the API documentation for parameters we have not used.
4. Tell the story of your route. Include more than 2 "stops", and/or including additional links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%.

