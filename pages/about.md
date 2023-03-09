---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="/objects/korea-unsplash.jpg" %}

{% include feature/nav-menu.html sections="Search Guide; Accountability - Collection Statement;About the Guide;About CollectionBuilder" %}

## Search Guide
Use the following attributes to find a film using the search function:
- Title	
- Director 	
- Description Keywords (e.g., colonial, Korean War, post-war)
- Subtitle Language(s)
- Release Year
- Historical Date
- Format (i.e., DVD, Blu-ray, Online)

**Note on Dates**
The historical date was determined by the film’s synoposis and/or in-film reference. For some films, the exact date of setting could not be determined, therefore it was mapped onto the nearest prominent date based on best judgement/guess.

If searching for a film about the 1980s, search "1980." The historical date and/or description will include this term.

If a film largely features flashbacks and covers a wide span of time, the film has been categorized based on its latest possible date. For example,

{% include feature/card.html header="국제시장 Kukche Sijang Ode to My Father" 
text="<p><strong>Release Year:</strong> 2015</p> <p><strong>Historical Date:</strong> 2015</p> <p><strong>Description:</strong> Follows the story of a protagonist across 60 years of his life. This begins from the Korean War (1950-1953), post-war life, Korean miners and nurses in Germany (1963), the Vietnam War (1964-1973), and the KBS Live Broadcast 이산가족을 찾습니다 (Finding Dispersed Families) in 1983.</p>" width="25" centered=true %}

This film is categorized under the historical date, 2015 and release year, 2015. However, all of the dates in the description are searchable using the search function as well.
## About CollectionBuilder

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

