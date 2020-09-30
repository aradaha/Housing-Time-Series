# Module 4 Final Project


## Introduction

![alt text](https://c1.staticflickr.com/5/4094/4904766787_51e252cda7_z.jpg)

In this project I worked with a time series in order to predict which zip codes would be the best to invest in. I chose the northwest, because I needed to cut the data down somehow, and I am interested in the northwest in general.

First, I tried to plot manhattan zip codes, but they didn't exist, that's too bad.

Then, I plotted the prices for Reno. A little bit surprising, because the prices haven't gotten back up to where they were 15 years ago, at least they hadn't two years ago.

I also plotted several zip codes in Denver, to get a good look at the housing crisis. I felt I should avoid it, so I picked a spot where most places were in recovery from it, early 2012.

I then melted the data, and observed that a few zip codes didn't have complete data. I figured this was because they recently came into existence. There were a couple of those on the Denver graph as well. Since there were only 6, out of over 500, it seemed reasonable to just drop them. Anyway, there may not be enough data to work with when predicting.

I then used a seasonal model to plot one zipcode and seperate the factors to confirm that there was a seasonal component, so I was right to use SARIMAX rather than ignoring the seasonal data.


![alt text](https://i.postimg.cc/2ysCnjBy/Bellvue.gif)