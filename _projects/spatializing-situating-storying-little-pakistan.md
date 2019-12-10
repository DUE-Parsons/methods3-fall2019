---
layout: project-page
title: "Spatializing - Situating - Storying: Little Pakistan"
linkname: spatializing-situating-storying-little-pakistan
author: "Sana Akram"
tagline: "This project aims to bridge gaps and fill voids in the narratives surrounding the immigrant neighborhood of Little Pakistan, Brooklyn.  "
location:
    - place: New York, USA
project-link:
    - href: https://thenewschool.carto.com/u/akras030/builder/67ce4c81-2a40-437a-9754-02e59759eb8d/embed
    - href:  https://vimeo.com/377916589
    - href:  https://thenewschool.carto.com/u/akras030/builder/ad19cb80-e34a-46d1-ba59-a7c1982a57eb/embed
tags:
    - tag: Storytelling
    - tag:  Urban Community Portrait
    - tag:  Immigrant Neighborhood
    - tag:  Power of Place
    - tag:  Public History
thumbnail-path: img/spatializing-situating-storying-little-pakistan-/BH97eVq.jpg
img-folder: ../../img/spatializing-situating-storying-little-pakistan-/
timestamp: 12/7/2019 0:01:10
---

The history of immigration from the Indian subcontinent to the United States dates back to 1880s. With the partition of the Indian subcontinent, Pakistan came into being in 1947. Therefore, people already residing in the US who had a religious or geographical affiliation with the newly formed state were to be identified with the hyphenated identity of Pakistani-American. Following the formation of Pakistan, Pakistanis entered the US seeking education in American universities. The number of Pakistanis in the US between 1947 to 1965 is estimated to be around 2500 according to reports by U.S. Immigration and Naturalization Services. This was followed by two major immigration waves of Pakistanis to the US (1965-1980 & 1980-2000). Currently, approximately 453,000 Pakistani immigrants and their children (of second and third generations) reside in the United States and this number is likely to exceed 500,000 in the Census 2020. 

It is estimated that around 22% of this population resides in New York City-New Jersey-Southern Connecticut Metropolitan Area and according to the 2010 census, Pakistani Americans are the fifth largest Asian American group in New York City. These Pakistani populations are spread across various neighborhoods in the city and scholars of South Asian diasporas have suggest that they prefer to live either in multi-ethnic South-Asian neighborhoods (such as Devon Street in Chicago or Jackson Heights in New York City) or in suburbs. 

However, following the immigration wave of the 1980s, a neighborhood with high concentration of Pakistani-Americans emerged along Coney Island Avenue “between Avenue H and Newkirk Avenue” in Flatbush/Midwood area of Brooklyn. This has been termed as an “ethnic enclave” of Pakistani-Americans, better known as ‘Little Pakistan’. By 2000, the neighborhood was strong in numbers and according to its residents, it was booming and thriving. Things changed with 9/11 attacks, when Muslim communities in the US came under scrutiny and were subjected to discrimination, policing, and Islamophobic policies. 

This was the case for Little Pakistan. FBI raids, incarceration, disappearances, deportation, selective immigration, and special registration program induced fear in the people. Islamophobia and hate-crime became common-place, and the neighborhood is said to have lost around one-third of its Pakistani population during this period (Henderson 2019). This time is often termed as the era of Exodus. Between 15,000 to 18,000 Pakistani-Americans left the neighborhood (according to estimates from 2003) and either moved across the border to Canada, or immigrated to Western Europe, while some opted return-migration to Pakistan (Mohammad-Arif 2007). A number of faltering Pakistani businesses either closed down or were abandoned altogether.     

The neighborhood has been largely defined in relation to the 9/11 attacks; a simple search online shows a number of articles, all tying the neighborhood to the event in one way or the other. During my research about the neighborhood, I was able to identify gaps or voids in the narratives surrounding it. And therefore, I wanted to bring to light unheard stories from the neighborhood as narrated by its people. But in order to story a place, one has to first spatialize it and situate it. 

![]({{ page.img-folder }}Wi0LbNc.png)

And therefore, this project aims at: 

 * SPATIALZING: (Identify patterns of settlement of Pakistani community in the US and zooming in on NYC)
 * SITUATING: (Analyze the claim, “Little Pakistan, Brooklyn, is the densest area of Pakistani population in the US” - Analyze the claim, “Little Pakistan, Brooklyn, lost one-third of its population following 9/11”, Analyze the claim “Little Pakistan has regained its numbers”)
 * STORYING: (Bring forth narratives around the neighborhood of Little Pakistan, Brooklyn, by making a “story map” - exploring interactive mapping with images and sounds)

The project is spread on multiple scales: the US > New York City > Boroughs > Little Pakistan

![]({{ page.img-folder }}Bh7TJa2.png) 

