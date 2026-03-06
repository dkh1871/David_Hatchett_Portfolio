# Video Game Completion and Speed Run Times

## Description  
The primary purpose of this project was to practice various data wrangling techniques across different sources and to produce a coherent final output. The code in this report will ingest and process data from a flat file, scrape data from a website, and finalize data from a REST API. The code in the repo provides a fundamental understanding of ETL, Data cleaning, and Python skills.

The project is broken up into four steps. One step for each data source, and a final dataset that combines the data and performs some basic analytics on the combined datasets. Each processing step will inject the dataset and save it to an SQLite database created to store and eventually merge the data.  

## Data   

### [Flat File: Video Game Playtimes (Kaggle)]( https://www.kaggle.com/datasets/baraazaid/how-long-to-beat-video-games)  
The dataset contains a list of video games that contains how long they usually take to beat.  This data is taken from pools and contains categories like 100% (do everything), Main Story (Bare minimum), and overall stats like average, minimum, and max playtimes. This data was sourced from [howlongtobeat](https://howlongtobeat.com/).  

Data was loaded to Kaggle by user: [Baraa Zaid](https://www.kaggle.com/baraazaid).  

### [Web Scraping: Games Done Quick Tracker](https://tracker.gamesdonequick.com/tracker/)  
This site is run by the charity group Games Done Quick, which holds several yearly events focused on speed running and raising money for charity. I chose to use the data from the runs portion of the site.

### [API: SpeedRuns.com API](https://github.com/speedruncomorg/api/tree/master/version1)
SpeedRuns.com is a popular site for tracking and sharing speed runs. They kindly provide an API that can be used to gather data and submit data. We will pull the top speed runs for games from this site.  
