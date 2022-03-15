**Business Fundamentals Project Write-Up**

Detecting Suicidal Adolescents on Instagram


**Abstract**

The goal of this project was to pitch Instagram a data science solution to a societal problem on adolescent suicide attempts in the United States. Using social media platforms has become a part of adolescent life. Given a large proportion of adolescent users on Instagram, Instagram can help to detect teenagers at high risk for suicide and deliver proper mental health resources (e.g., crisis hotline or stress relief strategies) in real-time. For the goal of suicidal teenager detection, the data science solution proposed was to perform natural language processing on text content shared by teenager users on Instagram. Those results from Natural Language Processing (NLP) would need to classify into suicidal warning sign categories (i.e., talk patterns, behaviors, and moods). In order to dive into the insights and characteristics of suicidal behaviors in U.S. adolescence, I used the Youth Risk Behavior Surveillance System Prevalence data from the Centers for Disease Control and Prevention. After exploring demographic information and suicide prevalence in adolescence, several notable differences in suicidal behaviors were found. Those preliminary insights found were visualized with Tableau.


**Design**

**Opportunity**

Suicide is one of the important societal public health problems. Among adolescents, suicide is the second leading cause of death in the United States. Accordingly, suicide death in adolescents has been increased over the last decade. However, it is difficult and complex to detect and assess suicidal warning signs among teenagers in real-time. Social media has become a huge part of adolescent life. Teenagers use social media for more than two hours on average per day. Among different types of social media platforms, Instagram is the most popular among adolescents. 78% of teenagers are either Instagram account holders or currently active users. Adolescents share different types of personal life on social media. Especially, 34% of teenagers share their emotions and feeling on social media. Given the conjuncture in adolescent suicide problem and a large number of teenager users on Instagram, it can help to detect suicidal warning signs by analyzing posts shared by teenager users. 

**Impact**

The desired impact of this project is to detect suicidal adolescents and provide appropriate mental health resources in real-time. Further desired impacts are to decrease suicide rates in adolescence and to have a healthier influence of social media on youth (i.e., mental health education).

**Data science solution path**

The proposed data solution path is to perform natural language processing (NLP) on Instagram text contents shared by adolescent users. The results from the NLP can be classified into the categories of suicidal warning signs (i.e., talk pattern, suicide-related mood, and suicidal behaviors) by a classification model. These processes would further help which resources to be provided in a certain group of teenagers at suicide risk (e.g., crisis hotline information for highly suicidal groups versus coping skills or stress relief resources for a non-suicidal but highly depressed group).

**Impact hypothesis**

The natural language processing and classification models held in the solution path may detect adolescent Instagram users at high suicide risks. 

**Measure of success**

In order to validate the project, the team should collect text-based posts shared by adolescent users. If the NLP and classification models can correctly classify a good amount of posts into suicidal versus non-suicidal groups by using a suicidal warning sign type protocol. If detected users interact with mental health resources provided (e.g., staring or clicking resources), then the project will be successful. 

**Assumptions**

The proposed solution path assumes that shared contents on emotions and feelings are not fake and honestly stated. Even though 38% of teenagers share emotions and feelings on social media, suicide-related emotions and thoughts can be too private to post publically on social media. 

**Data**

For the preliminary exploratory data analysis, I used the Youth Risk Behavior Surveillance System (YRBSS) Prevalence 2017 data from the Centers for Disease Control and Prevention. As of now, this data is the most current version of the YRBSS prevalence and can be found [here](https://chronicdata.cdc.gov/Youth-Risk-Behaviors/DASH-Youth-Risk-Behavior-Surveillance-System-YRBSS/q6p7-56au). The raw data consists of 5633 rows (including the heading) and 40 columns. Each row represents a prevalence of a type of suicidal behavior with a certain demographical condition (i.e., gender, sexual orientation, race, grade, and geolocation). 

**Algorithms**

I cleaned the dataset, sorting geographical information (i.e., state and county names), and aggregating the prevalence data in Microsoft Excel Spreadsheet. I performed a preliminary exploratory analysis in Excel and held the visualization in Tableau. 


**Tools**

1. Microsoft Excel to clean, aggregate, explore, and analyze the data

2. Tableau to visualize the preliminary findings


**Communication**

My pitch for this data science solution is presented in a PowerPoint presentation, which includes the visualizations created in Tableau.
