# The 2019 Tech Workforce

With the 2018 year coming to an end, I wanted to take a look at a recent Stackoverflow survey that examined all aspects of the developer experience from career satisfaction and job search to education and sound preference when coding. This survey received more than 100,000 responses fielded from 183 countries and dependent territories.

Based off of the survey results, there are 3 questions that I am looking to answer:
- What types of languages, databases, platforms and frameworks were used in 2018 and what will be the trend for 2019?
- What do people tend to look for more in a potential job?
- Where do developers see themselves in 5 years?
        

Data was received from the following:
https://insights.stackoverflow.com/survey

## Files
The following files are located in this directory:
- survey_results_schema_2018.csv: This file gives you definition between all of the columns that are in the 2018 survey.  (See note below about the survey file)
- README.md: The file you are reading now!
- DataScience.ipynb: The analysis notebook used

Note: Due to size of the 2018 dataset, the file is not in my github repo.  At the time of writing this notebook, the file was roughly 191Mb (91MB over the Github limit of 100MB).  The file can be downloaded from the link above

In terms of dealing with missing values in the dataset, I will be creating temporary tables that focus only on the columns that are being analyzed.  I will remove the rows with missing values on the temporary tables only.  
