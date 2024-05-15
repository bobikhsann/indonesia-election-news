# Project Title

Indonesian election tren and labeling 


## Project Overview
In this project, we will look at trends and labeling of election news in Indonesia in one of the online news outlets, namely detik.com. First, we scraped the detik.com web from 1 September 2022 - 30 January 2024 with the keywords election and presidential candidate. Once the dataset is ready, continue with data processing to get insight from the dataset.

In this project, you will gain an understanding of:

 - What is web scraping and why should you do it.
 - See election trends and labeling based on one of the news websites
 
## Prerequisites

1. [Jupyterlab](https://jupyter.org/install)
    
2. pandas
    * Run `pip install pandas`
3. BeautfulSoup
    * Run `pip install beautifulsoup4`
4. Wordcloud 
    * Run `pip install wordcloud`
    
## Code

You can find the code for this project [here](https://github.com/bobikhsann/indonesia-election-news).

File overview:

* `Scraping web.ipynb` - a jupyter notebook where script for web scraping
* `main program.ipynb` - script to process the scraped dataset
* `stop_words_idn.txt` - text that is used to remove words that are not needed later

## Usage
* Run `Scraping web.ipynb` to get a dataset from detik.com with the file politik.xlsx.
* Run `main program.ipynb` upload dataset politik.xlsx.
    * create data filter, Separate year, month, date and time data to make grouping easier.
    * CALCULATE NEWS TRENDS FOR PRESIDENTIAL CAPRES, Calculate the number of news headlines about the Presidential Election each month and display them in graphical form.
        * The graph is in the form of a bar chart
        * The graph is in the form of a line chart
        * Graphics combining bar charts and line charts.
    * DATA CLEANSING & MERGE, 
      Next, do preprocessing / data cleansing
        * Create a preprocess_text function to perform cleansing
        * Combine the title and body of the news
        * Perform preprocessing by calling functions.
    * labelling, data tokensizing, stopwords and wordclouds.to gain insight from the dataset


