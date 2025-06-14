# Feasibility survey insghts for a startup company

### Project Overview
---
This report effectively analyses the surevy data used to test the fasibility of a startup cpmpany's goal to create an All-In-One entertainment platform.
![omnify-1](https://github.com/user-attachments/assets/52e150af-56d6-4b49-944d-9577cc6915ac)


### Data Sources
---
The primary dataset used for this analysis is the "survey_data.xlsx", which contains actual records of responses from different persons.

### Tools
---
- Microsoft Excel - Data Cleaning
- Power BI - Data Analysis & Data Visualisation

### Data Cleaning / Preparation 
---
In the data preparation phase, the following tasks were performed:
- Loading the dataset
- Inspecting the datset for data quality issues
- Handling missing values
- Removing Duplicates
- Loadng data into Power BI
- Created a table for measures table in Power BI

### Exploratory Data Analysis
---
EDA involved exploring the dataset to answer the following questions:
- What is the breakdown of total responses by gender?
- What is the proportion of 'yes' and 'no' responses by gender?
- What are the preferrable podcast formats?
- What are the top challenges faced when switching between multiple platforms?
- What are the top preferrable features that would want to be seen on the platform?
- What are the preferrable subscription plans?
- What are the preferrable devices used for streaming?

### Data Analysis
---
Some interesting DAX worked with in power BI include :

``` DAX
Total Responses = COUNT('Untitled form-2'[Serial Number])
```

### Results/Findings
1. **Overview of Responses:** A total of 53 individuals participated in the needs assessment survey designed to test the feasibility of the proposed entertainment platform.
   
2. **Current Podcast Preferences:** For the preferred podcast format, the most selected option was "No preference" (13 responses), followed by "Conversational podcasts" (10 responses).
This suggests the startup does not need to niche down to a single podcast style, allowing flexibility in content offerings.

3. **Listening Time:** Podcasts are listened to throughout the day (morning, afternoon, and evening) by most respondents (16 responses), with morning being the next most common (12 responses). This shows that engagement is steady all day, so content can be scheduled or promoted without strict time constraints.
   
3. **Subscription and Devices:** Monthly subscription was the most preferred (19 responses).
The top devices used to stream are:
Smartphones (29 responses)
Laptops (10 responses)
Smart TVs (6 responses).
This indicates that the platform should be mobile-first, with responsive support for laptops and TVs.

4. **Motivation to Upgrade:** The leading reason for upgrading from a free to paid plan is access to high-quality content (9 responses). To increase subscriptions, the platform should emphasize premium, high-quality content offerings.

5. **Interest in an All-in-One Platform:** The main challenges reported were; 
   - Switching between apps (15 votes)
   - Managing multiple subscriptions (15 & 9 votes)
These pain points validate the problem-solution fit and support the platform's core concept.

6. **Interest in the Solution** : A significant majority; 44 out of 53 respondents indicated they would like an all-in-one platform.
Female: 25 votes
Male: 19 votes
This demonstrates strong interest across demographics and confirms product-market fit.

7. **Top Desired Features:** Users want features such as personalised recommendations, cross-device compatibility, mood-based content suggestions, multi-user access
These should be prioritized during the platform's development to enhance user satisfaction and retention. 
