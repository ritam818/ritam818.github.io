---
layout: post
title:  "What Kind of Apartments Are Being Offered in Airbnb?"
date:   2025-05-12 14:34:25
categories: 
tags: 
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.JPG
---
We want to get a deep understanding of the Airbnb market in Europe to see the impact that it has in European societies and the consequences of this touristic model. Here, we look at the most essential thing: the Airbnb apartments themselves and the people who stay in them. Who are they? Are apartment conditions in Athens significantly different from apartments in London or Paris? Which city has the most expensive listings and why? Let’s try to put some light in this darkness!
First, let’s look at the price distribution of listings in different cities.

![Boxplot illustrating the price distribution across the eight cities included in the analysis.](/assets/context/airbnb_price_distribution.png)

Here, we see that, coincidentally, Amsterdam (which is the city with the fewest number of listings) is the one with the highest prices, targeting higher-income tourists. On the other hand, cities like Athens or Prague seem to offer mainly cheaper apartments, catering to budget-conscious tourists. Furthermore, Barcelona has a wide range of prices, with offers for both luxury lovers and people on a budget. Even though in 2024, luxury tourism [represented](https://metropoliabierta.elespanol.com/economia/20250131/el-turismo-de-lujo-aunque-crece-tan-solo-alcanza-seis-cada-cien-reservas-en-barcelona/919908045_0.html?utm_cmp_rs=linksinline) only 6% of all bookings,  in 2025, the Virtuoso Luxe Report [established](https://metropoliabierta.elespanol.com/economia/20250325/barcelona-la-segunda-ciudad-del-mundo-preferida-para-el-turismo-de-lujo/933906624_0.html) Barcelona as one of the most desirable destinations for luxury tourism. The city government has [stated]( https://metropoliabierta.elespanol.com/informacion-municipal/20240610/collboni-activara-las-palancas-para-reducir-la-presion-turistica-en-zonas-mas-tensionadas-de-barcelona/861913846_0.html?utm_cmp_rs=linksinline) its desire to attract “quality tourism”  and, together with its thriving cultural life, wonderful weather and world-class culinary offerings (including Disfrutar, winner of The World’s 50 Best Restaurants in 2025) it is positioning itself as an appealing city for luxury lovers. Of course, Airbnb hosts are aware of these trends and adjust their offerings accordingly.


Now, moving on to the types of apartments offered, we have focused on the types of rooms and the types of guests.
Regarding the types of rooms, most of the listings in all the cities are entire homes or apartments. Then, private rooms have some popularity in cities such as Amsterdam, Barcelona, London or Madrid. The percentage of hotel rooms and shared rooms listings are generally very low. This aligns with the classic image that the general public has of an Airbnb apartment: in most cases, an entire apartment that they can rent for a few days or, at most, a private room in a bigger apartment shared with other customers.

![Stacked barplot showing the proportion of Airbnb listings by room type and city.](/assets/context/stacked_roomtype.png)

Regarding the types of guests, the figure below shows that in Amsterdam, London and Paris the most popular types of listings are those for couples. In the rest of the cities, the listings with the highest offer are those for families or small groups of between 3 and 5 people. Besides, listings for large groups are relatively popular in cities like Prague, Barcelona, Vienna or Athens. If we connect this with the price distribution, that showed that these cities have many listings at cheaper prices, we could establish a profile of travelers that visit this cities: the *frugal group traveler*. These could be, for instance (as data [suggests] (https://www.wysetc.org/2023/12/gen-z-otas-and-group-travel/)), young people going on a trip with their large group of friends. These travelers can be culturally curious and engaged but they can also become a disturbance for locals. Furthermore, budget-travelers tend to choose their trip destinations based on price, so the fact that Airbnb can offer low prices for them means that it is likely that (with the help of low-cost airlines) it creates a market that was not there before and this can have consequences in local economies, housing markets and lifestyles.

![Stacked barplot showing the proportion of Airbnb listings by type of guests and city.](/assets/context/stacked_guesttype.png)

After taking a closer look at the types of people who use Airbnb in these European cities and how are the places where they are staying, we can also analyze **when** are they staying there. Find below an interactive heatmap of the occupancy rate of the listings on the different months and days of the week. Feel free to explore the data of the different cities to discover if your own traveling trends match those of Airbnb users.

<figure>
  <iframe src="/assets/context/bokeh_occupancy_heatmap_tabs.html" width="100%" height="600px" style="border:none;"></iframe>
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
    Interactive heatmap of the average Airbnb occupancy rate by day/month.
  </figcaption>
</figure>

It is shown that in general there are no massive differences in occupancy rates between the weekdays and the weekend, so it does not look like tourists in general use Airbnb with a special focus on weekends. For instance, Fridays in the month of June in Paris are the day of the week with the lowest Occupancy rate.  On the other hand, in cities like Barcelona, Madrid and Vienna, Fridays are the most popular day in the month of June. This figure shows also the seasonality of occupancy in the different cities. For instance in London, the most popular months are April, May and June. Moreover, London, Madrid and Prague seem to have similar seasonality patterns. 


Finally, to conclude this analysis on the types of Airbnb listings offered, we can take a closer look at the prices of the apartments. You can freely explore this in the interactive figure below.

<figure>
  <iframe src="/assets/context/airbnb_histograms.html" width="100%" height="600px" style="border:none;"></iframe>
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
    Interactive price histograms by city.
  </figcaption>
</figure>

Here, we can see that most of the price distributions are skewed towards the left (meaning lower prices). For example, Athens has around 41% of listings with a price of around 40-70 € per night, highlighting the large potential of the city to attract budget-conscious travelers. The price histograms for Vienna and Prague are quite similar, with both cities having around 25-30% of listings with a price of around 70-100 € per night. Cities like Barcelona, Paris or London do not have such significant spikes and have perhaps a broader distribution. Besides, in the case of Amsterdam, its distribution has significantly lower spikes than the rest and is more skewed towards the right, meaning that it has higher prices.


Thus, data seems to point that different cities are focused on different types of Airbnb listing markets. Cities like Prague, Vienna or Athens seem to cater to frugal tourists that might sometimes travel in group. In contrast, Amsterdam, seems to focus on travelers with a higher willingness to spend. Other cities like Barcelona, Paris or London seem to look for a broader audience. For instance, Barcelona aims to target both luxury tourists and groups of budget-friendly youngsters.
