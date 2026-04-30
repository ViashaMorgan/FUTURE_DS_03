# FUTURE_DS_03

# Marketing Funnel & Conversion Performance Analysis 

## 1.) Objectives


* Analyze the marketing funnel by calculating conversion rates, identifying drop-off points, and evaluating performance across campaigns and customer segments.
  
* Investigate key conversion drivers such as call duration, campaign intensity, and previous outcomes to generate actionable insights.


## 2.) Datasets

Source: UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/222/bank+marketing)

* Contains data from direct telemarketing campaigns by a bank aimed at promoting term deposit subscriptions.
  
* Includes customer demographics, campaign interactions, and economic indicators to predict whether a client converts.





## 3.) Analysis Performed

3.1 Data Cleaning & Feature Engineering:

* Checked for missing values and duplicates
  
* Created a binary converted variable from the target (y)
  
* Ensured dataset consistency for analysis
  
3.2 Funnel Analysis: 

* Calculated total users at each stage (visitors → engaged leads → converted customers)
  
* Computed overall conversion rate
  
* Constructed a funnel dataset to track user progression
  
3.3 Drop-off Analysis:

* Calculated drop-off between funnel stages

* Identified where the largest loss of users occurs in the funnel

3.4 Contact Channel Analysis

* Analyzed conversion rates across different contact methods (contact)

* Compared effectiveness of communication channels

3.5 Monthly Performance Analysis

* Examined conversion rates across months (month)

* Identified seasonal trends in campaign success

3.6 Campaign Intensity Analysis

* Grouped data by number of contacts (campaign)

* Calculated conversion rate per contact frequency

* Visualised relationship between campaign intensity and conversion

3.7 Previous Campaign Outcome Analysis

* Analyzed conversion rates by previous outcome (poutcome)

* Assessed how past campaign success influences future conversions

3.8 Customer Segmentation Analysis

* Evaluated conversion rates across job categories (job)

* Identified high- and low-performing customer segments

3.9 Engagement Analysis (Call Duration)

* Compared call duration distributions between converted and non-converted customers

* Identified relationship between call duration and conversion likelihood

3.10 Behavioural Analysis (Duration Binning)

* Grouped call duration into intervals (bins)

* Analyzed how conversion patterns change across engagement levels


## 4.) Tech Stack


| Tool | Purpose |
|------|--------|
| Google Colab | Python development environment used to run notebooks and perform data analysis |
| Python | Core programming language used for data cleaning, manipulation, and analysis |
| Pandas | Data handling and preprocessing (cleaning, grouping, aggregation) |
| NumPy | Numerical computations and array-based operations |
| Matplotlib / Seaborn | Data visualisation in Python for exploratory analysis |
| Power BI | Building interactive dashboards and final business visualisations |
| Jupyter/Colab Notebook | Organising and documenting the analytical workflow |
| GitHub | Version control and project hosting |

*Minor discrepancies between Python and Power BI visual outputs arise from differences in default aggregation behaviour, data type handling, and filtering order within each tool. These variations do not affect the overall analytical conclusions, as both pipelines are derived from the same cleaned dataset and show consistent directional trends*

## 5.) Key Insights
<details>
  <summary> Churn Patterns</summary>
  



  




</details>

<details>
  <summary> Customer Lifetime Trends</summary>

  





</details>

<details>
  <summary> Cohort Retention Analysis</summary>
















  
</details>





## 6.) Dashboard Preview
> Link to the dashboard: https://app.powerbi.com/links/ZYNsIljxdx?ctid=4b1b908c-5582-4377-ba07-a36d65e34934&pbi_source=linkShare




## 7.) Business Recommendations



## 8.) Outcome



## 👤 Author

Viasha Morgan

E-mail: viashamorgan7@gmail.com
