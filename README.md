# Scraping "Today's Deal" in Amazon using Selenium Webdriver

This is a Selenium Web Scraping project for extracting the best daily deals in Amazon site along with the deal offers and the image urls.

## Introduction
---------------------------------------------------------
For regular customers at Amazon, it is imperative to keep track of a myriad of items such as electronic devices, household tools, and 
so forth. The incentive of this project is to scrape the "Today's deal" section of Amazon to automate a bot for scraping valuable 
information a customer might be interested in purchasing or might purchase later once a better deal was announced. This way, a customer 
can plan ahead of time and make a decision as soon as a better deal offer is announced, which in most cases is a limited type of offer.

![alt text](https://github.com/shahriar-rahman/Amazon-Today-Using-Selenium/blob/main/img/amazon_deals.PNG)

## Project Organization
---------------------------------------------------------

    ├── LICENSE
    ├── Makefile           <- Makefile with various commands
    ├── README.md          <- The top-level README for developers using this project.
    ├── scraping_data
    │   ├── csv            <- Data in csv format compatible with pandas dataframe.
    │   ├── excel          <- Data in xlsx format for better data analysis.
    │   ├── xml            <- Data in xml format.
    │   └── json           <- Data in Json format for better utilization.
    │
    │
    │
    ├── img                <- Contains project image files.
    │   
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         			generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── main           <- Contains scripts to automate web scraping using Selenium
    │   │   └── amazon_todays_deal.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

