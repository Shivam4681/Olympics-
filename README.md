<h1 align="center">Olympics Data Analysis with SQL</h1>
<p align="center">
<img src="images/pngtree-olympic-day-games-background-picture-image_996806.jpg" width="700" height="300">
</p>

## Description
The goal of this project is to become acquainted with SQL concepts by solving real-world data questions; it will be accomplished by downloading 120 years of Summer and Winter Olympics History till 2016 dataset from Kaggle and answering each question provided by techTFQ accordingly.

## The Tables used in this project are:

olympics_history: it contains all players that have participated in the Olympics till 2016 including their age, sex, national Olympic committee (noc), Olympic game, sport, event and medal type if they won.<br>
olympics_history_noc_regions: it contains all national olympic committees that represent countries with their old and new names from 1896 to 2016
The Goal of the project is to answer 14 questions related to the Olympics by making SQL query for each one of them and the Questions are:


## Questions
1. Show how many medal counts present for entire data.
2. Show count of unique sports present in Olympics. 
3. Show how many different medals won by team India.
4. Show event wise medals won by India show from highest to lowest medals won in order.
5. Show event wise medals won by India in order of year.
6. show country who won maximum medals.
7. show top 10 countries who won gold.
8. show in which year did United states won most gold medal.
9. In which sports United States has most medals.
10. Find top three players who won most medals along with their sports and country.
11. Find player with most gold medals in cycling along with his country.
12. Find player with most medals (Gold+Silver+Bronze) in Basketball also show his country.
13. Find out the count of different medals of the top basketball player Teresa Edwards.
14. Find out medals won by male,female each year , Export this data and plot graph in excel.


## Setup

1. Create a MySQL database named `project_1`.
<p>
<img src="images/create.png" width="180" height="130">
</p>


2. Create a table named `Olympics` to store the dataset.
   
<p>
<img src="images/Table.png" width="200" height="300">
</p>


3. Load Data from CSV file

<p>
<img src="images/File.png" width="650" height="300">
</p>
<br>
<br>

## Queries and Analysis

1. **Show how many medal counts present for entire data.**

   ![Image](images/q1.png)
   
   Result⬇️

   <img src="images/q1 output.png">

2. **Show count of unique sports present in Olympics.**

   ![Image](images/q2.png)
   
   Result⬇️

   <img src="images/q2 output.png">
   
3. **Show how many different medals won by team India.**

   ![Image](images/q3.png)
   
   Result⬇️

   <img src="images/q3 output.png">

4.**Show event wise medals won by India show from highest to lowest medals won in order.**

   ![Image](images/q4.png)
   
   Result⬇️

   <img src="images/q4 output.png">

5.**Show event wise medals won by India in order of year**
 
   ![Image](images/q5.png)
   
   Result⬇️

   <img src="images/q5 output.png">
   
6.**Show country who won maximum medals.**
 
   ![Image](images/q6.png)
    
   Result⬇️

   <img src="images/q6 output.png">

7.**show top 10 countries who won gold**

   ![Image](images/q7.png)
   
   Result⬇️

   <img src="images/q7 output.png">

8.**show in which year did United states won most gold medal**

   ![Image](images/q8.png)
   
   Result⬇️

   <img src="images/q8 output.png">

9.**In Witch sports United States has most medals.**

   ![Image](images/q9.png)
   
   Result⬇️

   <img src="images/q9 output.png">

10.**Find top three players who won most medals along with their sports and country**

   ![Image](images/q10.png)
   
   Result⬇️

   <img src="images/q10 output.png">

11.**Find player with most gold medals in cycling along with his country.**

   ![Image](images/q11.png)
   
   Result⬇️

   <img src="images/q11 output.png">

12.**Find player with most medals (Gold+Silver+Bronze) in Basketball also show his country**

   ![Image](images/q12.png)
   
   Result⬇️

   <img src="images/q12 output.png">

13.**Find out the count of different medals of the top basketball player Teresa Edwards**

   ![Image](images/q13.png)
   
   Result⬇️

   <img src="images/q13 output.png">

14.**Find out medals won by male, female each year  , Export this data and plot graph in excel.**

   ![Image](images/q14.png)
   
   Result⬇️

   <img src="images/q14 output.png">

   <img src="images/Male.png">

## Insights Summary

- **Medal Distribution:** The dataset contains information on medals awarded in various Olympic events, indicating the overall competitiveness and achievement levels across different sports and countries.
- **Sport Diversity:** With a count of unique sports present in the dataset, it's evident that the Olympics encompass a wide range of sporting disciplines, showcasing the diversity and inclusivity of the event.
- **India's Performance:** Team India has participated in Olympic events and achieved success, as shown by the medals won. The breakdown of medals by event and year provides insights into India's strengths and areas of success in Olympic competition.
- **Global Performance:** The analysis of medal counts by country highlights the competitive landscape of the Olympics, showcasing countries with significant success in terms of medal acquisition.
- **Gold Medal Dominance:** The identification of countries with the most gold medals emphasizes the importance and prestige associated with winning gold in Olympic competition.
- **United States' Dominance:** The queries focusing on the United States reveal the country's remarkable success in the Olympics, both in terms of overall medal counts and gold medal achievements across different sports and years.
- **Top Performers:** Highlighting top-performing athletes and their achievements provides insights into individual excellence and contributions to their respective countries' success in the Olympics.
- **Gender Disparity:** The analysis of medals won by gender each year sheds light on gender-based trends and disparities in Olympic participation and success, offering insights into the representation and performance of male and female athletes over time.

