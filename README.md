# Data-Mining-Project

Airbnb San Diego Market Analysis Report
BUDT 758T Data Mining and Predictive Analysis Team 1
May 7th, 2020
Introduction
Executive Summary
Research Questions & Expected Findings
Preliminary questions related to our perspective:

Where is the best place to own an Airbnb house in San Diego?

What kind of homes?

What features may help to become more popular?

Methodology

Data Preparation
Splited the dataset into training set and testing set
Remove dollar sign and change price related character to numeric
Transfer response rate from percentage to decimel
Data cleaning for original variables
Creating derived variables
Predictive Model
Remove variables will not included in the model
Variables included in the model
Change high_booking_rate colums into factor and replace 1/0 to X1_class/X0_class
XGBoost model based on the Kaggle part
Prediction Results
Draw Accuracy, Sensitivity, Specificity VS Cutoff
Exploratory data analysis
Location Selection: By using zipcode as our index, we grouped all Airbnb houses within certain locations and calculated the
proportion of houses that have high booking rate in each location to help us determine whether a location is popular among
Airbnb users, and then we sorted Top 10 locations.
Neighborhood Selection: We divided the top 10 location into 5 popular areas and then we found out the top 10 neighborhood
that has high proportion of having high booking rates in each area.
Features Finding: Calculate the proportion of having high booking rate for Airbnb homes with specific feature appeared.
Result & Findings
Location Selection Results
Balboa Park Area (zip code: 92104, 92102, 92116, 92113, 92114, 92105)
Ocean Beach & UCSD Area (zip code: 92107, 92106, 92110, 92121)
Features Finding Results
Conclusion and Discussion
Project Summary
Limitation
Future research
Reference
Appendeix
“We, the undersigned, certify that the report submitted is our own original work: all authors participated in the work in a substantive
way; all authors have seen and approved the report as submitted; the text, images illustrations, and other items included the manuscript
do not carry infringement/plagiarism issue upon any existing copyright materials.”
Team Member Names of the Signed team members
Contact Member Qiyuan Peng5/9/2020 Airbnb_SanDiego_1.utf8
file:///Users/hudi/Desktop/Data Mining/predict/untitled folder 2/Airbnb_SanDiego_1.html#variables-included-in-the-model 2/32
Team Member Names of the Signed team members
Team member 2 Di Hu
Team member 3 Xin Xu
Team member 4 Qinyu Wei
Team member 5 Munish Khurana
