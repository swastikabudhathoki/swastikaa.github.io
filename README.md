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
  Age is a numeric variable indicating the age of the individual. It serves as a continuous measure and can provide valuable insights into age-related trends and behaviors. Job type encompasses a variety of occupations, ranging from administrative roles to entrepreneurship and manual labor. This categorical variable sheds light on the employment status and professional diversity within the dataset. Marital status reflects the relationship status of individuals, categorizing them as either married, single, or divorced. This attribute offers insights into family structures and potentially influences financial decision-making processes. Education level categorizes individuals based on their educational attainment, distinguishing between tertiary, primary, and secondary education. Education often correlates with income levels and socioeconomic status, impacting financial behaviors and outcomes. Default, housing loan, and personal loan statuses indicate whether individuals have defaulted on credit payments or have housing and personal loans, respectively. These categorical variables are crucial indicators of financial health and risk assessment. </p>
  
<p>
  Also, the dataset contains additional attributes related to communication and timing aspects of contacts made during a marketing campaign or similar outreach efforts. These attributes include contact communication type, last contact month of the year, last contact day of the week, and the duration of the last contact in seconds.
<br>
<h4>EXPLORATORY DATA ANALYSIS</h4>

  <img width="757" alt="Job distribution" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/c58c4dfb-ec89-4609-86ef-44c1a44fb58d">
<img width="626" alt="Deposit and Job" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/feedac15-494f-4503-a416-dd333a2b4002">

<img width="525" alt="Contact" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/2f595147-aefd-4c8e-9642-c1b8ac8a4005">

<img width="441" alt="Default " src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/92401c83-7ee1-446f-9598-9dbff64eb39c">
<img width="536" alt="Default and Depost" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/460f7940-d925-464d-bc94-e7c5da482131">

<img width="478" alt="Marital Status" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/9c5135ec-e9ed-47b0-8694-f9eedbb01f63">
<img width="536" alt="Deposit and Marital Status" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/ed4a6fcd-0820-4d44-9335-e13faae643ba">

<img width="486" alt="Education" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/8c88f2d2-d530-410d-baec-8640038c118d">
<img width="535" alt="Education and Deposit" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/1885e266-1a45-4724-b94f-a60650fbc181">


<br>
<br>
<img width="311" alt="Screenshot 2024-03-07 at 6 13 21 PM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/89d6f198-67d0-44f3-a9ad-93baf9df1dc3">
<img width="268" alt="Screenshot 2024-03-07 at 6 13 32 PM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/ed417aaa-24ac-4b1a-9b97-78762c973e12">
Housing Loan/Personal Loan
<img width="538" alt="Housing and Deposit" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/e9ba80ed-2a72-4ac5-9753-31404cb229fd">
<img width="540" alt="Loan and Deposit" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/fbb2d5b1-baa5-4fd9-8925-e4214ea33f09">

<br>


<br>
<br>
<img width="525" alt="Screenshot 2024-03-08 at 8 53 11 AM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/1544f5f0-2826-4c7f-b577-76d51bc0a358">
(Contact)
<br>


  Other Parameters
 <br>
  Contact communication type categorizes the mode of communication used during the contact, distinguishing between cellular, telephone, and unknown methods. This categorical variable provides insights into the preferred channels of communication and may influence the effectiveness of outreach strategies.The last contact month of the year and day of the week capture the timing of the last contact made with individuals. These categorical variables offer information regarding seasonal trends, campaign scheduling, and day-of-week effects on contact outcomes. The duration of the last contact, measured in seconds, is a numeric variable that represents the length of the interaction between the contact initiator and the individual contacted. It's worth noting that this attribute significantly impacts the outcome target, where a duration of 0 typically results in a negative outcome (e.g., 'no' response). However, its predictive value may be limited due to the inherent nature of the data collection process, where the duration is only known after the call has ended.
  
<h5> BIVARIATE ANALYSIS </h4>
<img width="622" alt="Screenshot 2024-03-07 at 5 38 27 PM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/992a8f28-31bd-48cd-be43-9cba622dee96">
Sum of balance and job

