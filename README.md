# HackerNews_Platform_Analysis
### Finding the Best Time to Post: A Hacker News Platform Exploration

**Disclaimer:**
This project is a guided analysis from the platform [dataquest.io](http://dataquest.io). Most of the code, all of the markdown cells, and every analysis interpretation is my own work. The guided projects provide structure on what steps to take for successful project completion. For more information about what projects dataquest.io offers and how they are structured, visit their page using [this link](https://www.dataquest.io/data-science-projects/). 

**Project Summary:**
This project aims to uncover two questions regarding the Hacker News (HN) platform. The first question is: Do "Ask HN" or "Show HN" receive more comments on average? The second question is: Do posts created at a certain time receive more comments on average?

**Key Findings:**
On average, "Ask HN" posts had more comments than "Show HN" posts. Further analysis was focused on "Ask HN" posts due to this finding. In the end, our analysis suggested that submissions at 3:00pm receive the most number of comments on average. 

**Datasource:**
The dataset for this project contains information about submissions on the HackerNews platform and can be found on [Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news-posts). The dataset was preprocessed by dataquest.io and contains only 20,000 rows versus the 300,000 seen on Kaggle. All rows that didn’t receive comments were removed and the remaining rows were sampled at random. There are 20,100 rows and 7 columns in the dataset. For further exploration of the columns, please reference the project.

**Tools Used:**
This project uses the coding language Python and the Python module csv. 

**How to Run the Notebook:**
To rerun this notebook, place the data file named ‘HackerNews_Project.csv’ into the same folder. Due to the dataset used in the project containing randomly selected rows, the results may differ. 

