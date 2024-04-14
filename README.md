# Ian-donaldson-data-science-portfolio
Ian Donaldson's Data Science Portfolio

## R Projects

### University of Utah MSBA Capstone with Sponsor Swire Coca-Cola  
+ **Swire Coca-Cola - IS6813 Capstone Completion**
  + *Business Problem Overview and Project Objective:*
  
    Swire Coca-Cola sought our assistance in optimizing its innovation product launch strategy using machine learning and stochastic techniques to predict demand accurately. The project analyzed historical sales data to forecast demand, determine optimal product launches, and predict inventory needs. The primary challenge was developing accurate predictive models for new products while handling release durations and consumer preference variability. Leveraging machine learning and stochastic analysis, our team provided actionable insights for Swire's product launch strategy.

  + *Solution to the Analytic Problem:*
  
    After experimenting with various machine learning algorithms, including logistic regression and XGBoost, the final solution involved leveraging Stochastic Weight Averaging (SWA). While XGBoost predicted optimal product launch dates well, its accuracy in forecasting innovation demand unit sales using dummy data was lower than desired. Therefore, the team implemented SWA, a technique that blends the advantages of stochastic optimization with the stability of weighted averaging, to improve predictive performance. As a result the team achieved higher accuracy in forecasting demand for new beverage products and prescribing actionable insights for its product launch strategy.

  + *Contributions to Project:*
    
    As project co-lead, I assisted with orchestrating all group activities, through Zoom calls and a dedicated Slack channel. I performed extensive exploratory data analysis (EDA) for  a deep dive on overall sales of all products and then focused on specific products with additional EDA in the machine learning notebooks (Diet Moonlit Casava Energy 2L Multi Jug and Diet Smash Plum SSD 11Small 4One), to gather insights for model development. I ran linear regressions, machine learning algorithms, Stochastic Weight Averaging (SWA), and the NewsVendor model for inventory management of these products, contributing to the project's analytical framework. For effective presentation I produced multiple Tableau charts to visualize key findings and presented those insights to the Swire data science team. To enhance audience engagement, I generated advertisement pictures for these innovative products to boost the appeal of the drier predictive modeling aspects of the presentation.

  +  *Difficulties Encountered Along the Way:*

      The Swire project presented several challenges that required unique solutions. One primary challenge stemmed from the lack of existing historical data that perfectly matched the characteristics of innovation products, necessitating the creation of dummy data for those machine learning models where required (most dummy data did not perform well when highly correlated features such as Dollar Sales were removed from predicting Unit Sales). Additionally, the sheer massiveness of the dataset, comprising 24 million rows, posed computational and processing challenges, requiring careful optimization strategies, such as sampling, to better analyze the data and build models to manage it efficiently. Moreover, the encryption of the data to protect real product information added an extra layer of complexity to the analysis. Coordination hurdles, collaborative struggles in a distributed team, and the need for timely individual submissions further added to the project's complexity.

  + *Lessons Learned:*
 
    From this project, I reinforced the importance of data exploration, maintaining team dynamics, fostering creativity in model exploration, and setting early timelines in my learning. I learned that creative communication is one of the most important aspects of a high-performing data science team. It was through spitballing ideas that some of our most valuable ideas gained traction. The project also emphasized that effective audience engagement during presentations and data storytelling are crucial for project success, guiding future endeavors.

  + *Individual R Notebooks:*

    + EDA
      + [RMD](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Donaldson_Ian_Sales_EDA)
      + [HTML](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Swire%20EDA.html)
 
    + Data Prep and Modeling
      + [RMD](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Casava-and-Plum-combined.Rmd)   
      + [HTML](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Casava-and-Plum-combined.html)

  + Other Workbooks
    + [Plum Tableau](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Swire%20Plum.twb)
    + [Casava Tableau](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Swire%20Casava.twb)
    + [Diet Moonlit Tableau](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Swire%20Diet%20Moonlit.twb)
    + [Diet Smash Tableau](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Swire%20Diet%20Smash.twb)
    + [Casava NewsVendor](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/cassava_newsvendor_final.xlsx)
   
  + Group GitHub - Will Update Once Complete
  

### Kaggle Competitions  
+ **Home Credit Default - IS6812 Capstone Prep Project**
  + *Business Problem Overview and Project Objective:*
        
    Home Credit operates in rapidly growing and developing markets, catering to "unbanked" consumers without traditional credit scores. Home Credit seeks a predictive model utilizing alternative data sources to mitigate loan losses and expand its lending portfolio. Our project's objectives included a comprehensive analysis of Home Credit's dataset, emphasizing crucial feature discovery through extensive EDA and identifying necessary data cleaning processes. The primary goal was to develop a predictive model capable of accurately assessing the likelihood of customer loan default.

  + *Solution to the Business Problem:*

      Several models were developed to address Home Credit's business problem, with the final selection being a logistic regression model. Based on eight statistically significant variables identified through meticulous data exploration, this model not only boosts revenue but also identifies risky loans prone to default. The model's high AUC score and white-box explainable features ensure transparency, aiding regulatory compliance across operating countries.

  + *Contributions to Project:*

    I orchestrated all group activities as the project lead, maintaining communication through Zoom calls and a dedicated Slack channel. Detailed minutes of meetings ensured everyone was informed and deadlines were met. I spearheaded the development of logistic models, particularly focusing on the eight vital variables identified during the data exploration phase. The model, incorporating upsampling to address the rarity of default events, emerged as the chosen solution.

  + *Business Value of Solution:*

    The recommended logistic model reduces default risks and enhances revenue by minimizing unnecessary loan denials. The expected revenue increase is nearly 200%, providing a significant business advantage. The model's predictive features offer a transparent justification for loan approvals and denials, which is essential for addressing regulatory inquiries.

  +  *Difficulties Encountered Along the Way:*

      Challenges included imbalanced data, especially the rarity of default events (< 8%), necessitating careful handling to prevent bias in favor of the majority class. Some machine learning models required extensive runtime, addressed through downsampling, while upsampling was employed for quicker models like the logistic regression. Coordination hurdles, collaborative struggles in a distributed team, and the need for timely individual submissions were other challenges encountered.

  + *Lessons Learned:*

    Key takeaways encompass the importance of meticulous EDA for data insights, maintaining an enjoyable team atmosphere to combat project fatigue, the necessity of creativity in model exploration, setting early timelines to avoid last-minute rushes, effective audience engagement during presentations to enhance interest and understanding with more focus more on data story telling and less on the process used.

  + *Individual Notebooks:*
   
    + [EDA RMD](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/Home_Credit_EDA.Rmd)
    + [EDA HTML](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/HomeCredit-EDA.html)

    + [Data Prep and Modeling RMD](Home%20Credit%20Default%20Kaggle%20Competition%20Data%20Prep%20and%20Modeling%20Ian.Rmd)
    + [Data Prep and Modeling HTML](https://github.com/the-studious-alpinist/Ian-donaldson-data-science-portfolio/blob/main/HomeCredit_Modeling.html)
 


      
    

    
