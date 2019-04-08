# Lack of electric car charging points 'putting off drivers'

![](https://ichef.bbci.co.uk/news/660/cpsprodpb/63C5/production/_106314552_charging1.jpg)

In March 2019 the BBC Shared Data Unit [reported](https://www.bbc.co.uk/news/uk-47696839) a "patchy" network of charging points was discouraging UK drivers from embracing electric cars.

Our analysis found more than a third of local authorities had ten or fewer locations where drivers could plug in their vehicles, with wide variation across the country.

We analysed data from Open Charge Map, a crowd-sourced website of charging locations. Not every location will feature in Open Charge Map, but it aims to be a "reliable single point of reference for charging equipment location information". There is no similar resource from the government.

As part of the story we used the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula) to perform 49 million calculations for each distance (as the crow flies) between each of the 7,000 points, and then store the shortest one. 

In a Twitter thread, Peter Sherlock [explained why the data was used and how the team worked with that](https://twitter.com/petesherlock79/status/1114089816671563777)

The Shared Data Unit makes data journalism available to news organisations across the media industry, as part of a partnership between the BBC and the News Media Association. Stories generated by the partnership included:

The story was also used by the [BBC News Channel](https://www.youtube.com/watch?v=jNZPAQP4y2s&feature=youtu.be), BBC Radio 5 live, BBC Radio Norfolk, BBC Radio Lancashire, BBC Three Counties Radio and BBC Hereford & Worcester.
 

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

## Background and briefing

* [A full briefing pack on the story can be found here](https://docs.google.com/document/d/1vs9WsXXeoCndHQL7a1NLrOB7-qCgGLSIQbS8goYMAoA/edit)

## Code

* [RMarkdown notebook explaining how the distances were calculated](https://github.com/BBC-Data-Unit/electric-car-charging-points/blob/master/calculatingnearestpoints.Rmd)



