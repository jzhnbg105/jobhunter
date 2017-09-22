# jobhunter

This is an automation tool designed in the purpose of filtering and easily applying to jobs listed on indeed.ca.

******************************************************************************************
0.1
07/18/2017

1. Open job board, look up jobs that satisfy searching criteria
2. Scrape and format url, job title, company name, location, and qualification (qualified if requires less or equal to three years’ experience)
3. Open cover letter template, replace information with job posting’s information, format text, create new .txt file named after company name from job posting
4. Open job board with credential information, redirect to job posting’s url, locate nested iframe, fill out cover letter, click to continue 

******************************************************************************************
0.11                                                                               07/20/2017

5. Change the “findjobposting” function, now it can deliberately choose country and page number to start searching
6. Non-applicable jobs are excluded from job posting matrix

problem, for US website there is no clear pattern defined between links to outside website and indeed
******************************************************************************************
