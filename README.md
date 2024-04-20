# South Africa Automotive Industry Exploratory Data Analysis

![image](https://github.com/gregorymikuro/south-africa-automotive-industry-eda/assets/155205164/0a511d07-9ac6-4096-af6b-11ceb0eedcc7)


## 1.0 Introduction
### 1.1 Background
The project focuses on analyzing the Car Prices Dataset from South Africa, providing insights into pricing trends across various car brands and models in the South African market.

Data Source: Car Prices Dataset - https://www.kaggle.com/datasets/tamsanqalowan/car-prices-in-south-africa


### 1.2 Problem Statement
The aim is to understand pricing trends of different car brands and models in South Africa, benefiting potential car buyers, sellers, and enthusiasts interested in the market. Additionally, the dataset serves as a resource for practicing data analysis and machine learning techniques.

## 2.0 Data Access
### 2.1 Extracting the Data
The dataset is extracted using Python's zipfile module, and then read into a DataFrame using pandas.

# 3.0 Data Cleaning
### 3.1 Drop Missing Values
Rows with missing values are removed from the dataset to ensure data quality.

### 3.2 Remove Outliers
Outliers are removed using the Interquartile Range (IQR) method to enhance the robustness of the analysis.

## 4.0 Exploratory Data Analysis
### 4.1 The Prevalence of Brand Models
A bar chart illustrates the frequency of car brands within the dataset, indicating Toyota as the most prevalent brand.

![image](https://github.com/gregorymikuro/south-africa-automotive-industry-eda/assets/155205164/37a7b71f-681e-491d-8507-718d0e953e9b)

### 4.2 Correlation between Price and Engine Size
A heatmap and scatter plot visualize the correlation between price and engine size, revealing a moderate to strong positive correlation.

![image](https://github.com/gregorymikuro/south-africa-automotive-industry-eda/assets/155205164/2951b057-d513-441c-ab24-2e7d7b05d3fe)


![image](https://github.com/gregorymikuro/south-africa-automotive-industry-eda/assets/155205164/04b0156e-a1bc-48ff-99b5-e61f1f9c9251)

### 4.3 Number of Models vs Price Range
A histogram showcases the distribution of car models across different price ranges, highlighting a common price bracket of 200,000 to 600,000.

![image](https://github.com/gregorymikuro/south-africa-automotive-industry-eda/assets/155205164/cf3e9fb0-6323-4de7-a620-896bfc3ea9e7)

## 5.0 Recommendations
### 5.1 To Automotive Manufacturers
Expand Mid-Range Offerings

### 5.2 To Marketing Teams of Lesser-Known Car Brands
Increase Brand Visibility

### 5.3 To Car Dealerships
Stock More Vehicles with Popular Engine Sizes

## 6.0 Conclusion
The analysis provides valuable insights into the South African automotive market, emphasizing the significance of engine size in pricing strategies and Toyota's dominant market presence. The findings can guide stakeholders in decision-making and inform future research in the automotive sector. Visualizations and data analysis techniques employed serve as a foundation for further exploration and application.
