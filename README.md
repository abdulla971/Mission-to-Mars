# Mission-To-Mars-Web-Scraping-App
Various websites are scraped for data relevant to the Mission to Mars using a web application and the data is shown in a single HTML web page.

## Files:
- mission_to_mars.ipynb: a Jupyter Notebook that contains the original scrape code for the whole project.

- scrape_mars.py: Python File that contains two functions which are the init_browser() that is used to initiate browser via chromedriver and the scrape() function that is used perform scrape of all pages taken from original Jupyter Notebook.
- mars_app.py: Flask App that uses the scrape() function from scrape_mars.py to update mars_app database collection in the MongoDB and load as webpage from index.html.
- templates folder: HTML webpage used for Mission to Mars that displays the information from our web application scrape.
- images folder: Seven total .jpg images of the Mission to Mars web HTML web page app.
