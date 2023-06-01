# [PowerBI] User Churn Analysis
## INTRODUCTION
**1. Introduction on dataset**
* Churn rate is the percentage of users who have stopped using an app. This could be customers who have lapsed in use, so they are no longer starting sessions, or it could be customers who have uninstalled the app.
* Dataset includes a *dim table* containing information about users of a telecommunications network company, including fields of demographic information and others related to user churn
<br>**2. Data Dictionary**
<br> You could download the dataset [here](https://docs.google.com/spreadsheets/d/1uly9jpDpXIck3yX54TPXAntA1HpMA3Na/edit#gid=1283189571)
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/9734a926-d933-4cd5-ba79-e423572726f0)
<br>**3. Target**
* Dashboard will display churn status and which users are part of churn group
* Provide solutions to fix situation and reduce churn rate
## DESIGN THINKING
Here are the five steps of design thinking:
<br>
<br>**Step1: Empathize**
<br> Put yourself into report-readers' shoes and understand their needs
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/fe4b05f7-297b-4ede-a59c-40c0f9819c1b)
<br>
<br>**Step2: Define**
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/fb7f5b31-f020-42e6-a453-d459b72e751a)
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/56bb36df-316c-4af2-ac7b-3100c4963252)
<br>
<br>**Step3: Ideate**
<br>![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/4b12d4d2-f57d-4243-a3e5-a973f357c1b0)
<br>
<br>**Step4: Protype**
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/e75816f5-a9aa-4cb0-ac1b-900d744f595c)
<br>
<br>**Step: Review**
<br> ![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/5186aadb-cd00-4201-9470-4325f353a774)
<br>
## VISUALIZATION
![image](https://github.com/honganh218/User-Churn-Analysis/assets/133098903/f510e18e-0793-4e1f-89b7-b3da2b95f0df)
## INSIGHTS
**1. Overview**: The current churn rate (~27%) is higher than the average churn rate (21%) in Telecom industry (according to Statista, 2020), leading to revenue loss by churn users is ~19% (1.4M)
<br> => An indicator for the company to take action on churn issue.
<br> **2. Demographic analysis for churn users**: 
<br> - Gender: mostly equal 
<br> => No notable issues - discarded from dashboard
<br> - Age: Old adulthood (36-55) group is the 2nd largest users but has the highest churn rate (~32%), followed by Middle age (36-55) group, then Young adulthood (18-35) group (both around 23%)
<br> => More actions needed for people aged 36-55.
<br> **3. Churn Reasons:**
<br> - Most important trigger for churn users is Competitor (~45%) whether filtering by Agegroup or Station(Location). It causes a 45% loss in revenue as well which is also the biggest proportion in Total revenue loss by churn users
<br>
## RECOMMENDATIONS
**1. Product discount** Offer great deals /free data if:
<br> + *pay by year* (customers who pay by year have a churn rate of ~6%, while paying monthly is 46% -> 8 times less)
<br> + *pay by credit card* (the churn rate of customers paying with credit cards is ~14%, while paying with other forms the churn rate is more than double, 35%)
<br> => maybe customers prefer paying by credit card because it can be paid later or in installments
<br> **2. Customer Service** Improve the quality of customer care
<br> + Organize training to improve professional skills
<br> + Be more careful in recruiting to improve the quality of personnel from the very beginning
<br> + Do more analytics on Customer Service Department for more details
<br> **3. Competior analysis**
<br> The most important trigger for churn users are "Competitors"
<br> => Do competitor analysis thoroughly for further brainstorming ideas
 


 


 

 



