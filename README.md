## Final Portfolio Project

Tableau Slide Deck 1: https://public.tableau.com/profile/shadia.duery#!/vizhome/Final-Project_twbx_16159324170940/Story1?publish=yes

Tableau Slide Deck 2: https://public.tableau.com/profile/shadia.duery#!/vizhome/Camping_16160189818690/Story?publish=yes

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

6. Visually connect Nataliia's findings to our final report (Priya)

7. Organize the repository (Vincent)

8. Finalize project presentation


### Data Sources:
-Recreation.gov: https://ridb.recreation.gov/download
- Dataset was built with three filters:
    - Camping Season (May 1- Sep 30)
    - Reservable online campsites
    - Campsites located in Washington, Oregon and California (West Coast)

### Tools Used:
- Business Intelligence: Tableau
- Python Scripting: Python 3 | Pandas | NumPy | Matplotlib | Seaborn | Pyspark
- AWS Management Console
- Machine Learning: Supervised Machine Learning | Sklearn | Xgboost | SciKit-Learn 

### Project Description:

We analysed a dataset on camping data. Our business question: "what characteristics make a campsite popular". First we defined popularity as measures of demand (#reservations/#campsites available), how far in advance people book their sites, and number of nights people camped on average. We also explored if the demand for types of campsites (tenting, group, remote, and RV&Structured), and the bundle of recreational activities found around the campground. 
First we cleaned the data using Spark, and Jupyter Notebooks. We changed the data types to allow for calculations, and checked for NaN values. We filtered the data in different datasets that would allow us to go deeper into the analysis. We used Pandas DataFrames severatl Python Libraries to performed such tasks. For our exploratory analysis and final visualizations we used Tableau. We used cluster-analysis-unsupervised-machine-learning.

### Project Requirements:

1) Define a business question.

2) Leverage Machine Learning as at least one component of your analysis.

3) You must use: Scikit-Learn and/or other machine learning library.

4) You must use at least two of the below:
Python Pandas, Python Matplotlib, HTML/CSS/Bootstrap, JavaScript Plotly/D3/Leaflet , SQL Database, MongDB Database, Spark, Amazon AWS, Tableau

5) Optional: Host your application on Heroky, Github or tool of your choice

6) Prepare a 10-minute data storytelling preparation that addresses your business question; mention how ML added to or did not add to your analysis

7) Example projects:
- Create a front-end interface that leverages a ML API to "smarten" the algorithm.
- Perform a deep dive of existing data using various ML methods
- Create a visualization that continues to learn where clusters lie based ML (Use D3 or Plotly to change visualization)
- Create an analysis of existing data to make a prediction, classification, or regression.
- Implement your own version of neural network to solve the MNIST problem or a random forest classifier to solve a home valuation problem (must be approved).

