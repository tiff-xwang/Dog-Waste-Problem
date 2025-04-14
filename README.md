# The Dog Waste Problem in New York City
🐶💩

## Goal
My friends and I really experienced this problem firsthand. When it rains, there are poopy creeks on the streets that are purple, green, and yellow. I want to find out how pervasive the dog waste issue is and whether there are areas affected more than others.

## Findings
I found out there was a City Council hearing last May, where Council Members proposed a solution and said they used 311 service requests to measure the scale of the problem. I located Riverside Drive in Washington Heights as the worst spot to encounter dog waste and saw a continuous increase in the number of complaints in the past few years.
 
## Data & Workflow
All the datasets I used are in [docs](docs). 

First, I went to NYC Open Data for [311 call records](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data) from the first three months of the past 10 years because it was April 1, 2025 when I started my analysis and I wanted to see same-period year-over-year change. 

Then, I filtered for "Dog Waste" in the "Descriptor" column for data from 2022 to 2025, and "E8 Canine Violation" for data from earlier years.

Lastly, I plotted with Datawrapper and Folium.
 
