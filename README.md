### Mission to Mars

## Background:

Building a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page. 

## Objectives:

Apply scrape to sraping information from some websites.

Use MongoDB and Flask to create a new HTML page.

## Methods for Analysis:

Libraries utilized: Flask, MongoDB, bs4, splinter, pandas, time, sre_constants, requests, pandas, ChromeDriverManager

Initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

Scrape the NASA Mars News Site and collect the latest News Title and Paragraph Text. 

Visit the url for Featured Space Image.

Use splinter to navigate the site and find the image url for the current Featured Mars Image and assign the url string to a variable.

Visit the Mars Facts webpage and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc. Use Pandas to convert the data to a HTML table string.

Visit website to obtain high resolution images for each of Mar's hemispheres.Save the images url string for the full resolution hemisphere image, and the Hemisphere title containing the hemisphere names.

Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.

Use Bootstrap to structure the HTML template.


![Screenshot (111)](https://user-images.githubusercontent.com/100891182/182627509-506e145e-f887-41ea-82a5-7cc5c482ee1d.png)


![Screenshot (110)](https://user-images.githubusercontent.com/100891182/182627479-35a5317e-b895-4746-a580-14b6b40f5256.png)


![Screenshot (113)](https://user-images.githubusercontent.com/100891182/182627424-8d532609-b9f6-42ae-b8ee-f31a0bcec233.png)




## Findings:

The updated news from the website.

The new HTML from scraped information.

## References:

https://www.redplanetscience.com

https://spaceimages-mars.com

https://galaxyfacts-mars.com

https://marshemispheres.com



