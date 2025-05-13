---
layout: post
title:  "Special occasions: The Taylor Swift effect"
date:   2025-05-12 14:34:25
categories: 
tags: 
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.JPG
---
We wonder how special occasions affect the Airbnb European market. Our concern is that in specific periods of time like Christmas, Easter, Summer holidays or when there is a big event happening in the area, the city can get really overcrowded. In such situations, locals might not feel comfortable in their own city, and they might feel like they have no other option but flee the city during these specific days. 


To study how special events might oversaturate the market in European cities, we have used an interactive time series plot of occupancy rates of Airbnb listings over time. 


<figure style="margin-bottom: 0;">
  <iframe src="/assets/special_occ/bokeh_occupancy_timev2.html"
          width="100%"
          height="450px"
          style="border:none; display:block; margin:0 auto;"></iframe>
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
    Interactive plot of Airbnb occupancy rates over time by city.
  </figcaption>
</figure>



Here, we can see some general trends that affect most cities. For instance, after the beginning of the summer season in 2024, there’s a general decreasing trend in occupancy rates and after Christmas 2024 most cities experience an increase in occupancy leading to a stable occupancy rate. Then, around Easter 2025, most cities experience a new sudden increase in occupancy that leads to a higher stable occupancy rate.


Beyond the general trends, we observe also individual trends for the different cities. For example, in Amsterdam the occupancy rate does not fluctuate as much as in other cities and it always stays at a level above 70%. On the other hand, there is Athens, that starts the summer at around 80% and it experiences a steep decline in occupancy that leads to having occupancy rates below 20% right before the Christmas season. Interestingly, in Paris, where the Olympic games were held in Summer 2024, there is a steep decline in Occupancy right before the Olympics and then a steep increase right after. This could indicate that tourists tried to avoid being in the city while the Olympics were being held. This is aligned with reports [stating]( https://www.euronews.com/business/2024/07/31/paris-tourism-takes-a-plunge-despite-excitement-of-olympics-2024) that Paris tourism decreased despite the excitement of the Olympic games. Moreover, although it may at first seem like the Olympics result in an huge boom of tourists, analyst John Grant of aviation intelligence company does not believe this statement and about hosting the Olympics, [says]( https://www.euronews.com/business/2024/07/31/paris-tourism-takes-a-plunge-despite-excitement-of-olympics-2024)  that “It just never quite achieves and delivers what's expected”. Knowing this, one could even argue that without the Olympics there would have been more visitors. This could be a cautionary tale for cities that are willing to host huge events such as the Olympics, given that the city will have to spend a large amount of money and resources on the preparation and organization of the event and there might not be any significant social or economic gains for the city and the local community.


Another city that also held a large sports event during this period is Barcelona. Much to the dismay of the local community, during July-August 2024, the city hosted the 37th Louis Vuitton America’s Cup. To organize the event, local authorities [invested]( https://www.catalannews.com/business/item/americas-cup-leaves-35m-loss-for-barcelona-port-despite-positive-impact) over €3.5 million and there were several protests against it. Looking at the time series plot, it does not seem like there was a large increase in tourism as a consequence of the tournament.


In the figure we can also see some specific spikes in some specific short periods of time. For example, in Vienna, we see two big spikes during the month of August. To take a closer look at how specific events affect occupancy, we have used an interactive calendar plot. 


<figure style="margin-bottom: 0;">
  <iframe src="/assets/special_occ/bokeh_tabsv2.html"
          width="100%"
          height="270px"
          style="border:none; display:block; margin:0 auto;"></iframe>
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
    Interactive Map showing amount of tourism and Airbnb earnings for the selected cities.
  </figcaption>
</figure>


Studying these calendar plots for the different cities we have come across an interesting phenomenon that we have dubbed “The Taylor Swift effect”. The reason for this is that occupancy rates experience a significant increase in the dates around the singer’s planned concerts in the cities of Amsterdam (July 4-6) and Vienna (August 8-10). In Vienna, the concerts were not held in the end due to a foiled terrorist attack plot. Nevertheless, fans [still](https://www.bbc.com/news/articles/cp35wxendego) came out on Vienna’s streets to show their support to the artist and sing their songs.


Besides the American singer’s concerts, there are other events that can be attributed to spikes in occupancy in specific days. For instance, in Amsterdam there’s a significant spike in occupancy during 17-20 October and this coincides with Amsterdam Dance Event ([ADE]( https://www.amsterdam-dance-event.nl/en/)), which is the world’s largest electronic music festival and conference. Furthermore, in Madrid we can see some spikes in the last weekend of June and the two first weekends of July. Around those dates, Madrid Pride ([MADO]( https://www.elmundo.es/como/2024/07/03/66851405e85ecee4478b45b4.html)) 2024 was taking place in the city, with the main parade taking place on Saturday, July 6. Moreover, there’s a spike in occupancy in London around June 16, 2025, which is when Beyoncé’s Cowboy Carter tour will make a stop at the British capital.


With this, we can understand better what drives spikes in Airbnbs occupancy rates during special periods and occasions. It seems that huge sports events like the Olympics in Paris or the America’s Cup in Barcelona do not attract tourism (although they do cause huge public investments and use of resources). However, big concerts or cultural/leisure events like Taylor Swift’s Eras Tour, Amsterdam’s ADE or Madrid’s Pride do correspond to a large increase in occupancy.

