---
pagename: Performance Optimizer user guide
categoryName:  Data & reporting
subCategoryName: ''
indicator: both
subtitle: 'The Performance Optimizer is an analytics product within the Conversational Cloud platform'
level3: ''
permalink: data-reporting-analytics-performance-optimizer-user-guide.html
isTutorial: false
isNew: false
date: '2019-03-27T11:28:04.000+00:00'

---
## Introduction

The Performance Optimizer is an analytics product within the Conversational Cloud platform that converges numerous strategic metrics for different Lines of Business into the LIVEPERSON 4E Framework™ to drive probability and business growth.  The Performance Optimizer is LivePerson’s first analytical product geared towards C-Suite executives, Lines of Business and organizational decision makers. 

The Performance Optimizer contextualizes data through anonymized brand comparisons, anonymized industry benchmarks, segmentations, and KPI targets. Narrative-driven dashboards and data contextualization allow managers to diagnose performance opportunities in a faster, more intelligent way. Successes and failures can be generalized or mapped to specific actions, and LivePerson expertise can be presented directly in analytics views.  
The Performance Optimizer has a simple graphic interface which eliminates the need for high cognitive skills such as complex information processing, advanced data analysis, or mathematical skills. This provides users with accurate results, but with actionable information and recipes for success.

Performance Optimizer Allows Brands To: 
* Map and correlate ~500 operational metrics with a set of essential KPIs that align to the 4E framework. Leverage AI to automatically assess conversational performance, diagnose and recommend optimization plans.
* Benchmark their performance relative to their industry
* Spare the need for data wrangling and prioritization, as well as reducing the cognitive load of performing analysis on the data. 

![](img/PO-whatsnew.gif)

## The 4E Framework™
The Performance Optimizer is built upon the LivePerson 4E Framework™.  This analytic approach serves as the foundation for classifying metrics into specific categories that complement each other and guarantee success.  These categories are built around 2 core behavioral truths:
* Brands want to resolve consumer intents using minimal labor
* Consumers will maintain a positive perception of the brand as long as their intents are resolved with minimal friction

LIVEPERSON 4E framework™ correlates these desirable outcomes to conversational metrics. These metrics accurately measure how the conversational operations perform in 4 critical areas organized in a logical sequence: Efficiency, Effectiveness, Effort and Emotion. 

## How to access Performance Optimizer
* Log in to Performance Optimizer requires feature access by request (contact your account manager)
* Only Admin Profiles or pre-configured user profiles may log in. To customize profile authorization, contact your account manager.

Once your account is enabled, you can begin by logging in [here]([https://va.performance.liveperson.net/login)
**HINT:** You can also log in directly via the Quick Launch menu from Conversational Cloud.

### Login Page
![](img/performance-optimizer2.png)

1. Enter your Account Number and click Sign in. The Conversational Cloud Login Screen is displayed.
2. Enter your Username and Password 
3. To access via Quick Launch select the icon located at the bottom of the left toolbar (6 dots).
4. Select the Performance Optimizer icon located within Quick Launch. 

## Getting Started in Performance Optimizer
### Performance Optimizer Dashboard 

After login, the Dashboard is displayed.  

![](img/performance-optimizer4.png)

## Configuration 

To fully experience the advantages of the Performance Optimizer, LOBs must be configured through selection of skills and groups in the Configuration tab of the Performance Optimizer. If LOBs are not configured, the Performance Portal will display all skills and groups as a singular LOB.  There are no limitations as to how many LOBs are created. 

Select the Configuration tab on the upper right corner. 

![](img/performance-optimizer5.png)

## Creating a Line of Business 
1. To create new LOBs, select the edit icon within the “Default LOB (All Data)” box or the “Add a new LOB” button at the bottom left of the Configuration screen.

![](img/performance-optimizer6.png)

2. You will enter the LOB Name 
- Click Skills. A drop-down menu of ALL current Skills for the Account ID is displayed. Select all Skills that should be included within the LOB. 
- Click Groups. A drop-down menu of ALL current Groups for the Account ID is displayed. Select all Groups that should be included within the LOB.
- Select an option to define which metrics should be displayed by industry benchmark or defined number target, or your desired SLA for each metric.

![](img/performance-optimizer7.png)

3. Select the metric that should be measured against the industry benchmark or a brand specific target  value.  By default, the benchmark setting will be configured for all metrics. 

{: .notice}
Default trend values are set at the 75th percentile benchmark within the industry vertical. 

![](img/performance-optimizer8.png)

4. Selecting “Create LOB” displays the newly created LOB within the Configuration Dashboard. 

![](img/performance-optimizer9.png)

5. Click back to “Dashboard” to view your Performance Optimizer settings with your newly created LOBs. 

## Filtering Your Performance Optimizer View 
The Performance Optimizer can be filtered to ensure that only the most relevant data is displayed. These criteria include LOB, Date Range and Granularity ViewWeekly (Monday), Weekly (Sunday) or Monthly. The default filter selections will include all LOBs for the previous 2 weeks, and a monthly view. Note you are able to access 13 months of historical data. The current date or realtime information is not available within the Performance Optimizer. 

To filter the dashboard:
* On the left of the screen, select your LOB(s), date range (by calendar selection or manual entry) and granularity preferences.   
* Click Update. The data will now be displayed according to your preferences.

![](img/performance-optimizer10.png)

## Performance Optimizer Panels 
### Executive Summary Panel

The Executive Summary Panel, the first panel represented in the Performance Optimizer,is a holistic LOB view of the conversational operation which allows users to: 
1. Validate the number of LOBs selected through filter functionality. 
2. View actual performance for the 4E metrics 
3. View trends for each 4E metric based on a) filtered date range and b) previous timeframe as compared to the entered date range.  For example, when  selecting 06/01/2020-6/31/2020 (31 days), the numerical trends and trend line reflect the 31 days prior to 06/01/2020-06/31/2020: 05/01/2020-05/31/2020. 
- Trend arrows - display an upward or downward arrow reflecting the date range entered. For example, the arrow reflects the date range of 06/01/2020 as in the example above.
- The first numerical value, in blue, provides a brand’s actual performance for the date range entered.  As an example, the graphic below shows the brand’s CCPLH (closed conversations per login hour) at 10.83.  
- The second value in parenthesis displays the deviation from the 1st date range (06/01/2020-06/31/2020) from the previous period (05/01/2020-05/31/2020). 
- The trend line displays the performance based on the entered filter date range and the previous period. 


