# Ian-donaldson-data-science-portfolio
Ian Donaldson's Data Science Portfolio

## R Projects  

### Kaggle Competitions  
+ **Home Credit Default - IS6812 Capstone Prep Project**
  + *Business Problem Overview and Project Objective:*
        
    Home Credit operates in rapidly growing and developing markets where many 
consumers are "unbanked," lacking traditional credit scores common in more 
developed economies. To maintain acceptable levels of loan losses while 
expanding its lending portfolio, Home Credit requires a predictive model that 
leverages alternative data sources, such as transactional information and 
telecommunications data, to assess the likelihood of customer loan default. The goal of this project was to delve into Home Credit's dataset, with a focus on understanding crucial features through extensive EDA and also identifying any necessary data cleaning 
processes. The ultimate objective is to create a predictive model capable of 
determining whether a customer will successfully repay a loan or default.

  + *Solution to the Business Problem:*

      Our group developed several models for analyzing Home Credit's business problem and ultimately selected a logistic regression model based on 8 statistically signficiant and important variables uncovered from the data exploration process. The model not only will increase revenue for the business, but also help identify loans that may be too risky in terms of default. A key benefit of the logistic model beyond just it's high AUC score is the white box explainable features that will help Home Credit explain how risk is gauged using the logistic model to any regulators in countries where it operates.

  + *Contributions to Project:*

    I organized all group meetings, zoom calls, and and kept us on track as a group through a dedicated Slack channel with which we collaborated on the project. I maintained minutes of all meetings and kept the group up to date on deadlines to avoid last minute work which might affect the end product. I produced several logisitic models including the model based on the 8 important variables that I identified and that used upsampling to more accurately predict the relatively rere event of default, and that was ulitmately selected as our solution to the business problem.

  + *Business Value of Solution:*

    The logistic model that we ultimately recommended not only reduced risk through less potential defaults, but also increased revenue by denying fewer loans that did not end up defaulting. Our model would be expected to increase revenue by nearly 200%. Additionally, should questions ever arrise as to how the model discrimates against applicants for approval verse denial, the business can easily use the predictors to justify the approval process to any regulators.  

  +  *Difficulties Encountered Along the Way:*

      Some difficulties encountered along the way included the imbalance of data with relatively few defaults (< 8%) and ensuring that our models did not become too biased in favor of the majority class. Some of the machine learning  models took hours, or even overnight, to run, espcially with more intensive grid searches. Fine tuning this models any time a change was needed for exploration was incredibly time consuming. This was primarily addressed thorugh downsampling for those long running models, while we used upsampling (to better predict the more rare event of defaults) for quick to run models such as the logistic model. Other difficulties included common issues faced by groups including finding times to meet that worked for everyone, working collaboritely while being distributed as a team, and ensuring all team members submitted individual work early enough to give the team time to discuss and review it.

  + *Lessons Learned:*

    Lessons learned on this project included careful EDA to find any insights in the data, having fun to avoid brain fog from such a large data set, the importance of being creative and looking at many models, setting early timelines to avoid rushing at the end, addressing the audience during a presentation to more fully engage and raise interest.

    

    
