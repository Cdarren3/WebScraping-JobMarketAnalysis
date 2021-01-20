# Web Scraping Job Recruiting Website Using Selenium & Python



## Objective & Business Value

* Learn how the data science job market in Hong Kong looks like

* Provide the hiring information (including but not limited to the following) to potential candidates:
  
  * Number of job openings available
  * Number of companies are recruiting
  * Average years of experience required for different levels of position
  * The most sought-after technical skills 


## Data Collection Method

* We picked JobsDB among other recruit portals as it offers the highest number of jobs from IT industry locally

* Based on filtering available on JobsDB, we collected data of the following 3 job functions for further study:
  
  * Data Scientist
  * Database administrator (DBA)
  * Business Analyst/ Product Management


## Tools Involved

* Beautiful Soup
* Selenium
* Pandas
* Regex
* Matplotlib


## Key Findings

* The job market favors job seekers with average of 4 years of work experience
* Among the 3 job functions, Business Analyst accounts for the most no. of jobs (52%), followed by Data Scientist (25%) and DBA (22%)
* Python ranked 4th in terms of most mentioned technical skill
* Technical skill are less frequently mentioned than generic skills, suggesting possibilities that:
    * These skills are considered less important, and/or 
    * People who write the JDs are less familiar with technical skills required for Data Science roles



![alt Text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(0).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(1).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(2).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(3).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(4).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(5).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(6).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(7).png)


![alt text](https://github.com/Cdarren3/WebScraping-JobMarketAnalysis/blob/main/img/202009_%20%20Web%20Scraping%20-%20JobsDB%20(8).png)




## Limitations

* Counts on the most common required skills relies on a pre-defined list of skills
  * Skills not inlcuded in the list are left out
  
* Many job postings are posted by headhunt companies 
  * May lead to conclusion that these companies are hiring data science related jobs


## Moving Onwards

* Increase representation of the analysis by collecting data from other recruit portals
  
* Get insights of hiring trend by doing a scraping previous period's data (e.g. last month/ last year)
