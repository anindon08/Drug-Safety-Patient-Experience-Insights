# Drug-Safety-Patient-Experience-Insights
This project analyzes patient reviews to track side effects and boost pharmacovigilance (PV), satisfaction, and complaint management using Advanced Excel and NLP.
## Objective:

This project aims to leverage patient reviews of medications to identify trends in side effects, satisfaction levels, and overall sentiment. It will help manage customer complaints, enhance pharmacovigilance (PV) activities, and ensure high levels of patient satisfaction. By using Advanced Excel and NLP techniques, the goal is to extract actionable insights from real-world data, improving drug safety and effectiveness.

## Dataset Overview:

Total Records: Over 248,000 drug reviews

**Key Data Fields:**

**Drug Information:** Generic and brand names

**Condition Specificity:** Medical conditions treated (e.g., UTIs, cystitis)

**Patient Reviews:** Textual data detailing patient experiences

**Side Effects:** Reported by patients in reviews (41 columns)

**Sentiment Data:** Captured via text and ratings

**Substitute Drugs:** Up to 5 alternatives for each medication

## Key Metrics to Quantify:

**Total Number of Complaints and Reviews:**

**Metric:** Total reviews mentioning side effects, negative drug interactions, or substitute drug requests.

**Quantified:** Assume 20% of reviews report issues, which would equal approximately 49,600 reviews.

**Sentiment Score Calculation:**

**Metric:** Overall sentiment score from patient reviews, categorizing into positive, neutral, or negative sentiments.

**Quantified:** For instance, if 55% of reviews are positive, 25% neutral, and 20% negative, we can track shifts in sentiment after interventions (e.g., improved drug formulations).

**Most Commonly Reported Side Effects:**

**Metric:** Frequency of specific side effects (out of 41 possible side effects).

**Quantified:** GI issues (25%), headaches (15%), and fatigue (10%) could be the top complaints, representing trends in patient experiences.

**Drug Substitution Success Rate:**

**Metric:** Rate of successful complaint resolution by recommending substitute drugs.

**Quantified:** If substitutes are mentioned in 10% of complaints and resolve 60% of those cases, this yields a success rate of 6% (~2,976 cases).

**Complaint Resolution Impact on Satisfaction:**

**Metric:** How quickly complaints are resolved and the effect on patient satisfaction.

**Quantified:** Reducing resolution time from 10 days to 5 days could increase positive sentiment by 15%, improving satisfaction scores across 20,000+ patients.

## Tools and Functions Used:

**Step 1: Data Cleaning and Preparation**
**Tools: Excel**

**Functions:**

**Data Cleaning:** Use functions like IFERROR, CLEAN, and TRIM to handle missing, incomplete, or inconsistent data.
**VLOOKUP & INDEX-MATCH:** Cross-reference drugs with side effects, substitute drugs, and sentiment ratings to ensure accuracy.

**VBA Automation:** Develop macros to automate data cleaning processes, such as flagging blank columns or irrelevant reviews.

**Step 2: Sentiment Analysis on Patient Reviews**

**Tools: Excel, NLP Tools (e.g., Python)**

**Functions:**

**Text Functions:** Use Excel’s LEFT, MID, and FIND to isolate keywords from reviews that indicate positive or negative sentiments.

**NLP Implementation:** Utilize a basic sentiment analysis algorithm using Python’s TextBlob or VADER to score patient reviews based on sentiment polarity.

**VBA Macros:** Create macros to highlight positive/negative keywords in Excel automatically, aiding non-technical stakeholders.

**Step 3: Data Analysis and Visualization**

**Tools: Excel**

**Functions:**

**Pivot Tables & Charts:** Summarize and visualize the distribution of side effects, substitute drug success rates, and overall complaint trends.

**Dynamic Charts:** Create line graphs or pie charts tracking sentiment changes over time as interventions are implemented (e.g., after addressing common side effects).

**VBA Automation:** Build automated report generation scripts to keep stakeholders updated on patient sentiment and complaint resolution progress.

**Step 4: Customer Management and Complaint Tracking**

**Tools: Excel**

**Functions:**

**Conditional Formatting:** Apply formatting to highlight overdue complaints or cases where substitute drugs were not successful.

**Form Controls:** Use interactive form controls (dropdowns, slicers) to filter complaint data by therapeutic class, drug category, or patient demographic.

**Customer Feedback Analysis:** Use AVERAGEIF and COUNTIF functions to analyze patient feedback scores post-complaint resolution.

**Step 5: Final Reporting and Dashboard Creation**

**Tools: Excel, VBA**

**Functions:**

**Dashboard Design:** Create an interactive, user-friendly dashboard that tracks key metrics like top side effects, common complaints, resolution times, and sentiment shifts.

**VBA for Automation:** Automate report generation and dashboard updates, ensuring real-time insights are provided to the team without manual effort.

## Quantified Impact on Pharmacovigilance:

**Adverse Event Monitoring:**
By identifying frequent side effects in 41 columns of data, this project enables PV teams to monitor drugs for emerging safety concerns, helping to mitigate risks and ensure patient safety.

**Complaint Resolution Efficiency:**
Streamlining the resolution of 20% of complaints reduces customer dissatisfaction, with a target of improving resolution time by 50% (from 10 days to 5 days), enhancing overall patient satisfaction.

**Sentiment Improvement:**
Real-time sentiment analysis reveals patient concerns early, allowing for interventions that could improve positive sentiment by 15%, affecting ~20,000 reviews.

**Regulatory Compliance:**
With accurate and comprehensive tracking of complaints and side effects, this project ensures the company meets regulatory standards for PV reporting and drug safety monitoring.

## Conclusion:

This data analysis project demonstrates a strong understanding of managing customer complaints and leveraging patient sentiment data within the Life Sciences sector. By applying Advanced Excel techniques and NLP for sentiment analysis, the project helps enhance pharmacovigilance efforts, improve customer satisfaction, and provide actionable insights into drug safety and effectiveness.

This project will effectively showcase your ability to perform data-driven analysis, manage customer data, and ensure the highest standards in complaint management and pharmacovigilance in the Life Sciences sector.
