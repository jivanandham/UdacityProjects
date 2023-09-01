# Investigating-dataset
Udacity Data Analyst Nano Degree Project @

Project: Investigate a Dataset (European Soccer Database)
By Jeeva K
Table of Contents
Introduction
Data Wrangling
Exploratory Data Analysis
Conclusions

Introduction
European Soccer Dataset is analyzed and presented with the question. This dataset consists of the various tables with player, player_attributes, country, team , team attributes, and leagues in SQL. The SQL data is converted into dataframe for ease use of the data. The columns are dropped and renamed according to the need for data analysis and visualization.

The Questions decided on datasets are:

"Which foot is most preferred by player durning defense and attact?"

"Correlation between Overall rating of player, Free Kick Accuracy and Penalties"

"What is the effect of BMI Index on overall rating of the players."





Conclusions
It was very good working on this project. The analysis of dataset with respect to player_attributes of the preferred foot, BMI Index, Free Kick Accuracy and penalties with the overall rating of the player was done.

Limitations (1) Missing data

During data wrangling some data was missing in the table. The columns needed for my questions are all clean. The columns were very helpful in answering other interesting questions such as betting odds. In the team_attributes data, more than 80% of data in the column 'buildUpPlayDribbling' is missing, therefore analysis on this column will be less reliable .

(2) Insufficient amount of data

Team_attributes when analyzing column 'buildUpPlayPositioningClass' the most of the data in this column is insufficient and the column is dropped, So that the result will be more reliable.

Player_Info Analysis
Question 1
"Which foot is most preferred by player durning defense and attact?"

The pie chart shows 71% of player prefer right leg during attack and 77% during defense. The preference of right leg durning defense is more when compare to attack during the game.

Question 2
"Correlation between Overall rating of player and Free Kick Accuracy, Penalties"

The correlation between Overall rating and Free Kick Accuracy is .35. It shows the moderate significance between the two variables.

The correlation of overall rating and penalties is .392 which also shows moderate significance between the two variables

Question 3
"What is the effect of BMI Index on overall rating of the players."

The Effect of BMI Index with Overall rating shows that the most of the player are Healthy, and the BMI index doesn't plays any important role in the overall rating of the players.
