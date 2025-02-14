---
layout: post
title: Vignette for NHL Data - ST558 Project-I
author : Pramodini Karwande
---


<img src="https://raw.githubusercontent.com/pkarwan/pkarwan.github.io/master/images/cut.jpg" width="300" />

Interesting finding in the project : 
This is the first project which I came across to analyse the data for NHL sport which is recognized worldwide. I got excited to  play around data for creating contingency tables and graphs, use the meaningful functions which tells a story for the data and provides insigts of the hockey sport. I'm newbie for the Hocky sport, so I learned many things while playing around APIs for NHL Data. 
	 
I created a vignette for reading and summarizing data from the National Hokey League's (NHL) API. Based on NHL APIs, I analyse data randomly. I analysed games played, wins, losses, active players for ID 12. I observed that most players are inactive and played very less number of games. Also win rate is good when number of games played is less.

To create project in R, I followed the requirements from the project description and analysed data based on my statistics knowledge. I tried to use most of the part which got covered in the course till now. 

Most difficult part of the logic and programming : 
I feel difficult part to display column content data in correct format which contains number of different variables in the list format. Also finding right data to join tables, to use for graphs when there is no domain knowledge on the hockey game is little challenging part for me.

Different approach to a similar project in the future : 
I struggle to only show created functions or I should create functions including wrapper function and display the working functionality. So I converted data frame into table and return the same in the wrapper function. Later realized that I cannot convert again kable data into data frame. Maybe I need more practice in R to use return type correctly. So I had to again send request to NHL API to get data and then use it for further analysis. In future, my wrapper function will return data frame and it can be used multiple times for further actions on the data. 
Also I like to have more domain knowledge on the dataset I'm working on in order to do deep analysis. 

The link to the project is available [here](https://pkarwan.github.io/ST558-Project1/).	
The link to the repository is available [here](https://github.com/pkarwan/ST558-Project1).
