## TechStudio-Performance-Report

This project uses performance data from Tech Studio Academy, covering metrics such as enrollment, course satisfaction, completion rates, revenue, and geographic distribution.
The dataset was analyzed and visualized using Power BI, enabling interactive exploration of trends across years, courses, cities, and delivery modes.


<img width="1660" height="918" alt="Screenshot 2025-11-15 084145" src="https://github.com/user-attachments/assets/712533ff-4f47-4469-b5a7-d8f5b31ac19a" />


## Introduction
   
This report provides an overview of student engagement and performance at Tech Studio Academy between 2024 and 2025.
The aim is to understand overall enrolment trends, course success rates, revenue outcomes, and student satisfaction to help guide strategic decision-making.


## Objectives

The analysis seeks to:
* Examine patterns in student enrolment.
* Identify high-performing courses and cities.
* Assess satisfaction, completion, and employment outcomes.
*	Evaluate revenue performance after discounts.
*	Provide insights to support future planning and course optimisation.


## Dataset Description

The dataset captures detailed information about student enrolment and performance at Tech Studio Academy for the year 2024 and 2025. 
Each record represents an individual student and includes key attributes that describe their learning journey from the moment they enrolled to their post-training outcomes.

The dataset contains variables such as:
*	Enrolment Year – identifies whether the student joined in 2024 or 2025, allowing year-to-year comparison.
*	Course – specifies the program the student enrolled in (e.g., Data Analysis, Cyber Security, Product Design, Full Stack Web Development), enabling assessment of course popularity and performance.
*	City – indicates where the student studied (Abuja, Lagos, Port Harcourt, Ibadan), which helps evaluate geographic demand and city-level performance.
*	Mode of Learning – shows whether the student studied online, onsite, or hybrid, offering insights into learning preferences.
*	Satisfaction Score – a numerical rating (typically 1–10) that reflects the student’s experience and perception of the course quality.
*	Completion Status – indicates whether the student successfully completed the program, withdrew, or did not finish, supporting analysis of learning outcomes.
*	Employment Outcome – reveals whether the student secured a job after training, helping assess the academy’s career impact.
*	Revenue – the amount paid before any discount.
*	Discount – the amount deducted from the course fee.
*	Net Revenue (derived) – calculated as Revenue minus Discount, used to evaluate financial performance by course and city.
  
Together, these attributes provide a comprehensive view of how different courses performed, how engaged students were,
how effectively they completed their programs, and how training translated into employment outcomes. The dataset also supports financial analysis through revenue and discount tracking.


## Data Preparation

Before analysis, the dataset was cleaned and transformed in Power BI to ensure accuracy, consistency, and meaningful insights. 
The preparation process involved several key steps:

* Checking for Missing or Incorrect Values

The dataset was reviewed to identify empty fields, inconsistent entries, or errors in columns such as satisfaction score, completion status, and revenue. 
Any missing values were handled either by correcting them (where possible) or leaving them out of calculations to avoid misleading results.


*	Creating Derived Metrics

New calculated columns were added to support deeper analysis. For example:
*	Net Revenue = Revenue – Discount
*	Completion Flag (1 for completed, 0 for not completed)
* Employment Flag (1 for employed, 0 for not employed)
These metrics made it easier to measure overall performance, success rates, and financial outcomes.


*	Setting up Data Types

Each column was assigned the correct data type numbers as decimals or whole numbers, dates as date fields, and categories as text to ensure accurate calculations and visualization.


## Analysis and Findings

  
Key findings include:
Strong year-on-year enrolment growth.

* Year-on-Year Enrollment Trends: 2024 saw higher enrollment than 2025, with a noticeable drop from ~90 to ~60 students.
While the overall total enrollment is 150, the downward trend in 2025 suggests a need to investigate potential causes such as market saturation, competition, or changes in course offerings.

* Course Popularity: Product Design and Cyber Security are the most popular courses, attracting ~50 and ~40 enrollments respectively.
Data Analysis and Full Stack Web Development trail behind, with ~30 and ~20 enrollments.
This indicates a strong demand for design and security skills, possibly reflecting industry trends or student career preferences.

* City-Level Enrollment Distribution
Cities like Port Harcourt, Lagos, and Abuja dominate in enrollment numbers, as shown by larger bubbles on the map.
These urban centers likely benefit from better infrastructure, higher population density, and stronger tech ecosystems.

