
# Project 3: Communicate-Data-Findings

<h1 align="center">Project  3: Communicate-Data-Findings</h1>
<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Nanodegree </a></h3>


**Table of contents**

- [Investigation](#Investigation)
- [Dataset](#Dataset)
- [Summary of Findings](#Summary-of-Findings)
- [Key Insights for Presentation](#Key-Insights-for-Presentation)
- [Installation](#Installation)
- [Requirements](#Requirements)
- [Author](#Author)


## Investigation

> In this investigation, I wanted to find out the factors that affect the original loan amount using the [Prosper Loan Dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv). The features in the dataset which helped support my investigation into the original loan amount are income range, loan status, monthly income, income verifiable, months since origination, origination quarter, origination date, is borrower homeowner, term, borrow rate, listing category and monthly loan payment. 

## Dataset

> There are 113,937 loans in the dataset with 81 variables. Most variables are numeric in nature. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) and the feature documentation can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)



## Summary-of-Findings

> Many loans are issued in the last and first quarter, in the last quarter it is because of the festive season and in the first quarter it is because people would have spent too much money during the festive season and need to borrow money. As your monthly income becomes higher the more likely you are to be given a loan.

> It was discovered that original loan amount and monthly loan payment have a strong relationship. It was further discovered that this relationship is even stronger if only one term is used for each plot since the scatter plot for original loan amount and monthly loan payment was split into 3 sections using the term represented by different colors. The other numerical features did not have a strong relationship with original loan amount which is the feature of interest and these other features do not have any strong relationship between them. It was also observed that the original loan amount generally increases if the income is verifiable, the borrower is a homeowner and the term to payback the loan is longer.


## Key-Insights-for-Presentation

> The insights that were obtained from this investigation is that generally the number of loans issued decrease as the original loan amount increases with some peaks happening in-between. It was also observed that only original loan amount and monthly loan payment have a strong relationship, the rest of the features have a weak relationship. Generally there is an increase in the average original loan amount as the years progress. It was observed that the scatter plot of original loan amount against monthly loan payment was split into 3 sections using the terms and that each section had a linear relationship. The slope of the linear relationship increased as the term became long which means that as the term becomes longer, the borrower pays less money per month. It was observed that the average original loan amount increases as the term becomes longer. The general trend shows that the average original amount increases as the the time progresses for the 12 and 36 month terms whilst it first decreases then increases for the 60 month term.


## Installation 
```
git clone https://github.com/imukoki/Communicate-Data-Findings
cd Communicate-Data-Findings
jupyter notebook 
```

## Requirements

* pandas 
* numpy 
* Matplotlib
* Seaborn

## Author

👤 **Innocent Mukoki**

- GitHub: [Innocent Mukoki](https://github.com/imukoki)
- LinkedIn: [Innocent Mukoki](https://www.linkedin.com/in/innocent-mukoki/)
