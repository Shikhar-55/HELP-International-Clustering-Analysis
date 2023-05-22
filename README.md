# HELP-International-Clustering-Analysis

This repository contains the code and documentation for performing a clustering analysis of countries based on socio-economic and health factors. The objective is to categorize countries and provide recommendations to the CEO of HELP International on where to focus their aid efforts. The dataset used in this analysis, along with the corresponding data dictionary, can be found in the links provided below.

### Problem Statement
HELP International is an international humanitarian NGO committed to fighting poverty and providing basic amenities and relief during disasters and natural calamities. With a recent funding of $10 million, the CEO of the NGO needs to strategically allocate these funds to countries in dire need of aid. The challenge is to determine the countries' level of development based on socio-economic and health factors and recommend the countries that require the most attention.

As a data analyst, your task is to cluster the countries based on these factors and present your solution and recommendations to the CEO using a PowerPoint presentation.

### Data
The dataset contains socio-economic and health indicators for various countries. Before proceeding with the clustering analysis, it is essential to perform data inspection, exploratory data analysis (EDA), and data cleaning tasks.

### Approach
The following approach is suggested for this analysis:

Data Inspection and EDA: Perform necessary data cleaning, univariate analysis, and bivariate analysis tasks suitable for this dataset to gain insights into the data.

Outlier Analysis: Conduct outlier analysis to identify any outliers in the dataset. Based on the business needs or the number of countries affected, decide whether to keep or remove the outliers.

Clustering Models: Apply both K-means and Hierarchical clustering (single and complete linkage) on the dataset to create clusters. Note that the results from both methods may not be identical, and you may have to choose one of them for the final list of countries.

Cluster Analysis: Analyze the clusters and identify the countries in dire need of aid. Compare the variables 'gdpp,' 'child_mort,' and 'income' across different clusters to differentiate developed countries from underdeveloped ones.

Visualizations: Create visualizations for the formed clusters. Plot scatter plots of the countries based on two of the three variables mentioned above. You can also use other types of plots like boxplots to visualize the clusters.

Final Recommendations: Based on the analysis, report at least 5 countries that are in direst need of aid to the CEO. Make sure to mention the names of the countries, not just the cluster IDs or names.


### Dependencies
The following dependencies are required to run the code in this repository:

Python 3.7+

NumPy

pandas

scikit-learn

Matplotlib

seaborn

Jupyter Notebook

Please ensure that these dependencies are properly installed before running the code.

### Results
The repository includes a well-commented Jupyter notebook that contains the clustering models (K-means and Hierarchical Clustering) and the final list of countries in dire need of aid.
