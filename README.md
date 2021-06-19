# PS4 Games Sales Analysis 
        
         
## Directory 
[💪Motivation](#project-motivation)

[💾Library](#library-and-installation)

[📂Files & Description](#files-and-description)

[📚Data Preparation](#data-preparation)

[📊Summary](#summary)

[🎈Acknowledgment](#acknowledgement)

## Project Motivation ##

The motivation to complete this project is to provide answer based on data to these questions : 
- [ ] Publisher
  > Question 1 : Which publisher have publish most games for PS4 ?
  > 
  > Question 2 : What is the top 5 of high earn publisher ?
- [ ] Sales
  > Question 1 : What is the average sales of top 10 selling games per year ?
  >
  > Question 2 : Which PS4 game's genre score the highest sales ? And which country buy most of it ?
- [ ] Games
  > Question 1 : What are top 5 popular PS4 games published by Ubisoft ?


## Library and Installation ##

I used python 3 to complete this project. The library and installation command used in this project are listed as below: 

Library           | Command Installation             | Description
-------------     | -------------                    | -------------
Numpy             | `pip3 install numpy`             | Python library used for working with arrays
Pandas            | `pip3 install pandas`            | Open source Python package that is most widely used for data science/data analysis and machine learning tasks
Matplotlib        | `pip3 install matplotlib`        | Matplotlib is a cross-platform, data visualization and graphical plotting library for Python 
Sklearn           | `pip3 install sklearn`           | Sklearn library contains a lot of efficient tools for machine learning and statistical modeling 
Seaborn           | `pip3 install seaborn`           | Open-source Python library built on top of matplotlib. It is used for data visualization and exploratory data analysis.
Matplotlib-inline | `pip3 install matplotlib-inline` | %matplotlib inline is a magic command for IPython that allows you to add plots to the browser interface

## Files and Description ##

<details>
           <summary>PS4_GamesSales.csv</summary>
           <p>This is dataset used to gather information in order to seek answers for questions asked in project motivation. This dataset is downloaded from <a href="https://www.kaggle.com/sidtwr/videogames-sales-dataset">here</a>.</p>
         </details>
         
<details>
           <summary>PS4 Games Analysis.ipynb</summary>
           <p>This is jupyter notebook that consists all of the working code.</p>
         </details>
         
 <details>
           <summary>README.MD</summary>
           <p>This is a readme file that is used to represent this project.</p>
         </details>

## Data Preparation ##

1. Data Understanding

   The project begun by trying to understand the data set and gain much knowledge about data, the curiosity the data will satisfy, its content and its type.
   Exploration of the dataset is done when different queries are formed, to find the relationship between each column, and gain further insight regardings questions asked above.
   
2. Data Preparation

   During data preparation, we eliminate all row with null value for Publisher column since the row will become useless once the Publisher column is null. This process is also      known as data cleaning.
   
3. Deployment
   
   All deployment and working codes is nicely prepared in jupyter notebook. We also use jupyter notebook to output chart and graph for better visualization. 


## Summary ##
All the questions asked already answered after using data analysis method to further process the data. Please find answers as below: 
- [X] Publisher
- Question 1 : Which publisher have publish most games for PS4 ?   
  - Answer : Most of PS4 games was published by Namco Bandai Games with count of 56 games.


- Question 2 : What is the top 5 of high earn publisher ?
  - Answer : Top 5 high earn publishers are Activision, Ubisoft, Electronic Arts, Sony Interactive Entertainment and EA Sports with minimum earnings of 47.55 millions.
  
- [X] Sales
- Question 1 : What is the average sales of top 10 selling games per year ?
  - Answer : Average sales of top 10 selling games per year range between 1.41 millions to 2.77 millions.


- Question 2 : Which PS4 game's genre score the highest sales ? And which country buy most of it ?
  - Answer : Genre Action score the highest sales for PS4 games. The highest sales of this genre was contributed during Europe Sales.
   
- [X] Games
- Question 1 : What are top 5 popular PS4 games published by Ubisoft ?
  - Answer : The top 5 popular games published by Ubisoft are :
    - *Tom Clancy's The Division*
    - *Tom Clancy's Rainbow Six: Siege*
    - *Watch Dogs*
    - *Assassin's Creed: Unity*
    - *Assassin's Creed Origins*


## Acknowledgement ##
Special thanks to this website for their existence, really help me to conduct data analysis for this project with providing lesson, dataset and example :  

✅ [Udacity](https://www.udacity.com/ "Udacity")

✅ [Kaggle](https://www.kaggle.com/ "Kaggle")

✅ [StackOverflow](https://www.stackoverflow.com/ "StackOverflow")

✅ [GeeksforGeeks](https://www.geeksforgeeks.org// "GeeksforGeeks")
