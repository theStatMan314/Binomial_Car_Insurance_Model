<h1>Car Claims Predictive Model</h1>

<h2>Description</h2>
The code performs a thorough data analysis and modelling workflow for a car insurance claims dataset. It begins by importing the dataset and cleaning it to remove any rows with missing values. The data is then prepared for analysis by converting specific categorical variables into factors, making them suitable for modelling.

The code subsequently generates several visualisations to explore the data. These include a histogram to understand the distribution of annual mileage, a boxplot to compare annual mileage across different age groups, and bar charts to display the frequency of various vehicle types and racial categories. A correlation heatmap is created to show the relationships between numerical variables, highlighting strong correlations. Additional plots, such as a violin plot and density plot, further illustrate the distribution and density of annual mileage across different age and income groups. The ggpairs function provides a multi-dimensional view of the relationships between credit score, annual mileage, and age.

For predictive modelling, the data is split into training and test sets. Four different models are then built and evaluated: a Generalised Linear Model (GLM), a Random Forest model, a Generalised Additive Model (GAM), and a Gradient Boosting Machine (GBM). Each model's performance is assessed based on accuracy, and confusion matrices are used to summarise the predictions versus actual outcomes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>R Programming</b> 


<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<h3 align="center">Data Manipulation:</h3>
<p align="center">- Data Manipulation including converting categorical data into numerical data, mapping them and saving the map as a vector for direct analyses</p>

<br />

<h3 align="center">Below is a series of visualisation data to represent the given motor insurance claims dataset:</h3>

<p align="center">Histogram Plot:</p>
<p align="center"><img src="https://i.imgur.com/xgIUAqn.png" height="80%" width="80%" alt="Histogram"/></p>

<br />

<p align="center">Annual Mileage by Age Boxplot:</p>
<p align="center"><img src="https://imgur.com/XhdJC3l.png" height="80%" width="80%" alt="Boxplot"/></p>

<br />

<p align="center">Vehicle Type Bar Chart:</p>
<p align="center"><img src="https://imgur.com/3VqsiRK.png" height="80%" width="80%" alt="Bar Chart 1"/></p>

<br />

<p align="center">Race Bar Chart:</p>
<p align="center"><img src="https://imgur.com/xVvMwgv.png" height="80%" width="80%" alt="Bar Chart 2"/></p>

<br />

<p align="center">Correlation Heatmap:</p>
<p align="center"><img src="https://imgur.com/JzU7r0N.png" height="80%" width="80%" alt="Correlation Heatmap"/></p>

<br />

<p align="center">Violin Density Plot:</p>
<p align="center"><img src="https://imgur.com/c0ZH9JT.png" height="80%" width="80%" alt="Violin Density Plot"/></p>

<br />

<p align="center">Ggpairs Plot:</p>
<p align="center"><img src="https://imgur.com/GtcjQGu.png" height="80%" width="80%" alt="ggpairs plot"/></p>

<br />

<p align="center">Density Plot of Income X Annual Mileage:</p>
<p align="center"><img src="https://imgur.com/WtUs5SM.png" height="80%" width="80%" alt="Density Plot"/></p>

<br />

<h3 align="center">The 4 models selected have the following outcomes:</h3>

<p align="center">Generalized Linear Model (GLM):</p>
<p align="center"><img src="https://imgur.com/7MVAmH6.png" height="80%" width="80%" alt="GLM"/></p>

<br />

<p align="center">Random Forest Model:</p>
<p align="center"><img src="https://imgur.com/tbBqKkZ.png" height="35%" width="35%" alt="RFM"/></p>

<br />

<p align="center">Generalized Additive Model (GAM):</p>
<p align="center"><img src="https://imgur.com/qsMnF5B.png" height="80%" width="80%" alt="GAM"/></p>

<br />

<p align="center">Gradient Boosting Model (GBM):</p>
<p align="center"><img src="https://imgur.com/NhmCHJG.png" height="80%" width="80%" alt="GBM"/></p>

<br />

<p align="center">Model Comparison:</p>
<p align="center"><img src="https://imgur.com/Ihktgu6.png" height="50%" width="50%" alt="Comparison"/></p>

<h2>Conclusion</h2>
The GBM model is the best performer with the highest accuracy, indicating its effectiveness in handling the data’s complexity. Both GAM and GLM models perform well, with accuracies slightly lower than GBM but still high, suggesting they are also reasonable choices for this task. The Random Forest model’s extremely low accuracy suggests a significant issue that needs to be investigated and addressed. Re-examining the data pre-processing steps, model configuration, or even data quality might be necessary to resolve this. Overall, focusing on improving the Random Forest implementation and further validating the GBM model would be beneficial for achieving robust and reliable predictions.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
