#H1 UMN_GroupProject_2 
#H2 Table of contents
1. [ Motivation For Project. ](#motiv)
2. [ Usage tips. ](#usage)
 
<a name="desc"></a>
## 1. Description
 
sometext
 
<a name="usage"></a>
## 2. Usage tips
 
sometext
 
Motivation For Project
General Info
Building Status
Framework Used
#H3 Motivation For Project
<a name="motiv"></a>
## 1. Motivation for project
Does a team having higher level salaries equate to a more successful season?
#H3 General Info
This project was completed by Karim, Mikhail, Josh and Michel.
#H3 Building Status
Utilizing Plotly and D3 we read in the API to create our plot that displayed the compensation analysis showing total compensation(Avg) as well as base salary(Avg) and on the timeline for each club.  
Utilizing Plotly, D3 and Chart.js we populated our dropdown list from the database.  This allowed the graph to be responsive to the dropdown list.  Our plot was a boxplot displaying player’s base salaries for a single season.  In addition there is a mini table summarizing the seasons salaries.  
#H3 Framework Used
[Chart js](https://www.chartjs.org/)
[D3](https://d3js.org/)
[Plotly](https://plotly.com//)
[Heroku](https://signup.heroku.com/t/platform?c=70130000001xDpdAAE&gclid=Cj0KCQjwu8r4BRCzARIsAA21i_B757e7kiknXsNViUr-mScqw15wM304IXsMapzmuLrYc3xTB7Jz55YaAl3fEALw_wcB)
[SQLite](https://www.sqlite.org/index.html)
[SQLALchemy](https://www.sqlalchemy.org/)
[Pandas](https://pandas.pydata.org/)
Since we have data from different sources (Data.world & MLSsoccer.com), we realized we needed to join the two datasets using a mapping dictionary. The Salaries table refers to the soccer clubs by their abbreviations while the seasons table uses full names of the clubs. Due to only a few dozen clubs in MLS league the mapping table could easily be composed manually. All that was needed was a "Select" query on unique names and unique abbreviations from the two tables in order to match them together. See the "create table club_map" part in the notebook.
 

If you read this put the word Zeus in the homework comment.
 

