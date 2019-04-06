# Lack of electric car charging points 'putting off drivers'

In March 2019 **Aimee Stanton** [reported](https://www.bbc.co.uk/news/uk-47696839) a "patchy" network of charging points was discouraging UK drivers from embracing electric cars, as her analysis found more than a third of local authorities have ten or fewer locations where drivers can plug in their vehicles, with wide variation across the country.

The BBC's Shared Data Unit analysed data from Open Charge Map, a crowd-sourced website of charging locations. Not every location will feature in Open Charge Map, but it aims to be a "reliable single point of reference for charging equipment location information". There is no similar resource from the government.

As part of the story we used the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula) to perform 49 million calculations for each distance (as the crow flies) between each of the 7,000 points, and then store the shortest one. 

In a Twitter thread, Peter Sherlock [explained why the data was used and how the team worked with that](https://twitter.com/petesherlock79/status/1114089816671563777)

## Get the data 

* [Analysis, with sheets for England, Northern Ireland, Scotland and Wales](https://docs.google.com/spreadsheets/d/1bT0F0sj1t4_7uFrtr071tqW_yilRcl0iLshlKxmNU0Y/edit#gid=1583759189)

## Quotes and interviews

* Alex Banks from Exeter, owner of a Nissan Leaf
* Nicholas Lyes, head of roads policy, RAC 
* Bridget Fox, Campaign for Better Transport
* Spokesperson, the Department for Transport (DfT)
* Spokesman, Scottish Government

## Visualisation

* Interactive map: Average distance between charging locations, by authority
* Bar chart: Local authorities with the most charging locations

## Briefing pack

* [A full briefing pack on the story can be found here](https://docs.google.com/document/d/1vs9WsXXeoCndHQL7a1NLrOB7-qCgGLSIQbS8goYMAoA/edit)

## Code

* [RMarkdown notebook explaining how the distances were calculated](https://github.com/BBC-Data-Unit/electric-car-charging-points/blob/master/calculatingnearestpoints.Rmd)



