+++
title = "Cleaning Datastream Returns Data in R"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = ""

date = 2019-05-28T12:19:40+05:30
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Is this a featured post? (true/false)
featured = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

Anyone who has used data stream stock prices data is (or should be) aware of the fact that there are many obvious errors in the price data obtained from this source.
A detailed exposition on the types of errors and how to correct for them is available in Ince and Porter (2006) and Schmidt et. al. (). In this post, i consider on error that occurs due to delisting of stocks. Instead of removing the data for a stock, datastream shows the last traded price for that stock and hence gives a long list of zero's at the end of the returns data that need to be removed. 
This rule is explicitly stated by Ince and Porter as : Delete all zero returns (with returns calculated from the total return index) from the end of the sample until the first non-zero return .
I share an R function to 

1.testing 
2.Yes
3.No

[Ince Porter](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=486523)

I : heart : Academic : smile :

$$\left [ – \frac{\hbar^2}{2 m} \frac{\partial^2}{\partial x^2} + V \right ] \Psi = i \hbar \frac{\partial}{\partial t} \Psi$$

| Command           | Description                    |
| ------------------| ------------------------------ |
| `hugo`            | Build your website.            |
| `hugo serve -w`   | View your website.             |



```r
# Code example test


var = sd(c(1,2,8,9,11,2))

```
_testitalic_
In another post, I will share the entire process of collecting accounting and market data (with specific focus on empirical asset pricing studies) from the Thomson Reuters Datastream Database. I will also share some specific Do's and Don'ts that I have learned from some careful trial and error.