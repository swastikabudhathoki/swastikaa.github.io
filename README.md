# Pair Project
## **Bank Marketing Campaign: Data Driven Analysis**
### Prepared by:Swastika Budhathoki (207025) & Swornika Chhetri (207028)
<br>
Marketing selling campaigns constitute a typical strategy to enhance business (Moro,2014). The dataset unveil the relationship between direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit or not.
<br>
<h4>Data Distribution</h4>
The dataset provided is related to demographic and financial attributes of individuals, including their age, job type, marital status, education level, default status, housing loan status, and personal loan status of Portuguese. Each attribute represents categorical data, providing insight into various aspects of an individual's profile.
  
  <p>Age is a numeric variable indicating the age of the individual. It serves as a continuous measure and can provide valuable insights into age-related trends and behaviors. Job type encompasses a variety of occupations, ranging from administrative roles to entrepreneurship and manual labor. This categorical variable sheds light on the employment status and professional diversity within the dataset. Marital status reflects the relationship status of individuals, categorizing them as either married, single, or divorced. This attribute offers insights into family structures and potentially influences financial decision-making processes.</p>
  <p>Education level categorizes individuals based on their educational attainment, distinguishing between tertiary, primary, and secondary education. Education often correlates with income levels and socioeconomic status, impacting financial behaviors and outcomes. Default, housing loan, and personal loan statuses indicate whether individuals have defaulted on credit payments or have housing and personal loans, respectively. These categorical variables are crucial indicators of financial health and risk assessment. </p>
<p><b> Goal of the study: 
  <br><b>a. To find out which factor influence the long-term deposit subscription in Portuguese Banking Institution.</b>
<br>b.To find out the banking strategies based on the outcome.</b></p>
<h4>EXPLORATORY DATA ANALYSIS</h4>
<br> JOB DISTRIBUTION
<br><img width="549" alt="Job" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/d99fdc62-1aca-4ab6-a346-b08657bb2975">
<br><img width="1277" alt="Job and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/aefc0bc4-24b7-4d5d-8dd9-d0822a1a9a3e">
<br>
<p>The job distribution among clients reflects a diverse job fields, showcasing Management, Blue-collar, Technician, Admin, Services, and Others as the primary categories. Notably, Blue-collar clients demonstrate a relatively higher subscription rate for long-term deposits at 11.07%, contrasting with the 11.33% subscription rate among Management clients, despite their larger representation at 22.99%.</p>
<p>
<br> MARITAL STATUS
<br><img width="587" alt="Marital Status" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/0351289b-1d1d-4f2d-a46d-c245f2ee0bdf">
<br><img width="1263" alt="Marital Status and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/cb85b6b2-c4ce-4497-a83b-f181d74f1619">
<p>Marital status plays a pivotal role, with married clients constituting the majority at 56.90%, followed by Singles at 31.52% and Divorced individuals at 11.58%. Among these groups, married clients showcase the highest subscription rate for long-term deposits at 32.22%, followed by Singles at 14.39% and Divorced individuals at 6.01%.</p>
</p>
<p>
  <br> EDUCATION
<br><img width="518" alt="Education" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/f8e9a967-fd20-4406-b023-398310251b9d">
<br><img width="1278" alt="Education and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/bf71ea79-5bd5-49fc-ac62-11545d2a3ee7">
  <p>Education levels vary considerably, with Secondary education dominating at 49.06%, followed by Tertiary at 33.05%, Primary at 13.44%, and Unknown at 4.45%. Suprisingly, clients with Primary education exhibit a relatively higher subscription rate for long-term deposits at 8.14%, surpassing the 27.11% rate among those with Secondary education.</p>
</p>
<p>
  <br> CONTACT
  <br><img width="553" alt="Contact" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/e4d512bf-5934-4910-b0cc-a62382e6ef7c">
<br><img width="1258" alt="Contact and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/4ab82ac7-6daf-4edb-8cbf-6878c3eba012">
  <p> In terms of communication, Cellular communication emerges as the preferred mode, accounting for 72.05% of usage. Clients communicated through Cellular means exhibit a notably higher subscription rate for long-term deposits, with 32.91% opting for this mode.</p>
</p>
<p>
  <br>HOUSING
 <br> <img width="576" alt="Housing" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/b8a58edc-a360-4c81-a1f3-86a96d424590">
<b></b><img width="1271" alt="Housing and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/eb162e33-8e1a-40bd-bcfa-69981d153d37">
</p>
<p>
  <br>LOAN
<br><img width="490" alt="Loan" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/6dff4975-3ffc-46e8-a9e5-5eae07513bbe">
<br><img width="1293" alt="Loan and Subscription" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/e6d5dc2c-dd3a-4f45-8013-a30cee7f5b26">
  <p>Regarding housing and loans, 47.31% of clients have a housing loan, with 29.98% subscribing to long-term deposits. Conversely, 52.69% do not have a housing loan, yet 22.64% still subscribe to long-term deposits. Similarly, 13.08% of clients have a personal loan, with 8.74% subscribing to long-term deposits, while 86.92% do not, yet 43.87% subscribe to long-term deposits.</p>
</p>
<br>
<h4>CONCLUSION</h4>
<img width="1184" alt="Screenshot 2024-03-08 at 12 38 48 PM" src="https://github.com/swastikabudhathoki/swastikaa.github.io/assets/123391402/b28cbcfa-91a6-4de1-b0a2-0ae9b51b69aa">
<p>To boost long-term subscription rates and enhance customer engagement, banks can implement strategic initiatives. Firstly, they should focus on understanding their customers better by segmenting them based on their different traits and behaviors. This helps in creating personalized marketing messages and services that match the needs of various customer groups.</p>

<p>Secondly, with more people using mobile phones, especially for communication, banks need to prioritize digital platforms, like mobile apps and messaging services, to connect with customers easily.</p>

<p>Investing in educational programs about finances is also crucial. By helping customers understand the importance of long-term financial planning, banks can empower them to make smarter decisions about their money. Tailoring these programs to fit the education levels of their customers, like focusing on secondary education, can make them more effective.</p>

<p> Integrating deposit products with loans is another strategy. By offering attractive deals and benefits for customers who use both services, banks can encourage long-term commitment and loyalty.</p>

<p>Lastly, banks should continually analyze feedback from customers and keep an eye on market trends. This helps them stay responsive to changing needs and preferences, ensuring their strategies remain effective over time.</p>

<p>By embracing these strategies, banks can improve their long-term subscription rates, strengthen customer relationships, and thrive in the competitive financial industry.</p>