* Satisfaction and Completion Outcomes
The overall completion rate is 81.33%, which is quite strong.
However, average satisfaction is only 7.18 out of 10, and varies significantly by course:
Full Stack Web Development: ~5
Cyber Security: ~4
Data Analysis: ~3
Product Design: ~2
This suggests that while students are completing courses, their experience especially in Product Design is not meeting expectations.

* Revenue Contribution by Course
Cyber Security leads in revenue (~10M), followed by Full Stack Web Development (~9M).
Product Design and Data Analysis contribute ~7M and ~6M respectively.
Interestingly, Product Design has high enrollment but lower satisfaction and revenue,
while Full Stack Web Development has fewer students but higher revenue and satisfaction indicating better monetization and delivery quality.


## Insights and Interpretation

* Growth and Demand Patterns
While overall enrollment reached 150, the year-over-year data reveals a decline from 2024 to 2025.
This suggests that although the academy has achieved scale, growth may be plateauing or facing external challenges.
The strong demand for specific programs especially Product Design and Cyber Security indicate alignment with market needs and student interests.
These courses consistently attract the highest number of enrollments, making them strategic pillars for future expansion.

* Satisfaction, Completion, and Employment Linkages
The completion rate of 81.33% is impressive, but satisfaction scores vary widely across courses, with some falling below average.
Courses with higher satisfaction scores (e.g., Full Stack Web Development) tend to correlate with better completion outcomes,
suggesting that student experience directly influences persistence and success.
Although employment data isn't shown directly, the implication is that post-training employment may be stronger in courses with higher satisfaction and completion,
reinforcing the need to improve delivery quality in lower-rated programs.

* Geographic and Delivery Mode Trends
Enrollment is concentrated in major cities like Lagos, Abuja, and Port Harcourt, which likely reflects population density, tech industry presence, and access to infrastructure.
The split between delivery modes (58% vs 42%) shows a healthy balance between in-person and remote learning.
This pattern can guide decisions on where to invest in physical campuses versus digital platforms.
Understanding these geographic and modality preferences can help the academy optimize resource allocation, such as staffing, marketing, and infrastructure development.

* Strategic Implications
Invest in high-performing courses with strong demand and satisfaction to maximize impact and revenue.
Revamp lower-rated programs by improving curriculum, teaching quality, or support services.
Target high-enrollment cities for deeper market penetration and community engagement.


## Recommendations

Based on the analysis:

* Expand high-demand courses in top-performing cities.
Tech Studio Academy should consider increasing its Product Design and Cyber Security program capacity such as adding more class sessions, offering advanced modules, or allocating more trainers in Abuja and Lagos, where demand is proven to be strongest. These cities present the highest potential for growth and the best return on investment. 
For Port Harcourt, the academy could maintain or slightly scale its offerings, while Ibadan might benefit from targeted marketing or awareness campaigns to boost enrolment.

* Improve support in courses with lower satisfaction or completion rates.
 Why: Courses like Product Design and Data Analysis have lower satisfaction scores and may risk higher dropout rates.
Action: Conduct student feedback sessions, revise curriculum content, provide additional mentoring, and improve instructor training.
Impact: Enhancing the learning experience will boost satisfaction, increase completion rates, and improve the academy’s reputation.

* Optimize pricing or discount strategies for courses with low net revenue.
Why: Despite decent enrollment, some courses (e.g., Data Analysis) generate less revenue, possibly due to pricing misalignment or low perceived value.
Action: Reassess pricing models, introduce tiered packages, offer limited-time discounts, or bundle courses to increase value perception.
Impact: This can improve profitability without compromising accessibility, especially for courses with growth potential.

* Strengthen career-support initiatives to improve employment outcomes.
Why: Completion alone isn’t enough students expect tangible career outcomes post-training.
Action: Expand job placement services, build partnerships with tech companies, offer resume workshops, mock interviews, and alumni networking.
Impact: Stronger career outcomes will enhance student satisfaction, attract new enrollments, and reinforce the academy’s value proposition.


## Conclusion

Between 2024 and 2025, Tech Studio Academy demonstrated solid overall performance, marked by healthy enrollment figures, strong completion rates, and meaningful revenue generation.
The data reveals distinct patterns across courses, cities, and delivery modes that offer actionable opportunities for strategic growth.
High-demand programs and top-performing cities present clear avenues for expansion, while disparities in satisfaction and revenue across courses highlight areas for targeted improvement.
The strong link between student satisfaction, completion rates, and potential employment outcomes underscores the importance of enhancing the learning experience and career support services.
By leveraging these insights, the academy is well-positioned to scale its most successful offerings, optimize resource allocation, and elevate its impact on learners and the broader tech ecosystem.














