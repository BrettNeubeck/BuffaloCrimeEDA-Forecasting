# BuffaloCrimeEDA-Forecasting

This project serves as a comprehensive demonstration of crime analysis in Buffalo, utilizing an API linked to Buffalo's open data resources. In recognition of the potential data reliability issues noted on the Buffalo Open Data website prior to 2009, the decision was made to focus exclusively on data spanning from 2009 to the present day.

The primary objectives of this endeavor encompass several key aspects:

1. **Data Acquisition Through APIs**: The project commences by harnessing the power of Application Programming Interfaces (APIs) to efficiently collect and retrieve crime-related data from Buffalo's open data repository. This process ensures access to up-to-date and reliable information, essential for subsequent analysis.

2. **Exploratory Data Analysis (EDA)**: Following data acquisition, an initial exploratory analysis phase ensues. During this stage, the project aims to uncover valuable insights and trends within the crime data. This involves examining patterns by year, neighborhood, and crime type, shedding light on key factors influencing Buffalo's crime landscape.

3. **Forecasting Techniques**: Building upon the EDA findings, the project delves into advanced forecasting techniques to enhance our understanding of future crime trends. Three primary forecasting methods are employed:

   - **Simple Moving Averages**: This technique applies a straightforward moving average approach to predict future crime rates. It involves calculating the average of crime occurrences over a defined period, such as months or weeks, providing a basic yet valuable forecasting tool.

   - **Weighted Moving Averages**: In this approach, a weighted average is employed, assigning different levels of importance to data points based on their proximity to the prediction point. This method accommodates the potential significance of recent crime data in making forecasts.

   - **Exponential Moving Averages**: Recognizing the exponential decay of relevance in historical data, exponential moving averages assign greater weight to recent data points. This technique is particularly useful for capturing short-term fluctuations and trends in crime rates.

By integrating these forecasting techniques, the project aspires to provide actionable insights for stakeholders in Buffalo's law enforcement and community planning sectors. Ultimately, the goal is to enhance crime prediction accuracy, enabling proactive measures to mitigate potential issues and improve public safety. Through this multifaceted approach, the project contributes to a data-driven understanding of crime dynamics in Buffalo and empowers the city to make informed decisions for a safer future.
