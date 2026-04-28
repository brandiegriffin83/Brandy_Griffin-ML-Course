# Lab 6 – IIoT Time-Series Forecasting

## What I Did
In this lab, I worked with time-series data from an IoT temperature dataset to build a forecasting model. I started by loading and cleaning the dataset, converting the datetime column into the correct format, and sorting the data in chronological order. After confirming there were no missing values, I explored the dataset using statistical summaries and visualizations to better understand patterns in temperature over time.

I then prepared the data for machine learning by selecting relevant features and restructuring it for time-series analysis. Additional features such as hour of the day, day of the week, lag values, and rolling averages were created to help capture patterns in the data. A Linear Regression model was trained using these features to predict future temperature values.

## What I Learned
Through this lab, I gained a deeper understanding of how time-series forecasting works in real-world IoT systems. I learned how important data preparation is, including cleaning, formatting, and structuring time-based data correctly. I also learned how feature engineering plays a major role in improving model performance by capturing patterns like time dependencies and trends.

I also learned how to evaluate machine learning models using metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE). The model achieved an MAE of about 1.5 and MSE of about 7.9, showing it was able to capture general trends in the data :contentReference[oaicite:0]{index=0}.

## Challenges
One of the main challenges in this lab was properly preparing the dataset for time-series forecasting. Converting the datetime column and ensuring the data was sorted correctly was critical. Another challenge was creating meaningful features such as lag values and rolling averages without introducing errors or missing values.

Understanding how to split the data correctly using a time-based approach instead of random sampling was also important. This ensured that the model was tested on future data, which better reflects real-world scenarios.

## Results
The model was able to follow overall temperature trends, although it struggled slightly with sudden fluctuations, which is expected in real-world IoT data. After the initial model was built, I experimented with generating synthetic data by adding small variations to the dataset.

This improved the model’s performance, reducing the error to approximately MAE = 1.14 and MSE = 4.69 :contentReference[oaicite:1]{index=1}. This demonstrated how data augmentation can enhance model accuracy and generalization.

## Summary
This lab demonstrated the full workflow of a machine learning project, from data preprocessing and feature engineering to model training and evaluation. It showed how forecasting can be applied to IoT data to predict future conditions.

Overall, this lab helped me understand how machine learning models can be used to analyze time-based sensor data and make predictions that are useful in real-world AI and IoT applications.
