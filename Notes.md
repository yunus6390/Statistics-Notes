# What is statistics

- The science of uncertainty
- Methods for collecting, analyzing, interpreting, and presenting empirical data
- Two fundamental ideas in the field of statistics are:
    1. Uncertainty
    2. Variation

## Three Stages of Statistics

- Design/Planning
  - Data collection, data manipulation

- Descriptive
  - Presenting, organizing, and summarizing data

- Inferential
  - Drawing conclusions about a population based on data observed in a sample

| Sr. No | Descriptive Statistics | Inferential Statistics |
|:---|:---|:--|
| 1 | Concerned with describing the target population | Make inferences from the sample and generalize them to the population |
| 2 | Organize, analyze, and present the data in a meaningful manner | Compare, test, and predict future outcomes |
| 3 | Final results are shown in the form of charts, tables, and graphs | Final result is the probability scores |
| 4 | Describe the data which is already known | Tries to make conclusions about the population that is beyond the data available |
| 5 | Tools - Measures of central tendency (mean, mode, median), spread of data (range, variance, standard deviation, etc.) | Tools - Hypothesis tests, analysis of variance, etc. |

### Example of Descriptive and Inferential Stats

| *Descriptive Statistics* | *Inferential Statistics* |
|----------------------------|----------------------------|
| *Graphical*              | *Confidence interval*    |
| - Arrange data in tables   | - Margin of error          |
| - Bar graphs and pie charts|                            |
| *Numerical*              | *Compare means of two samples* |
| - Percentages              | - Pre/post scores          |
| - Averages                 | - t Test                   |
| - Range                    |                            |
| *Relationships*          | *Compare means from three samples*  |
| - Correlation coefficient  | - Pre/post and follow-up   |
| - Regression analysis       | - ANOVA = analysis of variance        |

### Design/Planning

1) ### Purpose: Why are we doing this study?

   - Insights -> EDA -> Descriptive
   - Result -> Inferential 

2) ### Population vs. Sample

   - Census: all members in the population
   - Sample: a small group of members
      - Sampling Method
      - Survey

3) ### Observational study vs. Experimental Study

   - Observe data as it is and give some idea based on the data like EDA.
   - In experimental studies, we compare, relate, generate inference, conclude, and make recommendations. All research work is done through experimental studies. Experimental studies are more expensive than observational studies.
   
4) ### Primary vs. Secondary Data

   - Primary data: collected by the researcher (human or machine), original data
     - Costlier & time-consuming
     - Require lots of research and surveys
   - Secondary data: collected from already available datasets
     - Cheaper & less time-consuming
     - Collected from primary data (computers, software, etc.)
     
#### Sampling Techniques

   **Probability vs. Non-Probability Sampling**

- **Simple Random Sampling**: Select sample randomly
- **Stratified Sampling**: Divide population into groups and take a sample from each
- **Cluster Sampling**: Divide population into groups and select a sample from each group (e.g., education level: high school, graduate, post-doctoral)
- **Systematic Sampling**: Equal interval between two points
- **Multistage Sampling**: Refine the selection based on the previous step sample
   
   **Non-Probability Sampling**
- **Quota Sampling**: Define quotas for different categories and aim to get at least that many persons from every category
- **Snowball Sampling**: Example: Interview panel for selecting samples
- **Judgemental Sampling**: Example: Selecting an interview panel
- **Convenience Sampling**: Example: Customers buying products from a store
   
    Google's Data Collection:
    Google uses its search engine to gather information about any topic they want to know about. They don’t just rely on traditional news sources; instead, they seek out information from all over the web about its users' searches, clicks, YouTube views, likes, shares, and subscriptions. They then use that data in ML models to predict user behavior.
  

5) ### Feature  Engineering

    - Transform raw data to useful features that can be used for analysis this works when you know the pupose  of your project 
    - Can include calculations, aggregations, binning, encoding, etc.   
    - Not always necessary but recommended before model building

#### Scale of measurment

- Nominal:  No order or relationship among categories
  Gender, Zip code, Eye color, Political Affiliation,Religious  Affiliation, Nationality
- Ordinal:  Order exists among categories
  Education level(High school graduate, Some college, Bachelor’s degree, Master’s Degree, Doctorate)
   Grades,judgement(1st,2nd,3rd),Rating,Ranking
- Interval:  There is an order and difference among categories
  Age, Temperature, IQ test score, Weight, Height
- Ratio:   No difference in differences among categories
  Salaried income, Number of hours worked per week, Body mass index(BMI), Birth weight
  - Sociological surveys are collect the data on below type

>     - Nominal | Categorical data
>     - Ordinal | Categorical data
  
#### Data  types/Variable  Types

- Numerical: 
  - Continuous
    A continuous variable is a type of quantitative variable that can take an infinite number of possible values within a certain range.
     - Examples: temperature, salary, age, height
  - Discrete
    
- Categorical : Finite / Infinite
   A discrete variable is a type of quantitative variable that can only take on specific, distinct values. These values are typically integers or whole numbers and cannot take on values between the specified points. Discrete variables are often counted rather than measured.
  - Ordinal: Ordered without gaps
  - Nominal: Ordered with gaps
  ##### Types of Variable
  1) Dependant  variable Vs Independant 
   Dependant Variable:(Target Variable): This is what we want to predict  using our model. It is also known as response variable. 
   Independant  variables:  Variables that do not directly affect the outcome but help predict it. They provide information about  variable.
  2) Time Series  vs Cross Sectional

#### Types of Studies

- Cross-sectional: No time component
- Time series: Observation over time
- Panel study: Multiple observations over time for same individuals or firms
- Longitudinal study: Follow up after initial observation