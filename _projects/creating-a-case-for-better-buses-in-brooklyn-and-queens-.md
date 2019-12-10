---
layout: project-page
title: "Creating a Case for Better Buses in Brooklyn and Queens "
linkname: creating-a-case-for-better-buses-in-brooklyn-and-queens-
author: "Maanasa Sivashankar"
tagline: "This project aims at creating a case for better buses in Brooklyn-Queens by highlighting the existing transit gaps in the two boroughs. "
location:
    - place: Brooklyn-Queens Boroughs, New York City, NY
project-link:
    - href: https://sivam516.carto.com/builder/2318b0aa-4eee-49a5-9ec9-9daf65eb3e2d/embed
tags:
    - tag: Transportation
    - tag:  Transit Equity
    - tag:  Infrastructure Investment 
thumbnail-path: img/creating-a-case-for-better-buses-in-brooklyn-and-queens-/ak7xuDE.jpg
img-folder: ../../img/creating-a-case-for-better-buses-in-brooklyn-and-queens-/
timestamp: 12/7/2019 0:30:35
---

In Jan 2016, Friends of the BQX released a proposal for a streetcar system to run along the Brooklyn-Queens waterfront. The plan claimed to be bridging existing transit gaps along the Brooklyn-Queens neighborhoods, serving “people in need” by connecting working-class people to more jobs and employment opportunities while being a fast and accessible means of public transit. The proposal, backed by Mayor de-Blasio, boasts self-funding by the means of value-capture in the form of inflated real estate values. This, in turn, would result in heavy displacement and an increase in rents in these neighborhoods. 

In this context, I wanted to evaluate and understand the existing condition of the Brooklyn-Queens transit systems. Identify where improvement is needed and who are the current commuters that face challenges. 

 A 2011 study by the Center for an Urban Future estimated that more than 150,000 people commute between Brooklyn and Queens. More than 20,000 people work in Hunts Point and at the Kings County-SUNY Downstate medical centers in East Flatbush, and more than 55,000 work at JFK Airport in Queens. More recently, 2017 data shows that approx. 200,000 healthcare professionals work in Brooklyn or Queens, that have 21 hospitals and 40% of NYC’s nursing homes. This is only a portion of the commuters in the two boroughs which substantiated the need for better transit.  

I started my analysis by mapping the subway entrances in the two boroughs and creating a buffer of 0.4 miles around the entrances as a 10-minute last-mile radius. I made the buffers white to subtract the areas that have access to a subway line. I repeated the same for express bus lines across the two boroughs and overlayed the maps on income per capita data. 

![]({{ page.img-folder }}l0YNOC5.jpg)

![]({{ page.img-folder }}EMxpGwG.jpg)

As one would expect, more affluent people have better access to transit stations and stops white the transit gaps show a clear indication of low-income populations bearing the brunt of transit deserts. To understand the nature of the areas that have these gaps, I overlayed the buffers on a land-use map. Most areas are low-income residential neighborhoods or older manufacturing zones. 

![]({{ page.img-folder }}iNR5wRr.jpg)


To further evaluate the extent of these deserts and what mode of transit would best serve then, I measured the gaps by rasterizing the buffers and measuring the largest distances between two buffered points. This indicated that the last mile gaps in this map are all under 3 miles making any form of Micromobility a convenient FLML solution (usually for all commutes under 5 miles).  So the next set of maps show citibike stations and public provisions for cyclists (cycles racks + tracts)

![]({{ page.img-folder }}L3Y20SB.jpg)
![]({{ page.img-folder }}IV06bmZ.jpg)

Again, most of the private and public infrastructure are concentrated in affluent areas across the two neighborhoods. My next step was to look at regular SBS or MTA bus infrastructure to see its distribution across these two boroughs. 

![]({{ page.img-folder }}WhVsRd8.jpg)

This map shows the spread of bus stops and bus stops with bus shelters. The demographic using buses in these areas are largely low-income populations of color or senior citizens. I attended an MTA meeting in my neighborhood to understand qualitatively the issues that riders face. Most citizens who showed up demanded better bus shelters and seating across the all the stops to make the quality of their journey better. They said they would put up with the delays if they could just sit down. 
In spite of irregularities or inefficiencies, bus stop buffers are a lot more widespread and cover the entire region. Like with the previous maps, this doesn’t necessarily indicate access to your destination (work/leisure). So I filtered out the buses that move only across the two boroughs to understand how many bridges the Brooklyn-Queens transit journeys that the BQX had set out to fix. 

![]({{ page.img-folder }}mm25ScC.jpg)

I also overlayed the subway lines that do move between the two boroughs with or without moving through manhattan (since only the G line works exclusively between Brooklyn and Queens). 

I finally interview riders alliance members who exclusively advocate for issues that bus riders face while using public transit across Brooklyn, Queens, and the Bronx. Their project “Woes on the Bus” is a collection of qualitative inputs of complaints or challenges that riders face. To understand where most complaints come from, I decided to map the complaints next to the buses that the riders have an issue with. The interactive carto map shows a range of riders’ complaints and the transit deserts to see if there is a correlation between the two. 

While my exercise to understand where transit gaps currently exist is still ongoing, one thing that is absolutely clear is that the current working-class population, accessing employment opportunities in the two boroughs aren’t going to be requiring a waterfront express to sustain them. It also evident that the options for transit along the BQX’s proposed line are sufficient with the subway lines and the bus lines creating a robust network along that route. 

Construction costs for SBS routes range between $7 million and $27 million, which means that even at its highest, capital construction costs for SBS would amount to about one percent of the total cost of building the BQX, all while providing about the same added capacity to the system. Additionally, Buses are cheaper- serving working-class populations, accessible and flexible as an infrastructure system. 
