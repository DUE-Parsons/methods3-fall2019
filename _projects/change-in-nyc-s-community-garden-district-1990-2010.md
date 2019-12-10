---
layout: project-page
title: "Change in NYC's Community Garden District: 1990-2010"
linkname: change-in-nyc-s-community-garden-district-1990-2010
author: "Matthew Morowitz"
tagline: "By rediscovering demolished community gardens in the East Village, I also observed broader changes in the neighborhood over a 20-year period."
location:
    - place: New York, NY, USA
project-link:
    - href: https://thenewschool.carto.com/u/morom531/builder/9a57d97d-83d7-4327-8445-a71c8fa8c5f0/embed
tags:
    - tag: Community Gardens
    - tag:  East Village
    - tag:  Alphabet City
    - tag:  Reclaimed Space
    - tag:  Demolished Spaces
    - tag:  Rediscovering Space
thumbnail-path: img/change-in-nyc-s-community-garden-district-1990-2010/YR9HOnl.jpg
img-folder: ../../img/change-in-nyc-s-community-garden-district-1990-2010/
timestamp: 12/5/2019 19:40:39
---
From 1990–2010, NYC saw major shifts in population, income, and even the appearance of the built environment. Yet, neighborhoods like the East Village seemed to buck this trend in the popular mentality based on a persona of counter-cultural resistance and status as an ethnic enclave.  However, preconception is not reality and the neighborhood–particularly the section known as “Alphabet City”–has seen significant changes to both its historic Latinx population, and the community gardens that helped define the area as NYC’s “Community Garden District.” Using the locations of the community gardens (past and present) as a map, I took a look at the census block data that correspond to these spaces to see how this area changed over this twenty-year period. 
Using data from a variety of sources (city-level, federal, anecdotal), I was able to create maps that help make visible hidden information about, and lost histories of, community gardens.  Additionally, I used garden locations–both current and demolished–as a framework to explore how population and demographics have changed around these spaces within the period of 1990-2010, when gardens saw their greatest threats and the city saw the beginnings of its current gentrification.
To begin my explorations, I made a map in QGIS of the current Green Thumb community gardens.  Green Thumb is the city agency responsible for providing support to the gardens and licensing these spaces to the individual gardens’ members.  On their website, they have an interactive map and list of all currently licensed gardens, along with their addresses and pop-up information about ownership.  I was able to gather the locations of the current gardens that are within Alphabet City, a sub-neighborhood of the East Village between Avenues A and D (though I also included a couple of gardens between Avenue A and 1st Avenue), geocode them, and put them into a QGIS map.  

![]({{ page.img-folder }}kbOXhth.jpg)

However, just because this is what the landscape of Green Thumb gardens looks like, doesn’t mean these spaces are all the same.  Community gardens are a mosaic; each space has different zoning (as seen above) but, most importantly, ownership, which generally dictates how the gardens are utilized.  As you can see from my map below, though the gardens are mostly owned by the NYC Parks Department, other entities–public, private, non-profit–also lay claim to these spaces, something that is not readily apparent from a casual glance at Green Thumb’s own maps.

![]({{ page.img-folder }}pBB6J86.jpg)

While the neighborhood still has an impressive amount of community gardens, these spaces only make up what managed to survive area after the attacks to the movement by the Giuliani mayoral administration in the 1990’s. 39 community gardens currently exist in my site of exploration; when I dove deeper into researching these spaces, I discovered that there used to be 26 more gardens previously within Alphabet City.  Over the last twenty years, real estate development in the neighborhood had caused many of these gardens, which were established on vacant city- or privately-owned lots, to be demolished and replaced with residential apartments. Different local groups, such as Earth Celebrations and the Sixth Street Community Center, had compiled lists and simple maps of gardens in the neighborhood that were demolished.  I then took this information and began the painstaking process of finding each one.  By comparing the lists and simple maps with building lots on the NYC GIS, along with 1980’s tax photos from the NYC Department of Finance, I was able to make educated guesses as to where these spaces once existed.  The result became a map in Carto with pop-ups highlighting each space, the year it was demolished, a link to the tax photo, and any pictures or qualifying information I could find from the aforementioned sources.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/morom531/builder/9a57d97d-83d7-4327-8445-a71c8fa8c5f0/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

With these new garden points, I shifted my focus to change in the neighborhood’s demographics within this twenty-year time period.  As the East Village/Alphabet City is an historically Latinx neighborhood, I wanted to see if the same forces affecting the displacement of garden spaces were also affecting this community.  I obtained census race data for the neighborhood from NHGIS and joined it with the census block shapefiles they also provided in order to get as granular as possible with the data.  I then selected the blocks that contained gardens.

![]({{ page.img-folder }}le9Nq71.png)

After exporting these block groups for each decade, I normalized the data on each new block group’s attribute table and created a choropleth to see what percentage of each block was Latinx compared to the total population.  What I discovered seemed to align with my hypothesis that this racial group was seeing displacement from this area (though I excluded one of the census blocks that contained outlier data compared with the others selected).
 
![]({{ page.img-folder }}6DyOX59.jpg)

![]({{ page.img-folder }}Ij85azU.jpg)

![]({{ page.img-folder }}0YWgT1c.jpg)

Over this twenty-year period, these census blocks saw a 17.2% total increase in population, yet a decrease in the Latinx population by 13.6%.  The area itself also saw a loss of about 40% of its community gardens.  While perceptions about the East Village’s history and character still persist, the reality shows that this may all be as part of marketing ploys to draw new residents to rent or purchase in an “authentic and diverse” neighborhood.  
