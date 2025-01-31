# tableau_datadev_hackathon_2425
Submission for Tableau Data Dev 2024 - 2025 Hackathon

Potential Further Improvements:

Our project satisfied our goal of improving Tableau’s current data modeling systems by creating a refined metric slider. This successfully enhances Tableau’s interactivity by allowing users to see real-time, dynamic updates to their data as they adjust a parameter slider. However, while our implementation significantly improves user experience, there are several areas for further refinement and expansion.  

1. Performance Optimization for Large Datasets:
One of the biggest challenges with real-time updates is ensuring smooth performance when working with large datasets. Currently, our project has only been tested using a simple metric, meaning that its efficiency with more complex calculations and larger datasets still needs to be validated. To improve performance, we can:  
- Use Tableau Extracts instead of live connections to speed up query processing. Extracts store a static snapshot of the data, significantly reducing query times.  
- Implement progressive loading, where only the necessary portion of data updates dynamically instead of recalculating the entire dataset at once. 
- Test with more complex metrics and larger datasets to ensure the slider functions as expected.

2. Multiple Linked Parameters:
Right now, our project only updates one metric at a time. However, real-world data analysis often involves multiple factors changing simultaneously. A natural next step would be to allow users to adjust multiple parameters at once, enabling more complex and insightful interactions.  
- Users could adjust revenue growth and expenses together to see their combined impact on profitability.  
- In financial applications, sliders could adjust interest rates, inflation, and investment growth simultaneously for a more comprehensive analysis.  
- The system could also support parameter dependencies—where changing one value dynamically adjusts another to maintain logical consistency (e.g., increasing marketing spend automatically increasing projected revenue).  

3. AI-Powered Predictive Modeling:
Beyond visualizing current trends, we can integrate machine learning models to provide predictive analytics within the Tableau dashboard.  
- Anomaly detection: If a user selects a value that significantly deviates from historical trends, the system could highlight it and provide recommendations.  
- Smart recommendations: The system could suggest optimal parameter values based on past successful trends, helping users make more data-driven decisions.  

Conclusion
While our project has already improved Tableau’s interactivity, it was only tested with a simple metric, meaning further testing and refinement are needed for more complex data scenarios. Performance optimization, multiple linked parameters, and AI-powered predictive insights are all areas where we can expand its capabilities. These enhancements will ensure that our solution remains scalable, and valuable for users working with large, dynamic datasets in live demonstration settings. 