![](img/performance-optimizer11.png)

### Volume Panel 
The volume panel allows the user to view closed conversations (agent, consumer and auto close) and agent login hours over the date range selected by the user in the filter criteria. 

![](img/performance-optimizer12.png)

### Channels 
Based upon the date range entered, the Channel panel provides insight into closed conversation volume (agent, consumer and auto close) by all possible entry points. 
The bar chart will display the distribution across entry panels.  
The line chart displays your entry point volume over time by each possible entry point. 

![](img/performance-optimizer13.png)

### Opportunities Panel 
The Opportunities panel is a pareto style graph that ranks your primary and secondary 4E metrics based on the deviation from industry benchmarks or target value, determined by metric configuration (benchmark or numerical target). The metrics are then ranked based on which metric has the greatest deviation. This allows the user to focus on the most impactful 4E metric that will improve performance. The user is also able to click on each individual bar and automatically navigate to that metric in the 4E detail section at the bottom of the dashboard. 

![](img/performance-optimizer14.png)

### Controlled Delivery Panel 
In this panel, LOBs are represented by a blue dot on the double axis chart that compares the overall 4E scores for efficiency, performing in the best manner with least waste of resources and effectiveness, the ability to achieve the intended result of resolving the consumer intent. Overall 4E scores are determined by a weighted score of all primary and secondary metrics within the 4E categories for efficiency and effectiveness. Users can quickly assess which LOBs to focus on based on the location of the LOB within the graph. For example, LOBs located in the top right corner of the graph are highly efficient and effective. Conversely, LOBs that are in the bottom left are highly inefficient and ineffective and are recommended to be of priority for the business. 

Only LOBs selected within the filter criteria will be displayed. The user may hover over each blue dot to view the name of the LOB and the overall metric score. Clicking on the dot will automatically navigate to the 4E Summary detail panel in a subsequent panel. 

![](img/performance-optimizer15.png)

### Account Config Panel
The Account Config panel displays specific configuration settings that have a potential to drive a brand’s 4E performance. 
* Auto Close Time 
* Inactive Time 
* Smart Capacity Min 
* Smart Capacity Max 

![](img/performance-optimizer16.png)

### LOB Detail Panel 
The LOB Detail panel will display all 4E metrics, primary and secondary, starting with efficiency, effectiveness, effort, and emotion. Only LOB filter selections will be displayed. The user has the ability to dynamically view data based on: benchmark, target, and trend through the toggle selections on the upper right hand corner of the panel. The default view is a benchmark. Actual, trend and deviation values are displayed for each metric based on the filtered date range entered by the user.    

![](img/performance-optimizer17.png)

### 4E Summary Panel 
Using the overall 4E score, the 4E Summary panel enables  users to a calculated overall score by each 4E category. Each 4E score incorporates each primary and secondary 4E metric and weights those metrics based on level of impact.  The score is then calculated to provide a singular score to represent the 4E category.  As seen in the graphic below shows the brand’s efficiency score 55% and the Effectiveness at 17%.  
Industry benchmarks are displayed in 25% percentile increments and are color-coded: Red indicates the bottom 25th percentile, and green indicates the 75th percentile. The user is able to compare their overall 4E scores against the industry benchmark.  As an example, the brand’s efficiency score of 55% is within the 50-75th percentile of their industry.

![](img/performance-optimizer18a.png)

### 4E Detail Panel 
The 4E Detail panel provides a wealth of information for the user to compare each 4E metric, primary and secondary, against industry benchmarks. The user will see their actual 4E performance metric, how their brand has trended compared to the benchmark, as well as the variance of their performance - the gap between what was expected and what happened -against the benchmark. In addition, the user will also see a detailed trend line of the metric performance, as well as a min, max and mean value for their performance. Note: Only LOB filter selections will be displayed.
The Diagnostics section provides a detailed narrative of the performance of the LOBs. The Performance Optimizer takes into account all of the 4E metrics (primary and secondary) of the actual performance It contextualizes the 4E data and the Account Configuration settings (as displayed within the Account Config panel) to provide a customized recommendation for the brand to improve performance based on the LOB and date range selected. 

![](img/performance-optimizer19a.png)

