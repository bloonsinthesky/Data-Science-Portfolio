# ML and Data Analytics Portfolio

### **UPDATE: Please view my new portfolio website published on GitHub Pages: [Portfolio website](https://bloonsinthesky.github.io/)**

This repository contains a portfolio of my ML and data analytics projects completed for professional, research, and learning purposes. Projects are presented in the form of Jupyter notebooks, R markdown files (published at RPubs), online dashboard apps, written reports, powerpoint slides, and video lectures.

Data files for all projects are available in their respective folders or, in the case of large data files, via a URL within the Jupyter notebooks. Jupyter notebooks are best viewed using the *nbviewer* links provided.

## Contents

+ ### Machine Learning
  + [The Battle of the Neighborhoods](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/The%20Battle%20of%20the%20Neighborhoods): *K*-means __clustering__ was used to cluster all neighborhoods in Helsinki based on a selection of neighborhood features. The "optimal" neighborhood cluster for opening a new café was then chosen using a set of business and mathematical assumptions. Neighborhood census and venue data were collected from *Statistics Finland* and via the *Foursquare* API, and then cleaned using SQL queries and pandas. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/The%20Battle%20of%20the%20Neighborhoods/The%20Battle%20of%20the%20Neighborhoods.ipynb) | [report](https://bloonsinthesky.github.io/pdf/The%20Battle%20of%20Neighborhoods%20-%20Report.pdf) | [slides](https://bloonsinthesky.github.io/pdf/The%20Battle%20of%20the%20Neighborhoods%20-%20Slides.pdf)* ]
  
  + [Predicting House Sale Prices Using Regression](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Predicting%20House%20Sale%20Prices%20Using%20Regression): A series of **regression** models predicting house sale prices were developed and compared. Model instances with varying polynomial degrees, regularization types (i.e., ridge, lasso, elastic net), and extreme gradient boosting were compared using *R*<sup>2</sup> and RMSE scores. All hyperparameters were tuned using 5-fold **cross validation** and Bayesian optimization. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/Predicting%20House%20Sale%20Prices%20Using%20Regression/Predicting%20House%20Sale%20Prices%20Using%20Regression.ipynb)* ]
  
  + [Determining the Best Classification Model for Loan Default Prediction](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Determining%20the%20Best%20Classification%20Model%20for%20Loan%20Default%20Prediction): A series of **classification** models predicting loan status were developed and compared. Model instances using *k*-nearest neighbor, decision tree, support vector machine, logistic regression, and extreme gradient boosting algorithms were compared using F1 scores, Jaccard indices, and log loss. Parameter tuning via cross validation and Bayesian optimization. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/Determining%20the%20Best%20Classification%20Model%20for%20Loan%20Default%20Prediction/Determining%20the%20Best%20Classification%20Model%20for%20Loan%20Default%20Prediction.ipynb)* ]
  
  + [Movie Recommendation Systems](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Movie%20Recommendation%20Systems): Two simple movie recommendation systems were created using (1) **content-based filtering**, which recommends movies similar in genre as those rated highly by the user, and (2) **collaborative filtering**, which recommends movies rated highly by other users with similar inputs, i.e., movies watched and rated. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/Movie%20Recommendation%20Systems/Movie%20Recommendation%20Systems.ipynb)* ]

  *Tools: SQL, Pandas, Numpy, Matplotlib, Seaborn, Folium, Scikit-learn, XGBoost, Hyperopt*

