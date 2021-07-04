# UFOs
![Site_Overview](https://user-images.githubusercontent.com/82347825/124340938-e5a79d80-db86-11eb-992d-c8c90a6ec41b.png)

## Overview
The purpose of this project was to build a dynamic and interactive website showcasing data on UFO sightings. By using Javascript, HTML and CSS we were able to construct a filterable dataset for users to examine and make conclusions of their own on whether they believe UFOs are out there.

## Results
The average user should find the website relatively easy to us since, based on the user's input, each of the 'Filter Search' fields on the left side of the page will narrow the data in the respective column on the right side of the page. For example, entering "ca" into the 'State' field will show us all results for the state of California:

![CA_search](https://user-images.githubusercontent.com/82347825/124396457-ab99e100-dcd7-11eb-83c8-0a760ba3719f.png)


Once filtered to show UFO sightings in California, one can then choose to narrow it down further by entering another field, such as city, date, or shape. In this example, we chose to look at all "light" shaped UFOs: 

![CA_Light_search](https://user-images.githubusercontent.com/82347825/124396459-b18fc200-dcd7-11eb-8c46-f2e1c6b3a7e3.png)

Entering one last filter of 'el cajon' for the "City" field shows us the two instances where a light shaped UFO appeared in El Cajon, California (per our 3 search filters):

![CA_Light_El Cajon_search](https://user-images.githubusercontent.com/82347825/124396463-b5bbdf80-dcd7-11eb-91c3-f1137b4aac5f.png)


## Summary
One drawback of our website is that our filter search only allows for exact matches. For example, entering "*frenso*" instead of "*fresno*" will not return a result. Similarly, using capital letters "*Fresno*" instead of "*fresno*" will also result not yield results. I would suggest including some sort of fuzzy match in our filter script so that typos and punctuation might still return results for our users.

Another drawback of our website is that our data set is limited to the events & sightings that were loaded at the moment of the site's creation. I would recommend integrating web scraping functionality so that any time we use it we can be sure that we are seeing all of the latest data that has been made available.
