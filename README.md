# Capstone Project
![](images/TheGreatAmericanSongbook_Pack1.jpg) ![](images/Walt-Disney-logo.png)

[Songbook Photo Source](https://www.demonmusicgroup.co.uk/catalogue/releases/the-great-american-songbook/) 
<br>[Disney Logo Source](https://1000logos.net/walt-disney-logo/)
## Problem Statement

Over the last hundred years popular music has changed dramatically. From the instruments used to the chord progressions that give the foundation of a song. This project is to discover how differently musical lyrics have changed over time. During the 20's, 30's, and 40's many musicians all performed the popular songs of the day that came from musicals. Today these great songs are known as 'The Great American Songbook.' I am interested to find out what makes these lyrics characteristically different to the music in Walt Disney films. I will use classification models to predict which category the lyrics are from and use precision and recall as success metrics. 

## Quick Summary
Looking through this notebook you can see all the information you need to find on how I scraped to gather the lyrics using requests and BeautifulSoup. Then did some cleaning of the data again using BeautifulSoup and some Python functions. After the data was cleaned I then did some analysis on that data. Then I finally put the lyrics through some models to see if it could predict between the two sources content. The words were run through a CountVectorizer and a TFIDFVectorizer to see if one performed better over the other. Some of the models used were a Logistic Regression, Random Trees Classifier, and Support Vector Classifier.

## Software Requirements/Libraries
- Python
- Pandas
- Numpy
- Time
- Requests
- Beautiful Soup
- Regex
- NLTK Stopwords
- Matplotlib
- Seaborn
- Scikit-Learn 
  - CountVectorizer
  - TfidfVectorizer
  - Logistic Regression
  - train_test_split
  - GridSearchCV
  - Pipeline
  - GaussianNB
  - TransformerMixin
  - RandomForestClassifier
  - ExtraTreesClassifier
  - GradientBoostingClassifier
  - AdaBoostClassifier
  - SVC
  - Confusion Matrix
  - ROC AUC Score

#### Below you can see links to the jupyter notebooks, data, and references:

## Jupyter Notebooks:

1. [Gathering American Songbook Lyrics](00_Gathering_Lyrics.ipynb)
2. [Gathering Disney Lyrics](01_Gathering_Disney_Lyrics.ipynb)
3. [Combining Data](02_Combining_Songs.ipynb)
4. [EDA](03_EDA.ipynb)
5. [Modeling](04_Modeling.ipynb)
6. [Confusion Matrix](05_Confusion_Matrix.ipynb)
7. [Predictions Data](06_Predictions_Data.ipynb)

##  References

##### Lyrics:
- [The Great American Songbook](https://www.lyricsfreak.com/) - Source for "The Great American Songbook Lyrics"
- [Disney Lyrics](http://www.disneyclips.com/lyrics/) - Source for all the Disney Lyrics

##### “The Great American Songbook”:

- [Great American Songbook Society](https://thesongbook.org/)
- [List of The Great American Songbook Songwriters](https://en.wikipedia.org/wiki/Great_American_Songbook#Songwriters_and_songs) - Source I used to pick songwriters 
- [Americna Popular Composers](https://archive.org/details/americanpopulars00alec/page/23) - Another source used to discover songwriters
- [History of The Great American Songbook](https://www.udiscovermusic.com/in-depth-features/cover-to-cover-the-story-of-the-great-american-songbook/) - Article on more information about "The Great American Songbook"

##### Disney and the Disney Renaissance:
- [Disney Renaissance](https://en.wikipedia.org/wiki/Disney_Renaissance) - Disney Movies that were apart of the Disney Renaissance
- [Disney Renaissance Video Breakdown](https://www.youtube.com/watch?v=JX0gZY9VKlM) - A video breakdown on why Disney music has such a nostalgic sound.

