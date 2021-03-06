---
layout: single
title: "The way a Data Scientist analyzes an Earthquake!!"
author: Ashish Tele
excerpt: "How can a happy journey turn to a scary experience 😱. One of the lifetime experiences everyone should have 🙂. I tried to explore the facts through data analysis."
description: "How can a happy journey turn to a scary experience 😱. One of the lifetime experiences everyone should have 🙂. I tried to explore the facts through data analysis."
permalink:
comments: true
tags: ["Data Science","Earthquake","Data Mining","Data Engineering","Pyhton","R","Death Valley","CA","search"]
published: true
comments: true
author_profile: false
header:
  teaserlogo:
  teaser: /images/earth_q_2.PNG
  image: /images/earth_q_2.PNG
  caption: "courtesy: Reddit.com"
---
Hi All, 

I am writing this blog post to share my experience of an earthquake! We were traveling from San Diego to Las Vegas through the Death Valley. We started our journey early morning to reach Vegas on time. We were enjoying the scenic view and capturing the moments. It was a hot day (105F). We decided to stop to click few pictures and fortunately, the time was perfect (scary thought!) to experience my first earthquake.

I was capturing moments through my iPhone. You can determine the location where you clicked the picture. To extract the metadata, I used the **ExifWizard** mobile application. It gives most of the information we require.

The below image gives the timestamp and coordinates of the location. We get many more features just through one single image captured.

<p align="center">
  <img width="300" height="400" src="/images/img_4_meta.png">
</p>


There are many sources available which provide the accurate information about the natural calamities. **Volcanodiscovery** is one of them. Let's see the timing of the earthquake and its epicenter:

Source: [Volcanodiscovery](https://www.volcanodiscovery.com/earthquakes/2019/07/04/17h33/magnitude6-CA-USA-quake.html)

 
<p align="center">
  <img width="500" height="250" src="/images/earth_q_1.PNG">
</p>


We can calculate the distance based on the latitude and longitude coordinates. I used **Google map distance finder** to calculate the 
distance between the points.

<p align="center">
  <img width="500" height="250" src="/images/dist_1.PNG">
</p>

Here starts the scary part. we were this much away from the epicenter!

<p align="center">
  <img width="500" height="400" src="/images/dist_img_2.PNG">
</p>

So, **25KM**, that's it!!

[Volcanodiscovery](https://www.volcanodiscovery.com/earthquakes/2019/07/04/17h33/magnitude6-CA-USA-quake.html) provides the Distance vs 
Intensity graph to check the intensity (mmi) we felt. 

<p align="center">
  <img width="500" height="400" src="/images/dis_inten_3.PNG">
</p>

As per the graph, we felt maximum intensity of **6.8 mmi** (median) at our location which was **25KM** away. So next time, please plan your trip accordingly.

Crazy experience!!!

We had another surprise on **July 5th(2019)** as well! 🙂
