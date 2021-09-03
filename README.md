# -Week-13-IP-R-Supervised-and-Unsupervised-Learning
# Advertising-and-Customer-Segmentation-Analysis-in-R

## PART 1

Data Analytic Question predict which individuals are most likely to click on ads from a cryptography course website

### Metric for Success 
For this study, we will perform conclusive Exploratory Data Analysis to enable us identify individuals who are most likely to click on ads.

We will then create various classification models to predict which individuals will click on ads. We use confusion matrix and accuracy score as our metrics of success

### Understanding the context 
A Kenyan entrepreneur has created an online cryptography course and would want to advertise it on her blog. She currently targets audiences originating from various countries. In the past, she ran ads to advertise a related course on the same blog and collected data in the process. Using the data previously collected, she is looking to do a study to identify which individuals are most likely to click on her ads.

Data Data is provided was collected in the past but from the same blog hence it is very suitable for this study.

### Definition of Variables

    - Daily Time Spent on Site
    - Age
    - Area
    - Income
    - Daily Internet Usage
    - Ad Topic Line
    - City
    - Male
    - Country
    - Timestamp
    - Clicked on Ad

Study done using google rstudio




## PART 2: Customer Segmentation

### Problem Definition

Kira Plastinina is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups.

### Data Sourcing

Data being used in this study was provided by Moringa School

### Data Description

- The dataset consists of 10 numerical and 8 categorical attributes.

- The Revenue attribute can be used as the class label.

- "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another.

## Metrics Measured by Google Analytics

- The value of the Bounce Rate feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.
- The value of the Exit Rate feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.
- The Page Value feature represents the average value for a web page that a user visited before completing an e-commerce transaction.

- The Special Day feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.

- The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.

Study done in RStudio
