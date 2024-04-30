Feynn Labs Project 2 Assignment 

Market Segment Analysis of EV Market in India 

A. Contributors :-   Maurya Mayank 

B.  Fermi Estimation: 

we aim to address the question of what type of electric vehicle the company should produce. To achieve this, we will utilize data on electric vehicle sales in India to estimate the demand for different types of electric vehicles, including cars, two-wheelers, three-wheelers, and commercial vehicles. 

Total Electric Vehicle Sales: We will gather data on the total number of electric vehicles sold in India over a specific period, typically the past few years. This data will provide us with insights into the overall market size and growth trajectory of the electric vehicle industry. 

Segmentation by Vehicle Type: By categorizing the electric vehicle sales data based on vehicle type (e.g., passenger cars, two-wheelers, three-wheelers, commercial vehicles), we can estimate the relative demand for each vehicle category in the market. 

Trends and Preferences: Analyzing the sales trends and consumer preferences within each vehicle category will help us identify the most promising segments with high demand and growth potential. 

 

In addition to understanding the overall market size and preferences for electric vehicles in India, it's crucial to identify the most promising states to target for the startup's operations. We can address this question by analyzing state-wise electric vehicle sales data to estimate the demand and growth potential in different regions. 

State-wise Electric Vehicle Sales Data: We will collect data on electric vehicle sales broken down by state or region within India. This data will provide insights into the geographical distribution of electric vehicle adoption and highlight regions with significant market demand. 

Sales Trends and Growth Rates: Analyzing the sales trends and growth rates of electric vehicles in each state will help us identify regions experiencing rapid adoption and potential saturation in the market. 

 

C. Data Sources :-  

The data used in the report are obtained from the following sources: 

Open Government Data:- (https://vahan.parivahan.gov.in/vahan4dashboard/vahan/view/reportview.xhtml) 

 

D. Data Pre-processing :- 

Before proceeding with analysis, the collected data underwent several pre-processing steps to ensure its quality and suitability for further analysis. The following steps were undertaken as part of the data pre-processing phase: 

Data Cleaning: 

Removal of Duplicate Entries: Identified and removed duplicate records from the dataset to eliminate redundancy. 

Handling Missing Values: Addressed missing values by imputing them with appropriate values or removing rows with missing data. 

Data Transformation: 

Converting Object Variables to Integer Variables: 

Identified columns containing object (string) data types that needed to be converted to integer format for analysis. 

Replaced any non-numeric characters (e.g., ",", "$") with empty strings or removed them to convert the object variables to integers. 

Renaming Columns: 

Reviewed the column names to ensure clarity and consistency. 

Renamed columns as necessary to improve readability and align with analysis objectives. 

Standardizing variables: 

 Scaling numerical variables to a common scale. 

Creating new features:  

Deriving new variables from existing ones to capture additional information. 

Reshaping the dataset 

 

Data Integration: 

Merged Datasets: Integrated multiple datasets obtained from different sources by merging them based on common identifiers or key variables. 

Standardized Variables: Ensured consistency in variable names, units of measurement, and data formats across datasets. 

Exploratory Data Analysis (EDA): 

Visualization: Conducted exploratory data analysis through visualization techniques to gain insights into the data distribution and relationships. 

Summary Statistics: Calculated summary statistics to summarize the central tendency and variability of numerical variables. 

This visualization shows the dominant Vehicle of market. ie. 2WN, 3WT. 

 

This visualization shows the percentage change of HGV is very 	high compare to rest of the vehicle. 

 

This visualisation shows the maximum customer of Electric 	vehicle is of Uttar Pradesh, Maharashtra and Karnataka. 

 

E. Segment Extraction :- 

 

In the context of segmentation analysis, segment extraction refers to the process of identifying distinct groups or clusters within a dataset based on similarities or patterns in the data. Machine learning (ML) techniques play a crucial role in segment extraction by automatically identifying these groups without the need for explicit rules or predefined criteria. 

some ML techniques we used for segment extraction: 

K-means Clustering 

Hierarchical Clustering 

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) 

We get good result from K-means clustering and Hierarchical clustering. DBscan does not work proper on this dataset. 

 

F. Profiling and describing potential segments :- 

Based on the segmentation analysis, we have identified distinct clusters within the dataset, each representing a unique segment of the market. Here are the insights derived from the segmentation: 

Vechicle Types :- In this we segment types of electric vechicle is the target. 

 

Cluster 1: 

Vehicle types in this cluster have varying growth rates, with some experiencing positive increases, while others show fluctuations or declines. 

