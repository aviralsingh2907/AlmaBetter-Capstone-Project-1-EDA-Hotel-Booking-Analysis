# AlmaBetter Capstone Project 1: EDA Hotel-Booking Analysis

Have you wondered about the best time of year to book a hotel room? Or the optimal length of stay in order to get the best daily rate? Is there a way to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?
Those questions can be explored with the help of this hotel booking dataset.

This data set contains booking information for a city hotel and a resort hotel, and includes information such as time of booking, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
Explore and analyse the data to discover important factors that govern or affect the bookings.

## Project Summary
The Hotel Booking EDA Capstone project is a data analysis project that aims to explore and gain insights into hotel booking trends and patterns. The project is hosted on GitHub and contains a detailed analysis of hotel booking data using Python and various data analysis libraries.

The project begins with an introduction to the dataset used. The dataset contains information on hotel bookings, including customer demographics, booking information, and cancellation status. The project summary provides an overview of the dataset and its characteristics, such as the number of records, columns, and missing values.

The project then moves on to exploratory data analysis (EDA), which involves visualizing and summarizing the data to gain insights into the patterns and trends. The EDA section is divided into several subsections, each of which focuses on a specific aspect of the data. For example, one subsection explores the distribution of booking cancellations, while another examines the seasonality of bookings.

The EDA section utilizes several popular data analysis libraries in Python, including Pandas, Matplotlib, and Seaborn. The project showcases the power of these libraries in transforming and visualizing the data, such as using heatmaps and scatterplots to display correlations between different variables. The project also highlights the importance of data cleaning and preprocessing, as several steps are taken to handle missing values and outliers.

The project then moves on to a booking pattern section, which aims to figure out the factors governing booking cancellations. The section describes the process of splitting the data into training and testing sets, selecting appropriate features, and evaluating the data using various metrics.

The project highlights several interesting findings, such as the high cancellation rate for bookings made without a deposit, and the seasonal variations in booking patterns. The project also notes the limitations of the dataset, such as the lack of information on external factors that may influence booking behavior.

In summary, the Hotel Booking EDA Capstone project provides a thorough and detailed analysis of hotel booking data using Python and popular data analysis libraries. The project demonstrates the power of data visualization and preprocessing in gaining insights into complex datasets and highlights the importance of careful model selection and evaluation. The project is a valuable resource for anyone interested in data analysis or the hotel industry, and provides a wealth of insights and practical tips for future data analysts.

## Following approaches were taken:
• Null values in the dataset were inspected and handled. There were four variables with null values.

• Country based, i.e. Portuguese and Non-Portuguese customer analysis was done for both hotels.

• Market segment & payment mode (deposit type) wise analysis was done for both hotels.

• Analysis of duration of stay along with average daily rate was done for both hotels.

• Reserved & allotted room type analysis along with average daily rate was done for both hotels.

• Analysis of demand along with average daily rate over time was done for both hotels.

• Analysis of special requests over time was done for both hotels.

• Analysis of cancelled bookings was done for both hotels taking room type, market segment, payment mode and lead time into consideration.

• Correlation heat map analysis was done for some other variables.

## Conclusion
• Majority of the customers are Portuguese nationals (28% overall). 'City' & 'Resort' hotels are located in Portugal. 'City Hotel' is the busier than 'Resort Hotel'.

• 'Resort Hotel' has better retention rate among both Portuguese & Non-Portuguese nationals, but it should consider marketing to attract more Non-Portuguese customers.

• 'Online TA' market-segment brought most of the business to the hotels, followed by 'Offline TA/TO'.

• Most customers prefer paying at the check-out time.

• In 'City Hotel', most of the customers stay 2-3 nights. In 'Resort Hotel', customers stay 3-5 nights, indicating customers come there for a longer trip.

• The median 'ADR' for 'City Hotel' is around 100 irrespective of duration of stay, whereas for 'Resort' it increases till 6 nights of stay, but stays below 100. So for longer duration 'Resort' hotel is economical.

• The most desired room type is 'A', followed by 'D'. Majority of those who didn’t get room type 'A' were allotted room type 'D'.

• The peak season for 'City Hotel' is from March to October and the trend of 'demand' & 'adr' is similar. The peak season for 'Resort Hotel' is from February to May & October, and the trend of 'demand' & 'adr' is opposite in nature.

• 'Not getting the desired room type' doesn’t have much effect on booking cancellations.

• Hotels need to focus more on cancellations via ‘Online TA’ market-segment, as that is where majority of the 'No Deposit' cancellations are & the 'median lead time' for 'cancelled' bookings is considerably higher than 'confirmed' bookings.

• Stay during weeknights is higher than stay during weekend nights.

• The majority of the customers are adults.

• Families with babies travel less than families with grown children.
