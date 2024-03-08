# Pair Project
## **Bank Marketing Campaign: Data-Driven Analysis**
### <h3>Prepared by:Swastika Budhathoki (207025) & Swornika Chhetri (207028)</h3>
<br>
Marketing selling campaigns constitute a typical strategy to enhance business (Moro,2014). The dataset unveil the relationship between direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit or not.
<br>
<h4>Data Distribution</h4>
The dataset provided is related to demographic and financial attributes of individuals, including their age, job type, marital status, education level, default status, housing loan status, and personal loan status of Portuguese. Each attribute represents categorical data, providing insight into various aspects of an individual's profile.
<br>
<p>
  Age is a numeric variable indicating the age of the individual. It serves as a continuous measure and can provide valuable insights into age-related trends and behaviors. Job type encompasses a variety of occupations, ranging from administrative roles to entrepreneurship and manual labor. This categorical variable sheds light on the employment status and professional diversity within the dataset. Marital status reflects the relationship status of individuals, categorizing them as either married, single, or divorced. This attribute offers insights into family structures and potentially influences financial decision-making processes. 
  
  <p>Education level categorizes individuals based on their educational attainment, distinguishing between tertiary, primary, and secondary education. Education often correlates with income levels and socioeconomic status, impacting financial behaviors and outcomes. Default, housing loan, and personal loan statuses indicate whether individuals have defaulted on credit payments or have housing and personal loans, respectively. These categorical variables are crucial indicators of financial health and risk assessment. </p>
  
<p>
  Also, the dataset contains additional attributes related to communication and timing aspects of contacts made during a marketing campaign or similar outreach efforts. These attributes include contact communication type, last contact month of the year, last contact day of the week, and the duration of the last contact in seconds.
<br>
<h4>EXPLORATORY DATA ANALYSIS</h4>
<img width="549" alt="Job" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/d99fdc62-1aca-4ab6-a346-b08657bb2975">
<img width="1277" alt="Job and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/aefc0bc4-24b7-4d5d-8dd9-d0822a1a9a3e">
<br>

<ol>
  <li><b>Management, Blue-collar, Technician, Admin, Services, and Others are the highest job categories</b></li>
  <li>Blue-collar clients have the highest subscription rate at 11.07%, followed by Management at 11.33%.</li>
</ol>
<img width="587" alt="Marital Status" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/0351289b-1d1d-4f2d-a46d-c245f2ee0bdf">
<img width="1263" alt="Marital Status and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/cb85b6b2-c4ce-4497-a83b-f181d74f1619">
<img width="518" alt="Education" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/f8e9a967-fd20-4406-b023-398310251b9d">
<img width="1278" alt="Education and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/bf71ea79-5bd5-49fc-ac62-11545d2a3ee7">
<img width="553" alt="Contact" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/e4d512bf-5934-4910-b0cc-a62382e6ef7c">
<img width="1258" alt="Contact and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/4ab82ac7-6daf-4edb-8cbf-6878c3eba012">
<img width="576" alt="Housing" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/b8a58edc-a360-4c81-a1f3-86a96d424590">
<img width="1271" alt="Housing and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/eb162e33-8e1a-40bd-bcfa-69981d153d37">
<img width="490" alt="Loan" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/6dff4975-3ffc-46e8-a9e5-5eae07513bbe">
<img width="1293" alt="Loan and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/e6d5dc2c-dd3a-4f45-8013-a30cee7f5b26">
<br>
<br>
  Contact communication type categorizes the mode of communication used during the contact, distinguishing between cellular, telephone, and unknown methods. This categorical variable provides insights into the preferred channels of communication and may influence the effectiveness of outreach strategies.The last contact month of the year and day of the week capture the timing of the last contact made with individuals. These categorical variables offer information regarding seasonal trends, campaign scheduling, and day-of-week effects on contact outcomes. The duration of the last contact, measured in seconds, is a numeric variable that represents the length of the interaction between the contact initiator and the individual contacted. It's worth noting that this attribute significantly impacts the outcome target, where a duration of 0 typically results in a negative outcome (e.g., 'no' response). However, its predictive value may be limited due to the inherent nature of the data collection process, where the duration is only known after the call has ended.
  
<h4>Conclusion</h4>
<img width="622" alt="Screenshot 2024-03-07 at 5 38 27 PM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/992a8f28-31bd-48cd-be43-9cba622dee96">
Sum of balance and job

