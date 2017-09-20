---
layout: post
title: Afghan Income Deciles Over Time
---


Recently, I was reading through the new econ book, [The Economy](http://www.core-econ.org/the-economy/book/text/0-3-contents.html), by the Core project.
They provide a CSV of most countries income per capita by decile over time. I was curious if the U.S. lead invasion of Afghanistan had an effect on incomes, and even more so if that effect was evenly distributed.

I plotted the Afghan data in CSV using Python and was surprised by the result.

![Afghanistan]({{ site.baseurl }}/images/20180920Afghanistan.png)

I expected to see an impact after 2001, but incomes rose since the late 90s and the U.S. invasion appeared to have no effect. The growth in incomes was relatively equal as well. Inequality rose slower than in neighboring countries.


Noticeably, incomes, especially among the riches, crashed around the time of the Soviet invasion and Afghan civil war. I wonder if enough capital was destroyed during that time, that the subsequent invasion by the US didn't have much of an impact.


## Other Countries
To make sure this was truly an outlier, I also plotted neighboring countries who were included in the data set.

![Pakistan]({{ site.baseurl }}/images/20180920Pakistan.png)
![Turkmenistan]({{ site.baseurl }}/images/20180920Turkmenistan.png)
![Uzbekistan]({{ site.baseurl }}/images/20180920Uzbekistan.png)

## Do it yourself
The code and CSV are found [here](https://github.com/samuelfelt/Global-Incomes-Plot). You'll need pandas and Bokeh in order for the Python code to work.
