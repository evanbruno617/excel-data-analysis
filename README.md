# Excel-Campaigns-Analysis

## Purpose

  The purpose of this project is to analyze data comparing theater campaign outcomes based on goals and launch dates. Louise's play, Fever, came close to it's goal in a short amount of time and we want to be able to have our future productions be just as successful. By looking at how successful these previous campaigns were based on how big their goals were and the date it was launched, can aid us to better plan future theatre events. We will use all the information collected on these campaigns to analyze these trends. [Campaign Information](https://github.com/evanbruno617/kickstarter-excel-data/blob/main/Kickstarter_Challenge_Data.xlsx)

--- 

## Analysis

  To begin my analysis I needed to filter out my Category and Subcategory to display the parent category and subcategory into seperate columns in order to seperately analyze them. 
  
### Theater Outcomes Based on Launch Date

  I first analyzed the outcomes of theatres by the date they were launched. I used years as my filters as well as parent category to only select the theatre campaigns to be showed in my data. We wanted to know how each campaigned fared with their launch date so I made rows of each month and columns of outcomes to see how many successful, failed, and cancelled outcomes there were in each given month. I created a chart based on this information with the months on the x-axis and  quantity of outcomes on the y-axis depicting seperate lines of successful, failed, and cancelled outcomes. ![Theater Outcomes Based on Launch Date](https://raw.githubusercontent.com/evanbruno617/kickstarter-excel-data/main/Resources/Theater_Outcomes_vs_Launch.png)
  
### Outcomes Based On Goals

  Next I analyzed the outcomes of plays in theatres based on their goals. I started by making a column for goals with a row starting at less than 1000 and then by intervals of 5000 until 50000. I then counted the number of successful plays in each interval by using a COUNTIF statement. I continued this proccess with failed and cancelled plays as well. I then calculated total projects of each row by adding up all of the outcomes. I then found the percentage of successful, failed, and cancelled outcomes for each row. From this data I created a line chart depicting the percent of successful, failed, and cancelled outcomes per goal interval. Some challenges I came accross were editing the charts in order to depict the data I wanted and I overcame this by playing around with it and moving data until it produced the format I needed. To find the amount of successful plays for each row I used this equation, [Successful Data](https://github.com/evanbruno617/kickstarter-excel-data/blob/main/Resources/Screen%20Shot%202022-02-06%20at%206.27.54%20PM.png), for the failed plays I used, [Failed Data](https://github.com/evanbruno617/kickstarter-excel-data/blob/main/Resources/Screen%20Shot%202022-02-06%20at%206.27.21%20PM.png), and for cancelled plays I used [Cancelled Data](https://github.com/evanbruno617/kickstarter-excel-data/blob/main/Resources/Screen%20Shot%202022-02-06%20at%206.26.17%20PM.png). With this information I developed the following chart. 
  
  
![Outcomes Based on Goals](https://raw.githubusercontent.com/evanbruno617/kickstarter-excel-data/main/Resources/Outcomes_vs_Goals.png)
  
---

## Results

  From the theatre outcomes data I can conclude that the number of successful campaigns increase in spring to its peak in early summer until it slowly declines going into fall. Late fall and early winter, around November to December, seems to be the worst months for successful campaigns as it declines drastically and nearly matches the amount of failed campaigns. The best time to start campaigns would be in the spring as they have the highest success rate. Based on the outcomes based on goals data I can conclude that the highest percent of successful campaigns have goals of 1000 or less. Some of the limitations on the data set is that there is much more data for lowwer goal campaigns than higher ones so the data may not accurately portray the success or failure of these campaigns. Another table I would consider creating is a similiar one for outcomes based on goals but instead include all of the subcategories for theatre to have a larger sample to work with in order to obtain more accurate information. 
  

