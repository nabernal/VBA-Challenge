# VBA Challenge Analysis 

## Overview of Project
#### The purpose of this analysis is to refactor the macro created for the Green Stocks activity in Module 2. The macro is designed to find the daily volume and yearly return of each stock in the file provided by declaring variables, creating an array, and For loops. Now we will modify the macro in an attempt to make it shorter, easier to follow, and produce the data we are looking for in a shorter amount of time. 

##Results
#### The Declared tickerIndex variable and set it equal to zero to make sure the macro starts with the first stock each time.

![Screen Shot 2022-09-22 at 11 39 06 PM](https://user-images.githubusercontent.com/108249510/191904847-4bc1f2a1-d950-4389-a95c-112abc1f04ab.png)


#### Created three putput arrays to be used at the end of the macro. This will be used to gather the data. 
![Screen Shot 2022-09-22 at 11 48 39 PM](https://user-images.githubusercontent.com/108249510/191905906-3b322feb-a75e-4f08-892a-55e1e0a7e0f7.png)

#### This will set the volume to zero everytime the macro is used. 
![Screen Shot 2022-09-22 at 11 49 08 PM](https://user-images.githubusercontent.com/108249510/191906002-f725c8cd-fb70-4aa3-b627-c410063ac146.png)

####used For loop to increase the volume for each ticker
![Screen Shot 2022-09-22 at 11 51 03 PM](https://user-images.githubusercontent.com/108249510/191906338-4d229c26-e856-4bc9-a42e-0d087cbe5412.png)

####The first one finds finds the start of a stock. The next one finds the end of a stock. Once the last one is reached the macro runs through the next stock.
![Screen Shot 2022-09-22 at 11 56 10 PM](https://user-images.githubusercontent.com/108249510/191906862-4031311c-c0e7-4fcb-96d9-e858ba80412a.png)

####This will insert the data into the appropriate cell in the All stock Analysis 

![Screen Shot 2022-09-22 at 11 57 38 PM](https://user-images.githubusercontent.com/108249510/191907026-2ebc033e-ab42-48c4-8945-3f0bba110c23.png)


##Summary
###Advantages and Disadvantages of Refactoring Code
#### One benefit of refactoring code is that it is modified to be less cluttered. This can make it easier to read when it is revisited after a long period of time. Another benefit is that you work toward being less repetative. Which results in learning more advanced code that is used less but delivers the same outcome. Lastely, it reduces the chances of errors since you do not have to repeat the same many times. 

#### The down side of refactoring code is that it takes time. since the goal is to do the same with less code, this means you are often researching more advanced code. Which can result in mistakes if you are new to the coding world or working on a complex script. This leads to the next con which is confusion. Refactoring can be a lot of trial and error which means a lot of changes. This can then result in lossing progress if you forgot to save when you were having success refactoring the code. 

### Andvantages and Disadvantages of Original and Refactored Script
#### One advantage of the refactored script is that it did result in a faster delivery of the data. However, this comes at the cost of many hours and feelings of frustration. Despit this downside, the outcome is a better understanding of the different compartments of a macro due to the amount of time researching and retyping code. 

