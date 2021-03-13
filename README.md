## Final Portfolio Project

Website: https://shadiaduery.github.io/Portfolio_Project/

# Campground Characteristic Analysis of Campgrounds in CA, OR, and WA

### Collaborators: 
Priya Arunachalam, Nataliia Sokolova, Vincent Durcan, Shadia Duery, and Anna Rischitelli

### Business Question:
We are a team of consultants hired to determine where to distribute financial resources among the campgrounds in Washington, Oregon, and California. Our goal is to identify which, if any, campground characteristics impact a campground's popularity, so we can make decisions about future funding of our most popular campgrounds.

In short,
- What characteristics describe the most popular campgrounds in Washington, Oregon, and California?

### Goals:
0. Data Cleaning
    Discuss the types of activities (ex: winter activities, water activities, climbing-related activities, etc.). Some of these activities are similar and can be grouped. This is important because if a campground has a similar acitivity as another, then you can compare. 

    Data cleaning and making sure activity names match so that we can have confidence that our activity comparisons are correct. Without this, you are losing a dimension that can dirty our cluster analysis later (extra column later that is unnecessary). 

    Data cleaning = creating confidence in our data to make sure we are correctly answering our question with our further analysis, like choosing the correct variables for ML later.

1. Intro graphs and question set up (Anna)
    Present dilemna and the initial look at some trends to describe how we are going to answer our business question. Camping, popularity, etc.
    
    We found out there are different campers - RV vs. tent, certain activities. So we wanted to figure out what characteristics are associated with popular campgrounds. Does that preference show in the types of campgrounds and their popularity?

2. Outside research and trends to create context for this problem (Vincent)
    a. Information about campgrounds
    b. Trends in camping

3. Do site types affect the popularity of a campground? (Shadia)

    a. Determine groups of campsite types
    b. Plot the groups of campsite types (box plots)

    x = 4 different camp types
    y = demand (reservations/campsites)

    ^ Visualize if there is a difference in the median number of days across the four types. If there is not, than the median number of days probably doesn't affect popularity. If the median does differ, then it could impact popularity and it should be added to the ML.

4. Find a feature of our campgrounds (like siteype) to explore that might add to final analysis (Vincent)

5. Clustering to understand the relationship between popularity* and activities (Nataliia). 

    *Popularity is defined by:
        a. Demand (# of reservations/# of campsites)
        b. How far in advance reservations are grouped
        c. Average number nights in reservations
        d. Types of activites
    
    Adding following to cluster:
        e. minimum time from order date to start date
        f. 

6. Visually connect Nataliia's findings to our final report (Priya)

7. Organize the repository (Vincent)

8. Finalize project presentation


Other work:
- Best/worst performing clusters 
- Reservations file - looking over time 
- Powerpoint presentation setup
- 


### Results
- Two features: remoteness and size of campgrounds
- 


### Data Sources:
-UC Irvine Machine Learning Repository: https://archive.ics.uci.edu/ml/index.php
-
-

### Tools Used:
Tableau, Python Scripting (Python 3, Pandas, NumPy, Matplotlib, Unsupervised machine learning (cluster analysis), supervised machine learning (Sklearn, Xgboost, SciKit-Learn).

### Project Description:

Describe your project topic, tools you used. 



