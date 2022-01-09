# CSCI-B 565 Data Mining Final Project - LinkedIn Job Listings Analysis: Discovering Data Science Job Market Trends
  
Authors: Aishwarya Budhkar (abudhkar) Jagriti Kumari (jkumari)

### Motivation

LinkedIn already has an abundance of job advertisements in its database, and hundreds of jobs are posted each day. With so many jobs, it has become difficult to find the actively hiring roles that are most relevant jobs for the candidate.  
    
A job seeker tends to apply to the jobs that are most coveted. For example, a recent college graduate with major in MS in Data Science, may look for jobs that are titled ‘Data Scientist’ and may skip looking at the job description of a ‘Research Analyst' that may have posted the roles suitable for a data scientist. For this reason, we have built a job recommendation system using cosine similarity to address the issue.  

Moreover, potential candidates face many rejections from the companies that require a combination of skills. This may be because a person cannot possibly learn all the skills in the world. Understanding the combination of skills that are listed frequently for a job type, that the candidate is interested in, can help them do targeted preparation to increase his or her chance of getting selected at the company.   

For universities, understanding the latest trends in the data science job market is important so they can tailor their curriculum to teach industry-relevant skills. 

### Project structure

#### datasets/ - Contains the Web-scraped Linkedin data in CSV files for job titles containing Data Science, Data analyst, Applied scientist, Machine learning enginner, Big data enginner, Statistician and Researcher.

#### Data mining mini presentation.pdf - Project presentation

#### Report.pdf - Final project report

#### DataMiningProject.ipynb - Contains project code orgainized in following sections
1. Data Collection
2. Exploratory Data Analysis
3. Data Preprocessing
4. Classify job description into different job roles
5. Job recommendation based on document similarity
6. Apriori analysis to determine skills often listed toghether to recommend skills training for job seekers for the roles
