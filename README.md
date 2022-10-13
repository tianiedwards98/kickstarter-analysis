# Kickstarter Analysis Project

## Overview of Project:
This project showcases how the different campaigns faired with their fundraising goals. 

## Analysis:
###### Theater Outcomes:
  In this analysis I added the Years column on to the spreadsheet and calculated it with the Year() function. This made it simple to make the pivot table filter for the years along with the Parent Category as a filter.I made the columns the outcomes and the values the outcomes or Count of outcomes. Lastly I made the rows the Date Created Conversion. When I added the Date Created Conversion the application also added the Years and Quarter fields so in order to only show the months I removed those fields but still kept the Date Created Conversion field. I believe that could be a problem someone could run into. After that I was able to use the filter button on the pivot table to sort the outcomes in a descending order and also make the Parent Category Theater. From there I was able to make the line graph from the data set that has been filtered. 
  
  ![Pivot Table](https://github.com/tianiedwards98/kickstarter-analysis/blob/main/resources/Image%2010-13-22%20at%2011.45%20AM.jpeg?raw=true)
  
###### Goal Outcomes:
	In this analysis using the data provided in the kickstarter data set. I made the new Outcomes Based on Goals spreadsheet. Added the column names and the value ranges for the Goals column. After this I used the COUNTIFS() function to determine if the goals set were successful, failed, or were canceled in their rightful columns according to the goal range mentioned in the goal column(A1). After finding those values is used the SUM() function to get the some of the total projects and found the percentages of the successful, failed, or canceled attempts and put those values on the spreadsheet(ex.number successful/total projects).From the data calculated I was able to make a line graph that lists the percentages of successful, failed, and canceled projects.
		Some challenges I ran into with this analysis was trying to figure out how to properly use the COUNTIFS() function. I was not using all of the fields that were required and I was just filtering through the Outcomes filed on the kickstarter data set.(ex. =COUNTIFS(KickStarter!F:F,"<1000",KickStarter!R:R,"plays"). 
After watching the tutorial in the hint a couple times I realized the the first criteria that I had to use was the goals field on the kickstarter data set and then filter through the outcomes to determine what was successful, fails, or was canceled. (ex. =COUNTIFS(KickStarter!$D:$D,"<1000",KickStarter!F:F,"successful",KickStarter!R:R,"plays")

![Graph](https://github.com/tianiedwards98/kickstarter-analysis/blob/main/resources/Image%2010-13-22%20at%2011.48%20AM.jpeg?raw=true)

## Results:

	I can conclude that there were a lot more successful outcomes in the theater category than were failed overall. I can also conclude that theater is very popular in summer months like May and June. For the Goal Outcomes I can conclude the lower goal amounts were more successful than the goal amounts that were higher around the 45000 or more amounts.
  
  ![Graph](https://github.com/tianiedwards98/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)
  ![Graph](https://github.com/tianiedwards98/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)
  
  Some limitations of this data set could be that it mainly focused on theater and plays which is not something I think a lot of people would use to be entertained. Another limitation could be the time in which we are analyzing the data over the years.

Some different tables/graphs we could make could be featuring different categories like film/tv or shorts. Something that is more known that a lot of people are known to use. We could also use the filters to filter the years when certain campaigns were made to find out  which was the most successful.
