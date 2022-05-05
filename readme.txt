1. This project, is known as Airline Analytics. This project is for my Applied Information Management Systems class, AIMS 4715: Developing Business Apps with SQL. 

2. Project Objective:

  a. This project solves the problem of declining revenue streams in today's post-COVID-19-pandemic companies. Declining revenue streams resulting from a sharp decrease in travel led these companies to struggle to maintain their financial positions.
  
  b. By analyzing patterns in today's prices for airline tickets, we can use these patterns to plan for what flights should be offered in the future, thereby    enhancing demand. 
  
3. Job Description:

  a. The job description that inspired this project can be found here:
  https://github.com/bshah6000/AIMS_4715_Airline_Analytics/blob/f92cb7ce8dad7f7ddc1b3514b04c9ba1c9943862/job_post_biraj_shah.pdf 
  This job was basically a private accounting job, and since my primary major, Accounting, has led me to get an internship (and hopefully full-time) offer at
  PricewaterhouseCoopers LLP, my long term career plans include maybe entering private accounting at some point, and then after working there for some years, I would 
  eventually transition into teaching at the university level. In order to get there, I would have to enter the private accounting industry, which would be something 
  like the above Revenue Accounting job. This Revenue Accounting Job is at American Airlines, as a Revenue Accounting Analyst, which is one of the largest airlines in 
  the United States. The job description involves running regular daily analyses to detect fraudulent transactions, as well as running analyses on credit card 
  transactions, and finding ways to improve operational performance of the company. 
  
  b. Analysis of transactions and finding ways to improve operational performance of the company are one of the key objectives of this project. By finding ways to 
  improve top-line revenue, we can improve the operational efficiency of the company as a whole. 
  
4. Data:
  a. Source: Web Scrape from various Kayak.com URLs. The Web Scraping Code, using BeautifulSoup4, can be found in the data_collection notebook.
  b. Characteristics: The data had a lot of whitespace, so I had to use the python string function .strip() function a lot to get just the data. In addition, some of the 
  data was stored in nonstandard formats (like the flight duration was stored as 3h 16m instead of 3:16 or something else), and combining stuff to get DATETIME format 
  was also difficult.
  
5. Notebooks:

  sql_project_data_collection.ipynb: This notebook documents all the code used to collect the data from Kayak URLs. It has directions to understand what is going on in 
  each cell of the notebook. 
  
  https://github.com/bshah6000/AIMS_4715_Airline_Analytics/blob/49e4ab3768d1a758a510674d3eb10be24b7ddcec/sql_project_data_collection.ipynb 
  
  sql_analysis.ipynb: This notebook documents the analytics that I did on the data after collecting it. It includes the SQL code that I put in the notebook and 
  executed on the database, as well as the expected results. 
  
  https://github.com/bshah6000/AIMS_4715_Airline_Analytics/blob/49e4ab3768d1a758a510674d3eb10be24b7ddcec/sql_project_data_collection.ipynb
  
6. Improvements:
  a. if I had more time: Sometimes, scope of data collected seemed too narrow. In addition, distribution of flights, i.e. availability of each and every time was not 
  taken into account when collecting the data. As such, the data ended up being skewed towards flights during the day, instead of having flights everywhere, at all 
  sorts of times to paint a better picture of the market situation with regard to flight tickets. In addition, I only used one website, KAYAK, when it would have been 
  better if I had collected from multiple websites. This would mean that I would have to make new code for those different websites. 
