# Starbucks Capstone Project
Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. The project is in collaboration with Starbucks where we were given simulated data that mimics customer behavior on the Starbucks rewards app.

## Table of Contents
* [Motivation](#moti)   
* [Libraries Used](#prerequisite)
* [Files Description](#desc)  
* [Summary](#summary) 
* [Acknowledgement](#acknow)  

<a name="moti"></a>
## Motivation
The motivation behind this project was exploring the Starbuck’s Dataset which simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.   
Therefore, we want to take a close look at our user demographics, the offers sent out and how both factor into action done in the end by the user. We want to eventually be answering these following questions:
* What are the age groups that use the app most frequently?
* What are the offer types that each age group receive?
* What are the incomes of people that have used each offer type?
* What is the ratio of offer completion for old and new app users?
* What is the ratio of offer receival to view for each offer type?
* What is the ratio of offer completion to view for each offer type?

<a name="prerequisite"/></a>
## Libraries Used
For this project, I used Python's version of Anaconda Distribution. It installs all the necessary packages and libraries. The libraries needed for this project were: 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Json
* Math

<a name="desc"></a>
## File Descriptions
The data is contained in three files:

* portfolio.json - Containing offer ids and meta data about each offer that Starbucks ships out (duration, type, reward, etc.)
* profile.json - Containing demographic data for each customer that uses the Starbucks app
* transcript.json - Containing records for transactions, offers received, offers viewed, and offers completed and also the time of each of these events

<a name="summary"/></a>
## Summary
As a brief summary of my findings:
#### i. Question 1 finding(s):
We found out that ages 45-65 are the most frequent that use the Starbucks app.

#### ii. Question 2 finding(s):
The percentage of informational offers sent was less than the bogo and discount offers by 50% across all age groups. Also, the number of bogo offers was almost similar to the number of discount offers across all age groups

#### iii. Question 3 finding(s):
There was no visible pattern between offer types and income. All 3 had the same distribution pretty much.

#### iv. Question 4 finding(s):
The number of completed offers by newer members was more than 4 times the number of completed offers by older members.

#### v. Question 5 finding(s):
Bogo offers were the most viewed offers (83.1%) followed by informational offers (70.2%) followed by discount offers (69.2%)

#### vi. Question 6 finding(s):
Discount offers were the most viewed offers (63.6%) followed by bogo offers (56.9%) followed by informational offers (53.7%)

<a name="acknow"/></a>
## Acknowledgement
I would like to thank Udacity for this amazing project, and Starbucks for providing the data.