I wanted to begin by delving into what data was available pertaining to the Pakistani population in the US and my initial instinct was to start by focusing on the emergence of Little Pakistan by mapping spread of Pakistani population in the area from the foundation years (1980s). However, this was not an easy process since the Pakistani population in the US has been categorized under the “Other Asian” category according to the US Census Bureau through various censuses. And therefore, population figures on the census-tract level were not available for the year 1980 and 1990, and were only made available from 2000 onwards. Furthermore, the only datasets offered by the US Census Bureau that have Pakistani population statistics are from American Community Survey (ACS) estimates (B05006) for Foreign-Born population. Which means that these figures do not include the second and third generation immigrants of Pakistani descent. And therefore, the maps that follow show Pakistani-born population in the US. This suggests that actual numbers and population densities of Pakistan-Americans would far exceed the numbers stated by US Census Bureau and used for the following maps.

SPATIALIZING:

The first map is a dot map showing every Pakistani (Foreign-Born) present in the US in 2017. The purpose of this map is to see the pattern of settlement of Pakistanis in the US; with New York City showing the densest populations, followed by Los Angeles, Chicago, Washington D.C, Houston, Dallas, San Francisco and Philadelphia, among others. According to the statistics, New York State has the largest (65,360) while Wyoming has the smallest (50) population of Pakistanis in the US. 

![]({{ page.img-folder }}Rjy5xtJ.png)

![]({{ page.img-folder }}sTrgw8t.png)


The map was made using the population figures from ACS 5 Year Estimates 2017 (B05006 - Foreign Born - South Central Asia – Pakistan). This required using Census Tract shapefiles for each state, downloaded from the US Census Bureau website and merging them in QGIS to form a single shapefile. This was followed by making a spatial join with the dataset having population figures for each census tract in each state. Once this was done, QGIS Research Tools allowed formation of random point inside each polygon corresponding to the Pakistani population figures. Furthermore, I added the State shapefiles to the map and using Analysis Tools in QGIS, points inside polygons were counted for each state. The shapefiles were then used to create a CARTO map that allows you to see the settlement patterns and also to click on each state and see the population figures. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/akras030/builder/67ce4c81-2a40-437a-9754-02e59759eb8d/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe> 

SITUATING:

The second map focuses on Boroughs of Brooklyn and Queens and further on the neighborhood of Little Pakistan in the area of Flatbush/Midwood, Brooklyn. The purpose of this map is to analyze three claims about the neighborhood. The first one being, “the neighborhood lost one-third of its Pakistani population following 9/11” and the second one being, “the neighborhood is the densest population of Pakistanis in the US”; the third being that Pakistani population has returned to the neighborhood. Since no datasets pertaining to Pakistani population were available for the years between 2000 to 2010, it was not possible to analyze the first claim with the information at my disposal. Therefore, I focused on the second and third claim and made a map showing density of Pakistani (Foreign-Born) population for each census-tract in NYC. 

This map not only confirmed the neighborhood of Little Pakistan to be the densest Pakistani neighborhood in NYC but also showed that it was among the very few neighborhoods in NYC where Pakistani (Foreign-Born) population maintained its density (the comparison between top three densest census-tracts in various neighborhoods of NYC features Little Pakistan the most with other neighborhoods like Flushing and Brighton Beach emerging as major hubs).

![]({{ page.img-folder }}RxTqCLg.jpg)

The maps below illustrate this and also suggest that Queens has lost its position as the Borough with highest percentage of Pakistani population and there is a gradual increase of Pakistani population in neighborhoods that lie in Brooklyn. These choropleth maps were made for the years 2000, and then from 2010-2017. Following animation shows the changes in patterns for each year.  

<iframe src="https://player.vimeo.com/video/377916589" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

The figure below illustrate the changes in population percentages for Brooklyn and Queens.

![]({{ page.img-folder }}fhrSQIk.jpg)

These maps were made using the ACS five-year estimates for each year. Population figures were normalized to show population density per square-km and choropleths were made for each year on QGIS. 

STORYING:  

The third map aims to begin storying the neighborhood and was an endeavor to explore interactive mapping of qualitative data with audio, video and text-based narrative. This resulted in a sound-map of the neighborhood. The descriptions were made such that they serve as prompts. Zoom-dependent styling with CARTOCSS allowed for an unraveling experience as the point for places, memories and pathways of walks from the subway appear only when one zooms into the map. This map required adding audio tags and images to the popups on Carto using HTML. 

![]({{ page.img-folder }}nly2dFt.png) 

![]({{ page.img-folder }}nnRXhio.png)

![]({{ page.img-folder }}4uvqH8M.png) 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/akras030/builder/ad19cb80-e34a-46d1-ba59-a7c1982a57eb/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


