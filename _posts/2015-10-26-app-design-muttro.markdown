---
published: true
title: App Design - Muttro
layout: post
---
Muttro was my first project after the basics section of the Bloc bootcamp. I had a new 10 week old puppy and suddenly found myself constantly searching for dog attractions. I decided to build an app dedicated to searching for all things dog related. 

Quickly I realized while using Apple Maps that the search capability just wasn't up to snuff with what users typically expect when searching for points of interest (POIs). To solve this, I used Yelp's API to power all searches made by the user, whether by category or by specific word search. This turned out to provide some benefits not just in terms of search results but also tracking categories. 

My second main task was building custom annotations and callouts for maps to identify categories for users to easily see what each POI was. For this I built both custom classes for both the annotation and callouts and used these whenever the user searched for POIs on the map. This also allowed me to control the image based on the Yelp API search categories once I had Yelp integrated into the search. 

Finally, I wanted to give the user the ability to save POIs to come back to them later, and to interact with a POI. This was achieved with a star button in the callout views and list views for POIs, and phone, web, and directions buttons for each POI. 

Overall I was pretty happy with this for my first project. You can find Muttro on the [iTunes Store](https://itunes.apple.com/us/app/id1014180036?mt=8), and take a look at the source code [here](https://github.com/tvieweg/Muttro/).


-<img src="http://a3.mzstatic.com/us/r30/Purple7/v4/0a/7f/80/0a7f8080-551d-d06b-1ca1-70b4ddeb2d17/screen322x572.jpeg" alt="Muttro" width="260">
-<img src="http://a4.mzstatic.com/us/r30/Purple7/v4/fa/bd/16/fabd1616-c099-3622-a5d3-4f9a2a5ccd58/screen322x572.jpeg" alt="Muttro" width="260">
-<img src="http://a5.mzstatic.com/us/r30/Purple5/v4/26/8c/ad/268cadfc-c9ac-bf61-d7ae-f37f89dd11e3/screen322x572.jpeg" alt="Muttro" width="260">