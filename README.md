<h1 align="center">Pymaceuticals Challenge 5</h1>


<p align="center">
<img width="424" alt="ratlabs" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/5b9f97c3-fd59-47ac-af04-7160d4418c7a">


<h1 align="center">Background</h1>

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

<h1 align="center">Analysis</h1>

Here is a full detailed .ipynb file to support my findings along with the raw data files:

[pymaceuticals_starter.ipynb](Pymaceuticals/pymaceuticals_starter.ipynb)

[study_results.csv](Pymaceuticals/data/Study_results.csv)

[mouse_metadata.csv](Pymaceuticals/data/Mouse_metadata.csv)

Below is a summary of the key findings from the analysis:


*  Summary Statistics
<p align="center">
<img width="936" alt="pymaceuticals_summary_stats" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/4e5c8e0c-d60c-403b-8f93-fed6a903fa2d">


* Bar Chart
<p align="center">
<img width="456" alt="pymaceuticals_bar_chart" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/fae4ccfb-e8a8-475c-be87-3b82fd2f35fd">


* Pie Chart
<p align="center">
<img width="219" alt="pymaceuticals_pie_chart" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/8a374c58-29a1-48fe-9fe4-747432778cd0">


* Capomulin, Ramicane, Infubinol, Ceftamin Outliers
<p align="center">
<img width="469" alt="pymaceuticals_drug_outliers" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/266dc15d-8fa8-4f13-a30d-2ed99286894f">


* Box Plot
<p align="center">
<img width="319" alt="pymaceuticals_boxplot" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/4882d6a4-33e8-474b-a9b9-410987e86a09">


* Line Plot
<p align="center">
<img width="305" alt="pymaceuticals_lineplot" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/2344cb05-b0f8-4053-bc9f-cd4a615b98fc">


* Scatter Plot
<p align="center">
<img width="305" alt="pymaceuticals_scatterplot" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/6dd0d42c-b8cf-4268-aa1d-8a9fd6286935">

* Correlation & Regresssion
<p align="center">
<img width="424" alt="pymaceuticals_correlation_regression" src="https://github.com/alejandro-davila/Matplotlib_Module5/assets/135288005/0b082ea2-fab6-4822-8e05-cc4ca4c34e8c">

***

<h1 align="center">Conclusions & Comparisons</h1>

The scatter plots clearly illustrate a significant correlation between mouse size and average tumor size. Heavier mice exhibited larger average tumor volumes in comparison to their lighter counterparts. Throughout the 45-day testing period, none of the mice from the sample selection completely eliminated the tumors. Extending the testing duration could provide valuable insights into whether any of the drug regimens were capable of eradicating tumors in any of the mice.

In the latter part of the analysis, the focus shifted to drug regimens, highlighting the superior effectiveness of Capomulin and Ramicane compared to Infubinol and Ceftamine, which showed relatively similar outcomes. An exception was found with Infubinol, as it contained only one outlier. Incorporating Ramicane into Pymaceuticals' drug regimen alongside Capomulin would be a commendable choice. Further research should be conducted to explore the potential of other drug regimens in reducing tumor size as effectively as Capomulin and Ramicane.

The sample size of the study displayed a nearly equal distribution between female and male mice, with males constituting 51% and females comprising 49%. To gain more insights, it would be intriguing to analyze the tumor-size reduction rates between males and females. Determining whether one gender exhibited better success than the other in terms of tumor-size reduction would be worth investigating.

***

<h1 align="center">References</h1>

SOFTWARE/TOOLS/LIBRARIES

Anaconda, Jupyter Lab, Pandas, PythonData environment using Python 3.6


