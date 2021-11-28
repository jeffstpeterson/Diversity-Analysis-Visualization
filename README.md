
# Diversity Analysis Visualization  
This project is a final project for the Data Analytics Bootcamp at UNC at Chapel Hill. 

#### -- Project Status: [Active, On-Hold, Completed]

Active 
## Project Intro/Objective
The purpose of this project is determine the correlation between a coproration's Diveristy, Equity and Inclusion (DE&I) success and the bottom line. Also will be pulling snetiment analysis as part of the exercise. 

"Diversity and Inclusion isn't just the right thing to do, it's good for business and our economy." Joyce Beatty, U.S Representative. (Forbes May 2019.)In today's world a DE&I program is socially relevant. The question is does this social relavance translate into an defined and positive impact on the company itself?  To put it another way, does DE&I success equal more profitability for a company?  

This project aims to attempt to answer that through a data analysis project. This project will utilize several data analysis methods including visualization and sentiment analysis to uncover the answer.

### Methods Used
* Python Data Cleaning
* Data Visualization

### Technologies

* Python, Pandas, jupyter
* Natural Language Processing
* Excel/csv
* 

## Project Description

Initially the project started with an examination of the FAANG (Facebook, Amazon, Apple, Netflix, and Alphabet (Google)) group. However after pulling their financial data, the correlation to DE&I was tenuous at best as their rankings in DE&I was not a consistent factor. 

The new phase of the project started with finding rankings for DE&I. Utilizing Forbes 2021 America's Best Employers for Diversity (see#2) ten companies were pulled for the study. 
In order to utilize consistently similiar data, non public companies or educational instituitions,  were not utilized for the study so the order# below is the public companies rankings on this report. There will be a comparison between Top 5 
and Bottom 5. 

Top 5
#1 Jones Lang Lasalle Inc (JLL) 
#2 Booz Allen Hamilton(BAH)
#9 Aflac(AFL)
#11 VMware(VMW)
#13 Paypal(PYPL)

Bottom 5
#499 Johnson Controls (JCI)
#498 Arcbest(ARCB)
#496 Synnex(SNX)
#495 International Paper (IP)
#493 Texas Roadhouse (TXRH)

Then, utilizing Barchart.com, various financial data was pulled. 1) Historical Stock Prices going back to January 2017 2) Various analyst ratings and profit/loss data. P/L data included market capitalization, shares outstanding, annnual sales, annaul net income, 1-5 year returns and earnings growth. 

After downloading data and doing data clean up and merging in pandas, the data was ready for import into Tableau. 

The goal of the data visualization first was to establish any differance between the Top 5 on Forbes rankings and the Bottom 5 on Forbes rankings. 
*The initial analysis does show some correlation between the Top 5 and Bottom 5
*However one question still need exploring is whether the this is due to larger profit businesses (Financial and Insurance) are on the Top 5. i.e. chicken or the egg?


![EPS Growth](https://github.com/jeffstpeterson/Diversity-Analysis-Visualization/blob/main/images/EPS%20Growth%20LY.png)
![Others](https://github.com/jeffstpeterson/Diversity-Analysis-Visualization/blob/main/images/Other%20Comparison.png)

Next part of the project is to determine a sentiment analysis differance

First-Need to determine where to get data-Web scraper didn't work intiially. Decided to do a manual approach and pulled JLL and IP as representatives of Top and Bottom. 



ROADBLOCKS
*Doing the analysis on sentiment. 
*Webscraping

## Needs of this project

- 
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

*https://www.forbes.com/best-employers-diversity/#83534629b9e9

## Contact

Jeff Peterson
jeffstpeterson@icloud.com 
