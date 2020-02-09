# IBM Data Science - Capstone Project: Week 1.

---

## Background

- As of July 2019, in South Korea, there were 71,000 Coffee shops. And the number of Coffee shops are increasing even now. However, many of them were closed before 3 years. 
- ![](https://file2.nocutnews.co.kr/newsroom/image/2019/11/06/20191106105353856742_0_710_555.jpg)
  - [https://www.nocutnews.co.kr/news/5238987]
  - (Yellow bar means number of start-up coffee shops, and black bar means number of shut-down coffee shops)
- So, if you want to start coffee shop in South Korea, it is very important to find appropriate place.

## Problem

- In Seoul, South Korea, where is the best place for starting a new coffee shop?
- Seoul has 25 Districts/Counties("Gu", in korean) and Districts are separated to several Cities/Towns("Dong", in korean).
- ![image-20200209170433315](https://upload.wikimedia.org/wikipedia/commons/a/a2/Map_Seoul_districts_de.png)
  - [https://en.wikipedia.org/wiki/File:Map_Seoul_districts_de.png]
- So, our goal is found best "Dong" for starting a new coffee shop using Foursquare location data. We may use location data for Seoul additionally.

## Dataset

1. Foursquare location data, espetially venue dataset
2. Location data of Seoul("Gu" and "Dong"), it contains latitude, longitude, border line. 