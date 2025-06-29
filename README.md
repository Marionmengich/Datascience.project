# Aircraft Safety Risk Analysis
Understanding aircraft safety is crucial for any business looking to enter the aviation industry. This project dives deep into over 88,000 aircraft incidents from the U.S. National Transportation Safety Board (NTSB) dataset to provide data-driven insights and recommendations for acquiring the safest aircraft for both commercial and private use.
#Project Objective
Our primary goal was to guide our company's aircraft acquisition strategy by answering key safety questions:

Which aircraft models demonstrate the highest and lowest risk?

How does injury severity vary across different aircraft types?

What conditions (like weather or build type) significantly increase incident severity?
##  Data Used

- **Source**: U.S. National Transportation Safety Board (NTSB) dataset
- **Rows**: 88,000+ incidents
- **Key columns**: Aircraft Make, Model, Fatalities, Weather, Aircraft Type, etc.
##  Key Steps

1. **Data Cleaning**
   - Handled missing values using `dropna`, `fillna`, and logical imputation
   - Removed irrelevant or incomplete records
2. **Feature Engineering**
   - Created columns like `Year`, `Total Injuries`, and `Fatalities per Incident`
3. **Exploratory Data Analysis (EDA)**
   - Compared aircraft models based on incident count and injury severity
   - Analyzed patterns across weather, location, and build type
4. **Visualization**
   - Created interactive and static visualizations using Tableau and Matplotlib
   - Focused on making findings clear to business stakeholders
#Key Insights
Our analysis revealed several critical safety insights:

Safest Models: The Cessna 172, Piper PA-28, and Beechcraft Bonanza consistently showed lower risk profiles.

High-Risk Models: The Piper PA-46 and Cessna 210 were identified as models with higher incident rates and severity.

Amateur-Built Aircraft: A significant finding was the substantially higher fatality rates associated with amateur-built aircraft.

Clear Weather Incidents: Surprisingly, most incidents occurred in clear weather, suggesting that factors like pilot error or mechanical failure are often key contributors, rather than adverse weather.

# Business Recommendations
Based on our findings, we strongly recommend the following for aircraft acquisition and operations:

Invest in Low-Risk Aircraft: Prioritize models like the Cessna 172, Piper PA-28, and Beechcraft Bonanza for both operational use and pilot training programs.

Avoid High-Fatality Models: Steer clear of models like the Piper PA-46 and Cessna 210, regardless of potential cost benefits, due to their higher safety risks.

Exclude Amateur-Built Planes: Do not consider amateur-built aircraft for business use due to their significantly elevated fatality rates.

Emphasize Training and Inspection: Implement rigorous pilot training programs and regular, thorough aircraft inspections to mitigate risks, especially given the prevalence of clear weather incidents.
## Tools Used

- **Python** (pandas, matplotlib)
- **Jupyter Notebook**
- **Tableau** (for dashboard)
- **GitHub** (for version control and sharing)

Email: cherotichmarion20@gmail.com
