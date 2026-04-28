# Lab 7 – IIoT Network Analysis: Age of Information and Reliability

## What I Did
For this lab, I analyzed how network conditions affect data freshness in Industrial IoT (IIoT) systems. I worked with a dataset that included variables such as transmission probability, packet loss probability, number of nodes, and channel quality. I began by cleaning the dataset, removing invalid values, and preparing it for analysis.

After preparing the data, I created visualizations such as scatter plots, box plots, and a correlation heatmap to explore relationships between variables. I then built a Random Forest machine learning model to predict Age of Information (AoI), which measures how up-to-date the data is in a network.

## What I Learned
This lab helped me understand how complex IIoT systems are and how multiple factors influence performance. I learned that:
- Age of Information depends on a combination of network conditions rather than a single variable  
- Packet loss has a major impact on how outdated data becomes  
- Visualization is important for identifying patterns and trends in data  
- Machine learning models can help predict system behavior, even when relationships are not obvious  

I also learned how AoI-oriented and deadline-oriented traffic behave differently in networks and how they affect system performance :contentReference[oaicite:0]{index=0}.

## Challenges
One of the main challenges was cleaning and preparing the dataset. I had to handle infinite values and remove rows with missing data to ensure accurate results. Another challenge was interpreting the visualizations, since many of the relationships between variables were not very strong or obvious.

Understanding the model results was also challenging. The dataset contained large outliers, which made the Mean Squared Error very high. Learning how to interpret these results correctly helped me better understand the limitations of machine learning models in real-world data.

## Results
The Random Forest model achieved an R² score of approximately 0.56, meaning it explained about 56% of the variation in Age of Information. The Mean Squared Error was relatively high due to extreme values in the dataset, but the model was still able to capture overall trends :contentReference[oaicite:1]{index=1}.

Feature importance analysis showed that packet loss probability was the most significant factor influencing Age of Information, with a much higher impact than other variables. This confirmed that reducing packet loss is critical for maintaining fresh and reliable data in IIoT systems.

## Summary
This lab demonstrated how machine learning and data analysis can be used to study complex network behavior. It showed that improving system performance requires balancing multiple factors, including reliability and data freshness.

Overall, this lab strengthened my understanding of IIoT networks and gave me experience applying machine learning to analyze and solve real-world engineering problems.