Examples in this cluster include 2WIC, 2WT, 3WN, 4WIC, HMV, HPV, LGV, LMV, LPV, MGV, MMV, MPV, OTH. 

 

Cluster 2: 

This cluster contains two vehicle types, 2WN and 3WT, with very high increases in total numbers over the years. 

The percentage increases for these vehicle types are consistently positive, indicating significant growth. 

Targeting this vehicle type could be advantageous due to its substantial growth rates, suggesting high demand and market potential. However, it's worth noting that the growth rate of 2WN is slightly higher than 3WT, making it a slightly more positive choice. 

 

Cluster 3: 

This group has just one type of vehicle HGV, and it's doing okay. Its percentage increasing very high, but sales is not as much as the superstar in Cluster 2. 

 

Geographic Characteristics: 

We have two choose 2WN and 3WT so we target geographical characteristics based on these separtly.  

For 2WN:- 

 

Cluster 0: 

States in this cluster have relatively low numbers of electric vehicles registered over the years. 

These states might be in the early stages of electric vehicle adoption or have slower growth rates. 

Examples: Andaman & Nicobar Island, Arunachal Pradesh, Assam, Bihar, Chandigarh, Goa, Haryana, Himachal Pradesh, Jammu and Kashmir, Jharkhand, Ladakh, Manipur, Meghalaya, Mizoram, Nagaland, Puducherry, Punjab, Tripura, UT of DNH and DD, Uttarakhand, West Bengal. 

Insight: Targeting this cluster could be beneficial for tapping into potential growth areas where electric vehicle adoption is still in its infancy. However, sales might be slower initially compared to more established markets. 

Cluster 1: 

States in this cluster have moderate to high numbers of electric vehicles registered over the years, indicating steady growth. 

Examples: Karnataka, Maharashtra. 

Insight: This cluster represents mature markets with steady growth trends. While these states have already adopted electric vehicles, there could still be opportunities for further expansion and increasing market share. 

Cluster 2: 

States in this cluster have high numbers of electric vehicles registered and significant growth rates over the years. 

Examples: Andhra Pradesh, Delhi, Gujarat, Kerala, Madhya Pradesh, Odisha, Rajasthan, Tamil Nadu, Uttar Pradesh. 

Insight: This cluster represents high-growth markets with considerable demand for electric vehicles. These states offer substantial opportunities for rapid expansion and capturing a significant market share. 

  

For 3WT:- 

 

Cluster 0: 

States in this cluster generally have lower sales of electric vehicles across all years. They may have relatively lower market demand or slower adoption rates for electric vehicles compared to other clusters. 

Examples include Andaman & Nicobar Island, Arunachal Pradesh, Goa, Himachal Pradesh, and others. 

Cluster 1: 
	 

Uttar Pradesh is the only state in this cluster. It shows a significant increase in electric vehicle sales from 2021 to 2024, suggesting a potentially high-growth market. Uttar Pradesh may be an attractive target for your startup due to its substantial growth in electric vehicle sales over the years. 
 

 Cluster 2: 
 

States in this cluster exhibit fluctuating sales trends, with some showing significant increases in sales over the years. 

Examples include Assam, Bihar, Delhi, Maharashtra, Rajasthan, and others. These states may represent markets with potential growth opportunities, although sales trends may vary. 

 

F. Selection of target segment 

Based on the insights derived from the segmentation analysis, the selection of the target segment involves identifying the most promising cluster(s) that align with the company's objectives and capabilities. 

Based on vehicle type analysis, focusing on 2WN and 3WT, could be a strategic approach for us to electric vehicle startup. 

Based on 2WN  state analysis : The best target cluster for your electric vehicle startup sales would likely be Cluster 2. Targeting states with high growth rates and significant demand, such as Andhra Pradesh, Delhi, Gujarat, Kerala, Madhya Pradesh, Odisha, Rajasthan, Tamil Nadu, and Uttar Pradesh, can help maximize sales and accelerate the growth of your startup. These states offer a fertile ground for expanding your market presence and establishing a strong foothold in the electric vehicle industry.¶ 

Based on 3WT state analysis : Based on my analysis for 3WT , if you're looking for immediate growth and potential market penetration, targeting states in Cluster 1 (such as Uttar Pradesh) might be a strategic choice. Additionally, Cluster 2 sales trends may vary, these states represent markets with latent demand and potential for growth, making them attractive targets for market expansion.¶ 

 

Github Link :- ( https://github.com/mmayank2/Market-Segment-Analysis-of-EV-Market-in-India ) 
