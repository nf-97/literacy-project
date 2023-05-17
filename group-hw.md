## Question 1 [20 points] What is your project question(s) and the problem it tackles? 
### You will be marked on how realistic the problem is given the project timeline, as well as the fit with the subjects covered throughout the Data Specialisation and your personal, common interests in the topic. 
<br>

Our project question is to study the key factors contributing to female literacy rates in the top 5 countries vs the bottom 5 countries within the years 2000-2021. We approach this topic of female illiteracy with an understanding that there are several significant factors that contribute to this issue.This is a relevant and interesting problem to tackle, as female literacy rates remain a significant global issue, and understanding the factors that contribute to higher or lower rates can help identify areas for improvement.This question hopes to highlight the main contributing factors. Using this comparison, we would hope to see what factors would affect these rates the most and least. This would help identify where the key problem areas are for governments and charities that want to address this issue. 

Our common interests are aligned with female education combined with our international background and interests in sociological phenomena affecting gender inequality, we thought that this question would cover all bases. 

As we are considering several different factors and their influence on female literacy rates, we will be able to combine resources of different datasets to expand their data series. The objective of this project is to study the key factors, by study we mean identify and compare the key factors, once we do this with the data, we would consider the core questions answered. We will use Pandas to clean and deal with missing values in the data and Matplotlib for creating visualisations and statistical analysis.

<br>

## Question 2 [20 points] Explain your target audience. Who could be interested in reading your final report and for whom will your project be useful?
### Assess the level of expertise in relation to data science of your audience (for example, how technical should your report/presentation be?). ▪ You will be marked on correctly identifying your audience and the technical level of your presentation and report.
<br>

Our target audience is varied as this is a topic that is useful for various groups to understand female literacy rate and how they can channel resources into bridging the gap in female literacy rate. Some of our target audience are:

1) Education providers/govt authorities: For governments to achieve gender equality, it is important that women are educated at the same rate as men. Knowing the literacy rate will help them and education providers channel resources and finances into ensuring more women are educated. Government tax and spending budgets have economic, social and environmental implications on a country’s population. Reports like ours could help governments improve their gender budgets by supporting education providers and policy makers. An equally educated society helps shape people’s choices and impacts their contribution to the society at large.

2) Charities/Organisations focused on female education: There are charities that already support female literacy and education. However our report can help them channel more resources towards the bottom 5 countries in our list. For organisations who are interested in adding to their CSR this report can also help them make decisions on areas to support.

3) NGOs and women's rights advocates could also use the report's insights to design programs and initiatives that aim to improve female literacy rates in areas where it remains low. 

4) EDtech companies/charities : EDtech organisations like CFG can work on merging technology and education by expanding their involvement to countries that are more affected in our report. They can work with local community partners in the most affected countries to help improve female literacy in these countries. Our report can also encourage other edtech companies to fund charities focused on improving female literacy.
Anyone in academia focusing on female education: This report can be used for further analysis. Researchers and data scientists could use the report's methodology and findings as a basis for further research on the topic of gender equality in education.


As listed above, it can be seen that our target audience is varied therefore, we will make the report easy to understand for everyone with little to no technical knowledge by using graphs that can be interpreted easily and providing further analysis to aid further understanding in the subject matter.

<br>

## Question 3 [30 points] What data sources will you need to answer your project question(s)?
### Describe any potential issues you can have with the datasets and how will you overcome this? For example, will the data you find only cover particular geographical areas? Will you need to combine multiple datasets to overcome this?
<br>
The data sources we will be using are mostly from UNESCO Institute for Statistics, World Bank, and national statistical agencies. Their databases are essential tools for providing key statistical information; reports are consistent and reliable as they follow internationally accepted standards of data statistics. 

When combining data from national statistics websites that have different columns and table structures, there are several strategies we will employ to overcome the challenges and effectively combine the data for the project.

We start by identifying common attributes or variables across the different datasets. Look for columns or fields that contain similar information but might be named differently. Once we have identified common attributes, we will transform and standardise the data to ensure consistency. This could involve renaming columns, converting data types, or applying formatting rules. One of the most challenging parts is dealing with missing data appropriately. We first determine the reason for missing values and decide how to handle them based on the project's requirements. We may choose to impute missing values using statistical methods or remove incomplete records altogether, depending on the impact of missing data on the analysis. Lastly, we will perform thorough data validation and quality checks to ensure the accuracy and consistency of the combined dataset. This includes checking for outliers, inconsistencies, and data integrity issues.

Potential issues with datasets: 
1: The data we found is representative of the  whole world. However, not all countries are included in the data.
2: The dataset also includes data from regions which means the list of countries includes a list of regions as well
3: There are some countries with more missing data between the years. For example in the last 20 years, we only have 3 years where there has been data imputed for Afghanistan. In order to tackle this, we have used the mean literacy rate to represent the number for all the countries involved.
4: Null values and what to do with them. We are considering whether to remove the rows completely, fill it with a 0 value, predict the value or category or replace with the mode value 

<br>

## Question 4 [30 points] Describe the team approach to the project work: 
### How are you planning to distribute the workload and how are you planning to work on your project; what are your team’s strengths and weaknesses; how are you managing your code; include an expected timeline of the project?
<br>

We started off by creating a non exhaustive list of factors that would affect female literacy rates. Then we divided this list by each person on our team. Each person was tasked to research that topic and find datasets on this topic. Then we came back and spoke about the data and research that we found with each other. Then we decided on one core dataset for our data analysis. Emi and Nat cleaned and organised that dataset. We each are all tasked with cleaning our dataset similar to the core dataset. Then in our group sessions, we are planning to work on a jupyter notebook, to work together on doing the statistical analysis and the data visualisation. After this, using the results from the data visualisation, we are planning to summarise and interpret our findings and write up our conclusions. 

We will aim to get all the datasets cleaned and combined into one table by Friday the 19th. Then we will finish doing statistics and creating visualisations on Friday the 26th. During this time (19th - 26th) we will allocate someone to write the word document overview of the project. We will compile our presentation on the 26th and 27th. 

Our code is being managed via GitHub - we are creating branches for each stage (i.e., a branch of literacy dataset cleaning etc.). Once the branch is complete, we will open a Pull Request so that the code can be checked by someone else in the group. The branch will be merged into the main branch  once it has been approved. We are using Jupyter Notebooks to write our code as we can use markdowns to explain in detail how we did our code/why.

Our strengths and weaknesses are listed below:<br>

_Natalie_: <br>
* Strengths (S): data cleaning, stats, visualisations
* Weaknesses (W): APIs, report-writing

_Emi_: <br>
* S: Data visualisation, Exploratory data analysis, teamwork<br>
* W: API, organising reports

_Lilia_:<br>
* S: Expertise in statistical modelling techniques
Data cleaning, experience working with large datasets
* W: Limited experience in certain subject matter areas related to gender equality in education,
APIs

_Rhianna_: <br>
* S: Data cleaning, presentations, reports, SQL
* W: APIs, regex and lambda 


_Kayla_: <br>
* S: Google to do researching 
* W: APIs, presentation, writing and organising reports

_Befru_: <br>
* S: SQL queries, research, exploratory data analysis
* W: APIs







