# Web Scraping Job Recruiting Website Using Selenium & Python

https://docs.google.com/presentation/d/1JC5lLi7bl61XO42e35yccHu4FWKjDMgIwGuqxSC-8fk/edit


## Objective & Business Value

* Learn how the data science job market in Hong Kong looks like

* Provide the hiring information (including but not limited to the following) to potential candidates:
  * Number of job openings available
  * Number of companies are recruiting
  * Average years of experience required for different levels of position
  * The most sought-after technical skills 


## Data Collection Method

* We picked JobsDB among other recruit portals as it offers the highest number of jobs from IT industry locally

* Based on filters available on JobsDB, we collected data of the following 3 job functions for further study:
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
![alt Text]()
![alt text](https://github.com/deschiu/Bootcamp-Colab-Showcase-Project-2-ML-Project-Mental-Health-in-Tech/blob/master/images/Mental%20Health%20in%20Tech.png)


## Limitations

* Counts on the most common required skills relies on a pre-defined list of skills
  * Skills not inlcuded in the list are left out
  
* Many job postings are posted by headhunt companies 
  * May lead to conclusion that these companies are hiring data science related jobs


## Moving Onwards

* Increase representation of the analysis by collecting data from other recruit portals
  
* Get insights of hiring trend by doing a scraping previous period's data (e.g. last month/ last year)