+ ### Data Analysis and Visualization
  + [Gender Research Productivity Gap](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Gender%20Research%20Productivity%20Gap): *GGPlot* was used to visualize the gender research productivity gap in STEM and other scientific fields. I collected publication data by individual researchers in the *Mathematics*, *Genetics*, *Applied Psychology*, and *Mathematical Psychology* fields, then **compared the productivity distributions by gender** using histograms and kernel density plots. Note that this data was collected as part of my PhD dissertation, and a study based on my dissertation research was published in *Journal of Applied Psychology*. View [ *[R markdown](https://rpubs.com/bloonsinthesky/gender_productivity_gap_vis) | [published article](https://bloonsinthesky.github.io/pdf/Aguinis%20Ji%20Joo%202018%20JAP%20Gender%20Productivity%20Gap%20among%20Stars.pdf) | [slides](https://bloonsinthesky.github.io/pdf/Gender%20Productivity%20Gap%20Among%20Stars_Aalto%20Biz%20Seminar.pdf)* ]
   
  + [Descriptive Analysis of the 2019 Stack Overflow Developer Survey Data](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Descriptive%20Analysis%20of%20the%202019%20Stack%20Overflow%20Developer%20Survey%20Data): Data collected as part of the *2019 Stack Overflow Annual Developer Survey* was analyzed and visualized using *SQL*, *Python* and *IBM Cognos*. Findings yielded numerous insights into developer technology usage, trends, and demographics. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/Descriptive%20Analysis%20of%20the%202019%20Stack%20Overflow%20Developer%20Survey%20Data/Descriptive%20Analysis%20of%20the%202019%20Stack%20Overflow%20Developer%20Survey%20Data.ipynb) | [cognos dashboard](https://eu-gb.dataplatform.cloud.ibm.com/dashboards/171ae20c-d010-40b8-8837-c0da7850a86b/view/0509dd3d6e9437df42b4f2e407c87f052c662c0fb4bb8305d1d07b490e337197f06c1490c87e4f0f8f430c30a6be440ac9) | [slides](https://bloonsinthesky.github.io/pdf/Descriptive%20Analysis%20of%20the%202019%20Stack%20Overflow%20Developer%20Survey%20Data%20-%20presentation.pdf)* ]

  + [Automobile Sales, Recalls, and Sentiment](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Automobile%20Sales%2C%20Recalls%2C%20and%20Sentiment): Data on the *profits, quantity sold, units recalled, and customer sentiment* regarding 5 automobiles (distributed by 10 dealers) were visualized using *Tableau*. The data files used here were obtained from the IBM Accelerator Catalog. View [ *[tableau dashboard](https://public.tableau.com/app/profile/younghunji/viz/AutomobilsSalesRecallsandSentiment/Dashboard1)* ] 
  
  + [Airline Performance Dashboard Using Plotly Dash](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Airline%20Performance%20Dashboard%20Using%20Plotly%20Dash): A *plotly dash app* visualizing yearly *airline performance and delay* data from 2005 to 2020 was **deployed using Heroku**. Data were visualized using a collection of bar, line, pie, choropleth map, and treemap charts. View [ *[dash app](https://airline-dashboard.herokuapp.com/) | [python script](https://github.com/bloonsinthesky/Data-Science-Portfolio/blob/main/Airline%20Performance%20Dashboard%20Using%20Plotly%20Dash/app.py)* ]
  
  + [Visualizing Tesla and GameStop Stock Data](https://github.com/bloonsinthesky/Data-Science-Portfolio/tree/main/Visualizing%20Tesla%20and%20GameStop%20Stock%20Data): I used *yfinance* to extract the Tesla (TSLA) and GameStop (GME) stock data. I also used *beautiful soup* to scrape revenue data for the two companies. View [ *[notebook](https://nbviewer.jupyter.org/github/bloonsinthesky/Data-Science-Portfolio/blob/main/Visualizing%20Tesla%20and%20GameStop%20Stock%20Data/Visualizing%20Tesla%20and%20GameStop%20Stock%20Data.ipynb)* ]

  *Tools: SQL, GGPlot2, Tableau, Cognos, Plotly, Dash, BeautifulSoup*

+ ### Teaching About Data
  Since 2019, I have been the responsible teacher for the master's course *Doing Quantitative Research* at Aalto University School of Business. In 2020, due to the pandemic, the course was conducted fully online via pre-recorded lectures and live Zoom sessions. 
  
  Below are five pre-recorded lectures from 2020:
  
  + Main Lecturer
    + [Logistic Regression, Mediation, and Moderation](https://youtu.be/xnoyWw3QnlI)
    + [Fundamentals of Survey Resarch](https://youtu.be/FyC3LbO0EYA)
    + [Introduction to IBM SPSS](https://youtu.be/IDmYNgflVOg)
    
  + Secondary Lecturer
    + [Assumptions of Linear Regression](https://youtu.be/SRo6wAkYcn8)
    + [Research Design](https://youtu.be/UD8m5L34Tzk) 
  
I've also been involved in numerous **academic research** projects in which I performed the leading role in data collection, data analysis, paper writing, and presenting. In my research, I use statistical techniques from the social, natural, and formal science fields such as *structural equation modeling*, *time series analysis*, *allometric modeling*, and *social network analysis* on survey, experiment research, and archival data. You can view these outputs in a separate repository: [Academic Publications and Presentations](https://github.com/bloonsinthesky/academic-papers-and-presentations)
  
Thank you for your interest in my work. If you would like to chat about my portfolio, professional opportunities, or collaboration, please message me on LinkedIn: https://www.linkedin.com/in/younghunji/.
