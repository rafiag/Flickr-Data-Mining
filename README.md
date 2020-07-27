# Flickr-Data-Mining

In this project I try to use geotagged photo from Flickr to understand the characteristics of foreign tourist visiting Bali, Indonesia. This repository consisted of three Python notebook:
1. FlickrCrawler: this notebook is used to collect data using th API provided by Flickr. For more information you can check the [documentation](https://www.flickr.com/services/api/).
1. Clustering: cluster the data based on their latitude and longitude either using OPTICS or DBSCAN algorithm and visualize the result.
1. Markov_Chain_Modelling: build markov chain model to see how tourist likes to move from one cluster to another.

Here are a couple of visualization result I did for this project:
![Clustering visualization](https://raw.githubusercontent.com/rafiag/Flickr-Data-Mining/master/Image/DBSCAN%20(0.4%2C%201800).png)
![Markov chain visualization](https://raw.githubusercontent.com/rafiag/Flickr-Data-Mining/master/Image/Markov%20Chain.png)
