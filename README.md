# Survey-data-analysis
## Overview
I conducted a comprehensive data-driven initiative with the primary objective of discerning the nuanced preferences and priorities of merchants in relation to Value-Added Services (VAS). Throughout this analysis, I focused on various dimensions, acknowledging potential divergences between countries, specific merchant verticals, business sizes, and individual respondent profiles.

My analysis delved into crucial aspects such as ranking merchants' prominent pain points, including challenges related to access to credit, seamless technology integration, the quest for loyalty solutions, and the need for efficient accounting and inventory management. I aimed not only to identify what merchants seek but also to assess whether they face difficulties in locating these solutions.

The ultimate goal of my work was to leverage the comprehensive dataset to inform the creation of tailored solutions. By integrating these insights into our offerings, the aim was to meet the unique needs of diverse merchants, thereby enhancing our value proposition and market competitiveness.

Key Questions Explored:

1. I analyzed the Value-Added Services that merchants prioritize.
2. I assessed the willingness of merchants to pay for these services.
3. I investigated how preferences vary across countries, merchant verticals, and business sizes.
4. I ranked and analyzed the primary pain points for merchants, providing insights into their importance.
5. I explored whether merchants are actively seeking solutions for specific challenges, such as credit access, seamless technology, loyalty programs, or accounting/inventory management.

I presented the findings in an informative and interactive Power BI report.

## Data cleaning and preprocessing
The data was in an excel file. The data had survey answers from merchants from different countries, business sizes, and verticals. The survey responses were from more questions unrelated to the study too. I had to select only the required data for the study, clean it, and transform it to get the best insights. I used Excel to perform Exploratory Data Analysis and understand the data better before working on it.

I then used python for data wrangling.

First, I imported all the required modules. I then imported the data using pandas, and set the dataframe's column names correctly<br/><br/>
![Import modules](./Images/Python1.png)  <br/> <br/>

I then created a new dataframe, a slice of the original dataframe, and named it raw_vas_df. It contained only the data relevant to Value added services only<br><br>
![Creating a Dataframe](./Images/Python2.png)  <br/> <br/>

The column names in this dataframe were the questions asked in the survey. They were really long and not fit for easy reading and understanding for analysis. I hence preceeded to rename the columns for easier reading during analysis.<br><br>
![Cleaning column names](./Images/Python3.png)  <br/> <br/>
![Cleaning column names](./Images/Python4.png)  <br/> <br/>
![Cleaning column names](./Images/Python5.png)  <br/> <br/>

The raw_vas_df now had clean and easy to read column names ready for transformation. I proceeded to create a dataframe to get the rating of every Value added service as rated by each merchant. I stored this transformed data in a dataframe called rating_df<br><br>
![rating_df](./Images/Python6.png)  <br/> <br/>
![rating_df](./Images/Python7.png)  <br/> <br/>
![rating_df](./Images/Python8.png)  <br/> <br/>



