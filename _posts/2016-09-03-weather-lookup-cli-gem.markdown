---
layout: post
title:  "weather-lookup-cli-gem"
date:   2016-09-03 20:57:12 +0000
---


Creating this cli gem was both fun and frustrating. So initially, I wanted to scrap data from "weather.com". HOWEVER, this proved to be too difficult because their naming convention was really werid. I spent hours trying to get data from the site without any luck. It's like they purposely made it difficult to scrap data from their site. After awhile, I decided to give up on "weather.com" and instead use another site called "wunderground.com".

With "wunderground.com" and Nokogiri, I was able to quickly scrap all the data I needed to create my weather-lookup-cli-gem. When the user enters a zip in the cli, Nokogiri goes into "wunderground.com" and searches the weather with the zip. There, it scaps the time/location/weather/temp and returns it to the user.
