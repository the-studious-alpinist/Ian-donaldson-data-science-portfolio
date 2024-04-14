# Ian-donaldson-data-science-portfolio
Ian Donaldson's Data Science Portfolio

## R Projects

### University of Utah MSBA Capstone with Sponsor Swire Coca-Cola  
+ **Swire Coca-Cola - IS6813 Capstone Completion**
  + *Business Problem Overview and Project Objective:*
  
    Swire Coca-Cola requested our teams help optimize its innovation product launch strategy by leveraging machine learning and stochastic techniques to predict demand for new beverage products accurately. The project seeked to develop a robust framework for analyzing historical sales data of Swire and competitor products to forecast demand for innovative products, including prescribing optimal product launches, determining expected demand, identifying the best timing and region for each product, and accurately predicting inventory to reduce costs from the risk of over or under ordering revolutionary syrup flavors for established brands. The primary analytic challenge was in developing accurate predictive models based on historical products for new unseen products that could effectively handle the variability in product release durations and capture the complex factors influencing consumer preferences across different regions. This notebook documents the process and results of the machine learning and stochastic analysis, providing actionable insights for Swire's product launch strategy based on the derived machine learning and stochastic models.

  + *Solution to the Analytic Problem:*
  
    After experimenting with various machine learning algorithms, including logistic regression and XGBoost, the final solution to Swire Coca-Cola's analytic problem involved leveraging Stochastic Weight Averaging (SWA). While XGBoost predicted optimal product launch dates well, its accuracy in forecasting innovation demand unit sales using dummy data was lower than desired. Therefore, the team implemented SWA, a technique that blends the advantages of stochastic optimization with the stability of weighted averaging, to improve predictive performance. By incorporating SWA into the modeling process, the team achieved higher accuracy in forecasting demand for new beverage products, thus providing Swire with actionable insights for its product launch strategy.

  + *Contributions to Project:*
    
    As project co-lead, I assisted with orchestrating all group activities, ensuring effective communication and collaboration among team members through Zoom calls and a dedicated Slack channel. Additionally, I performed extensive exploratory data analysis (EDA) for specific products, including the Diet Moonlit Casava Energy 2L Multi Jug and Diet Smash Plum SSD 11Small 4One, to gather insights for model development. Leveraging my expertise, I ran machine learning algorithms, Stochastic Weight Averaging (SWA), and the NewsVendor model for inventory management of these products, contributing to the project's analytical framework. Furthermore, I produced multiple Tableau charts to visualize key findings and presented insights from the analysis to the Swire data science team. Additionally, I generated advertisement pictures for these innovative products, ensuring cohesive branding and marketing strategies aligned with our predictive modeling efforts.

  +  *Difficulties Encountered Along the Way:*

      The Swire project presented several unique challenges that required innovative solutions. One primary challenge stemmed from the lack of existing historical data that perfectly matched the characteristics of innovation products, necessitating the creation of dummy data for those machine learning models where required. Additionally, the sheer massiveness of the dataset, comprising 24 million rows, posed computational and processing challenges, requiring careful optimization strategies, such as sampling, to analyze the data better and build models to manage it efficiently. Moreover, the encryption of the data to protect real product information added an extra layer of complexity to the analysis. Coordination hurdles, collaborative struggles in a distributed team, and the need for timely individual submissions further added to the project's complexity.


  + *Lessons Learned:*
 
    From the Swire project, we gleaned valuable lessons integral to future endeavors. Meticulous exploratory data analysis (EDA) proved indispensable for extracting actionable insights from the dataset, emphasizing the importance of thorough data exploration at the outset of any analytical project. Additionally, maintaining an enjoyable team atmosphere was crucial in combating project fatigue and fostering collaboration, highlighting the significance of team dynamics in achieving project success. Creativity emerged as a key asset in model exploration, underscoring the need for innovative approaches to tackle complex analytical challenges effectively. Setting early timelines and milestones proved beneficial in avoiding last-minute rushes and ensuring timely project delivery. Moreover, effective audience engagement during presentations was pivotal in enhancing interest and understanding, emphasizing the importance of data storytelling and using engaging visuals to convey insights compellingly while minimizing technical jargon. These lessons serve as valuable guiding principles for future projects, reinforcing the importance of a holistic approach encompassing technical expertise and effective communication strategies.
  

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

    + [EDA](Donaldson_Ian_EDA.Rmd)

    + [Data Prep and Modeling](Home%20Credit%20Default%20Kaggle%20Competition%20Data%20Prep%20and%20Modeling%20Ian.Rmd)

    

    
