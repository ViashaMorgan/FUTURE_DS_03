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
  <summary> Funnel Performance & Drop-Off Insights</summary>
  

<img width="713" height="509" alt="image" src="https://github.com/user-attachments/assets/9cd0401e-b6c9-4866-a7a3-53cb45b3bad3" />

* Strong acquisition and engagement= users move easily into the funnel
  
* Significant drop-off at final stage= very low conversion to customers
  
* Key issue is bottom-of-funnel= conversion strategy needs optimisation
  
  
<img width="713" height="509" alt="image" src="https://github.com/user-attachments/assets/cd32d00d-7f70-4a41-b819-6813294e36e7" />

* Negligible drop-off between initial stages= users are consistently progressing early in the funnel

* Extremely high drop-off at the conversion stage= most engaged leads fail to convert

* Confirms a severe bottom-of-funnel issue, where the majority of potential customers are lost right before purchase


</details>

<details>
  <summary> Campaign and Channel Effectiveness </summary>

  <img width="622" height="470" alt="image" src="https://github.com/user-attachments/assets/ad82d5a6-1e67-409f-bc58-c6e3ee0d5416" />

* Cellular contact significantly outperforms telephone, with a much higher conversion rate
  
* Indicates marketing should prioritise cellular channels and reassess or optimise telephone outreach



<img width="768" height="470" alt="image" src="https://github.com/user-attachments/assets/25efd111-f2cc-4307-86bc-2cc37e1fdf20" />

* Seasonal demand plays a role, as months like March, September–October, and December often align with budget cycles and increased spending
  
* Customer intent is lower mid-year (May–August), where users engage but delay making final decisions
  
* Marketing efforts, promotions, and external factors like holidays are stronger in peak months, driving higher conversions


<img width="855" height="470" alt="image" src="https://github.com/user-attachments/assets/c6ec2a1b-0ca4-4486-ad7f-4af1e83b78e8" />

* Conversion rate declines as the number of contacts increases, showing diminishing returns from repeated outreach

* After a certain point (around 15–20+ contacts), conversion drops to near zero, indicating over-contacting is ineffective

* Suggests an optimal contact range exists, and excessive follow-ups may reduce effectiveness or annoy potential customers

</details>

<details>
  <summary> Customer & Conversion Drivers</summary>

<img width="613" height="470" alt="image" src="https://github.com/user-attachments/assets/ed13c46b-5f7a-4234-ac78-d20414dd10f1" />

* Customers with a previous successful campaign have by far the highest conversion rate, showing strong repeat responsiveness

* Indicates that historical success is a strong predictor of future conversion, making it a key targeting factor
  

<img width="921" height="547" alt="image" src="https://github.com/user-attachments/assets/a2595963-a0f0-4953-bbf2-a98a8db5125d" />

* Students and retirees tend to have more time, lower switching barriers, and may be more responsive to offers or financial products

* Mid-career roles (admin, management, technician) have stable income but are more selective and less impulsive in decision-making

* Blue-collar and service workers may face affordability constraints, lower accessibility, or less alignment with the product being marketed
  
</details>


<details>
  <summary> Customer Engagement & Behaviour</summary>

<img width="781" height="470" alt="image" src="https://github.com/user-attachments/assets/9b21289a-9dff-474a-a3ed-880909bc343e" />

* Converted customers have significantly longer call durations, indicating that deeper conversations increase likelihood of success

* Short calls are mostly associated with non-conversions, suggesting low engagement or early rejection

* Implies that call quality and engagement time are key drivers of conversion, not just contact frequency



  
</details>







## 6.) Dashboard Preview
> Link to the dashboard: https://app.powerbi.com/links/ZYNsIljxdx?ctid=4b1b908c-5582-4377-ba07-a36d65e34934&pbi_source=linkShare




## 7.) Business Recommendations



## 8.) Outcome



## 👤 Author

Viasha Morgan

E-mail: viashamorgan7@gmail.com
