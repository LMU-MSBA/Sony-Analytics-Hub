# Business Problem Definition

## Determine Business Objectives

### Background
The film industry is highly competitive, and production companies are constantly trying to find new ways to get the best return on their investments. That is why is it so important to be able to understand trends in the film industry in order to make strategic decisions as well as gain a competitive advantage over competitors. 

### Business Activity Category
The business activity category that best suits the goals and direction of this project is the Strategy section. Although ultimately the goal would be to increase revenues, the more defined objective is to be able to analyze the trends in the movie industry to give Sony Pictures the tools to make informed decisions on how to best imrpove their methods. 

### OKR (Objectives & Key Results)
Although the main objective of the project is to adjust give the Sony Pictures team the tools necessary to improve strategic decisions, the objectives of the Sony Pictures team might be much more specific. Our goal is just to make them aware to things that they might not have been aware of before using available data. So our objective will be to create deliverables for the project that are laid out in the [README](https://github.com/LMU-MSBA/Sony-Analytics-Hub/blob/main/README.md) file. A few examples of these deliverables incude different dashboards, an ETL and a predictive model. 

An example of goals for Sony Pictures could be the following:
- Increase revenues for movies produced in a specific genre (i.e. Action) by 10% in the next 5 years.

This would give Sony enought time to go through the data, make the informed decision that they should invest more into action movies, then produce more movies over the next few years that fall into that genre.

### OKR Initiatives

## Assess Situation
### Inventory of Resources
- Personnel
  - Lior Ben David - Data Analyst
  - Ben Gerber - Data Scientist
  - Inbar Geva - Data Engineer
  - Dani Le - BI Specialist

- Data
  - TMDB Movies Dataset 2024 (1M Movies)
  - Creation of ERD from mentioned dataset
 
- Computing Resources
  - Each of our personal computers

- Software
  - Excel (Data Cleaning)
  - Python (Data Analyis & Model Creation
  - mySQL Workbench (Querying & Data Manipulation)
  - Tableau (Data Visualization / Dashboard Creation)

### Assumptions & Constraints
- Assumptions
  - The data we are using should not require any licensing since it was a dataset public on Kaggle
  - We also must assume that the data we pulled from the database is accurate, so our conclusions are based on correct numbers
- Constraints
  - Time
  - Finding time to meet and work as a group since we are all busy with work and class separately

### Terminology
- Genre: Categories or types of movies (ex. Action, Comedy, Drama)
- Data Analysis: The process of inspecting, cleaning, transforming and modeling data to uncover insights and make data-driven decisions
- Predictive Modeling: Using statistical algorithms and machine learning techniques to predict future outcomes based on historical data
- Python: Programming Language
- SQL: Structured Query Language, used for managing and querying from databases
- Tableau: Data Visualization tool that can be used to create interactive dashboards

### Costs & Benefits

If we were doing this project from the point of view of Sony Pictures, then the cost would be the money spent on our group's time spent working on the project. For example, if each of us were being paid $20/hr of work by Sony, then the total price of the project would be $80xTime in Hours Billed. The reason it is $80 is since there are four of us in the group working on the project. There are no other expenses for this project as we already have the software necessary and the data was public, we did not have to pay to get it.

There is no way of saying how much money that Sony Pictures would get directly from this project. Instead, the gains would be the insights generated based around the analysis of genre. Examples of use of those insights would be figuring out which genres are more valuable to invest into, what time of year to release certain genres of film, etc. Even though the ultimate goal is to increase revenues, we are focused here on strategy as our business activity category. A general goal would be to improve stratgey based on the insights of the project in order to best imrpove ROI.

## Determine Data Mining Goals
### Data Mining Goals (Enabling Activites)

The main goal of our data mining is to find data that will be insightful to Sony Pictures to be able to make more strategic decisions on their investments. Specifically, the data must include information on genre, as we are focusing our analysis on the genre of different movies. The enabling activities that we will use to deliver our desired outcome are the following:
- F01: Increased use of external data
- F07: Increased use of structured data
- F17: Improved use of data science models
- F23: Improved use of machine learning
- F31: More data-aware exec

### Data Mining Success Criteria

For our data mining to be considered successful, we need a dataset that is usable. That means a number of things. First, there are enough variables included in the dataset so that we can make meaningful and deep insghts into the data. If there are only two or three variables, then we would have trouble doing a deep dive into the data. Another criteria is that the data needs to have enough rows. If there are not enough observations, then we can't draw anything meaningful. The data also cannot have too many missing values, and the data needs to be accurate. We will need to use the ETL (Extract, Tranform, Load)process in order to generate clean data, as the intial data will most likely not be clean. It will have missing values, formatting problems, unnecessary columns, etc. Once all of this is done, then we can say that our data mining was successful.

## Produce Project Plan
### Initial Assessment of Tools (Technology) & Techniques (Analytics)

As mentioned earlier, we will be using our personal computers to complete this project, with the following analytics tools to help:
- Excel (Data Cleaning)
- Python (Data Analyis & Model Creation
- mySQL Workbench (Querying & Data Manipulation)
- Tableau (Data Visualization / Dashboard Creation)

Each group member will bring their specific skillset in order to help us most effectively get each step of the project done.

### Data Toolkit Items

Our project will produce many different items from the data toolkit. For example, in the first sprint of the project we will create a dashboard to present with our initial findings from the data during the Aspire and Mature phases of the Analytics Maturity Scale. We will also be creating written reports throughout, such as this one. Later on during the project, we will be using data science and machine learning to create a predictive model.

### Project Plan

Loosely, our project plan will be as follows:
1. Aspire Phase
   1. Understand Bussiness Problem
   2. Find Data
   3. ETL (Extract, Transform, Load) on the Data
   4. Create Dashboard of Descriptive Analytics
2. Mature Phase
   1. Creaste a Data Governance Policy
   2. Create an ERD of the Data
   3. Create a Data Warehouse on mySQL
   4. Create an ETL Pipeline
3. Present on Findings to This Point
4. Industrialize Phase
   1. Create an Automated ETL Pipeline
   2. Create a Diagnostic Analytics Dashboard
   3. Present on the Diagnostic Analytics
5. Realize Phase
   1. Create & Test a Predictive Model
   2. Run an A/B Test
6. Differentiate Phase
   1. Create a Data Manifesto
7. Present on Findings
