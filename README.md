# JC_Mission_To_Mars
Module 10: Web Scraping with HTMLCSS!

# Overview of the analysis:

Robin's web app is showing some cool stuff about Mars facts and data, and she wants to take this to the next level by adding images of the Mars’ hemispheres. To do this, we used BeautifulSoup and Splinter to scrape full-resolution images of Mars’ hemispheres and the titles of those images, stored the scraped data on a Mongo db, used a web app to display the data, and tailored the design of the web app to shuffle these images.

3 parts are accomplished through this analysis:

- D1: Scrape Full-Resolution Mars Hemisphere Images and Titles
- D2: Update the Web App with Mars Hemisphere Images and Titles
- D3: Add Bootstrap Components

# Resources:
 
 **Data source** All data used and queries used in this analysis are available in the [Repo Folder](https://github.com/juanitacosmica/JC_Mission-to-Mars) and all sample images of the results are in the [Resources Folder](https://github.com/juanitacosmica/JC_Mission-to-Mars/Resources) plus we also have the [html] in the [templates folder](https://github.com/juanitacosmica/JC_Mission-to-Mars/templates)

  **Software** Jupyter Notebook, VSCode, MongoDB, Flask, Chrome, HTML, CSS, Bootstrap3, Python, BeautifulSoup, Splinter.


# Results:

The web scraping from active Mars' websites allowed this analysis to retrieve information about Mars facts and data from different articles, see images and their titles, and collect images of the Mars Hemispheres. The data once scrapped, is put together in a web app to show the results.

- D1: Scrape Full-Resolution Mars Hemisphere Images and Titles

From the script called [Mission_to_Mars_Challenge.ipynb](https://github.com/juanitacosmica/JC_Mission-to-Mars) we can appreciate how by using a for loop we were able to scrap and retrieve the image urls and titles for each hemisphere and print the list from the dictionary of them.

![Script](/Resources/D1_img1.png)

![Results](/Resources/D1_img2.png)

- D2: Update the Web App with Mars Hemisphere Images and Titles

![Function defined for Hemispheres (x4)](/Resources/D2_img1.png)

![Img and Titles Results Hemispheres (x4)](/Resources/D2_img2.png)

- D3: Add Bootstrap Components

![How it looks in the web app](/Resources/D3_img1.png)

![This is the code so we can keep scrapping data in the web app](/Resources/D3_img2.png)

All script screenshots results are avaialble for viewing on the [Resources Folder](https://github.com/juanitacosmica/JC_Mission-to-Mars/Resources).

# Summary:

Imagine how useful this can be, for you instead of going and gather data manually from different websites, this type of script and tools (as shown from D1 to D3) will allow to scrap from data, text to images from different websites! Plus being able to utilize unstructured data types as well, and getting all the results put together in a tailored webapp for the clients to see. A handy method for all time saving fellas.

People call me JC, the short for [Juanita C. Nunez](https://www.linkedin.com/in/juanitacamargonunez/). Contact me for any questions! I love networking, so here you go my [LinkedIn] (https://www.linkedin.com/in/juanitacamargonunez/) :)