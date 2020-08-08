# ds_salary_proj

# Data Science Salary Estimator: Project Overview
--> Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.                      
--> Scraped over 1000 job descriptions from glassdoor using python and selenium.                                                       
--> Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.                                   
--> Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.                                                            
--> Built a client facing API using flask.                                                                       

## resources & Code
#### Packages:  
pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle
#### For Web Framework Requirements: 
pip install -r requirements.txt
#### Scraper Github: 
https://github.com/arapfaik/scraping-glassdoor-selenium
#### Scraper Blog Article:
https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905
#### Flask Productionization: 
https://towardsdatascience.com/productionize-a-machine-learning-model-with-flask-and-heroku-8201260503d2

## WEb Scraper
From the above github repo. scrape 1000 job postings from glassdoor.com. With each job, we got the following:
--> Job title                                                                                                                                          
--> Salary Estimate                                                                                                                                        
--> Job Description                                                                                                                                   
--> Rating                                                                                                                                   
--> Company                                                                                                                                          
--> Location                                                                                                                             
--> Company Headquarters                                                                                                              
--> Company Size                                                                                                                                        
--> Company Founded Date                                                                                                             
--> Type of Ownership                                                                                                                 
--> Industry                                                                                                                            
--> Sector                                                                                                     
--> Revenue                                                                                                                                   
--> Competitors                                                                                                                                  

## For the detailed documentation:
https://www.notion.so/Data-Science-Salary-Project-922dea4433794216b579514ed0a4eb65
