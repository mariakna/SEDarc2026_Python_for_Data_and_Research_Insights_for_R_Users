# Python for Data and Research: Insights for R Users

This repository contains all materials used for the "Python for Data and Research: Insights for R Users" class for the SEDarc DTP (https://www.sedarc.ac.uk/).

Many scientists do not have formal training in computer science and often learn programming through trial and error, most commonly using R, a language well-suited for statistical analysis. However, data science and data analysis more broadly often require other programming languages, most notably Python. Because Python differs from R in important ways, it can be difficult to learn without a solid grasp of computing basics. This short session will introduce Python with a focus on how it differs from R, both in how it works and what it can do. We will cover core topics such as object-oriented programming, data types, control structures, regular expressions, and visualisation. The course will feature live demonstrations, and you will have the opportunity to ask questions in a dedicated Q&A session. By the end of the session, you will have a clear understanding of how Python differs from R, when Python might be the better choice, how to perform some basic tasks, and where to look for further learning resources.

Most of the class content is based on the slide deck (Python_intro_slides) and the Jupyter Notebook (Python_demo.ipynb and Python_demo.html).

Following questions raised during the live session, here are some recommendations and resources:

## Collecting social media data in an ethical way

The most ethical approach is probably to use official APIs, as these are designed for data access within each platform's terms of service; examples include:

- [Twitter API](https://twitterapi.io/)
- [Graph API](https://developers.facebook.com/docs/graph-api/) for Facebook and Instagram
- [YouTube Data API](https://developers.google.com/youtube/v3)
- [Reddit API](https://www.reddit.com/dev/api/)

Python libraries designed to work with these APIs are:

- [Tweepy](https://www.tweepy.org/) for Twitter API
- [Facebook SDK](https://facebook-sdk.readthedocs.io/en/latest/) for Facebook
- [Pystagram](https://pypi.org/project/pystagram/) for Instagram
- [PRAW](https://praw.readthedocs.io/en/stable/) for Reddit API

You may also find [this collection of resources](https://study.sagepub.com/brooker/student-resources/directory-of-python-libraries/working-with-social-media-platforms) helpful. If a platform does not provide a dedicated API, I'd recommend [Scrapy](https://www.scrapy.org/) and [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/#:~:text=Beautiful%20Soup%20is%20a%20Python,hours%20or%20days%20of%20work.), but you'll need to be careful to make sure you comply with the platform's terms of service!

## Working with GIS in Python and R

For those interested in geographic information systems (GIS), here are some useful tools:

- Python: [GeoPandas](https://geopandas.org/en/stable/), [Fiona](https://fiona.readthedocs.io/en/stable/), [Cartopy](https://cartopy.readthedocs.io/stable/). Courses that look interesting: [Udemy](https://www.udemy.com/course/pyspatial/), [Coursera](https://www.coursera.org/learn/packt-python-geospatial-development-essentials)

- R: [sf](https://r-spatial.github.io/sf/); [terra](https://rspatial.github.io/terra/); [tmap](https://r-tmap.github.io/tmap/); [leaflet](https://rstudio.github.io/leaflet/). You might also find [this book](https://www.paulamoraga.com/book-spatial/index.html) useful. Online courses on this are available on DataCamp (see [here](https://www.datacamp.com/courses/visualizing-geospatial-data-in-r) for example).
