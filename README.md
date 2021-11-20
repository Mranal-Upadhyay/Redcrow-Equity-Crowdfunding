# Redcrow Equity Crowdfunding 
## By Mranal Upadhyay

# INTRODUCTION 
The main objective of RedCrow equity funding is to help companies in initial times to raise the necessary capital to move forward and the early stage start-ups booming in the healthcare industry to expand their business. As in the initial stages it’s very risky for the companies to invest funds on a particular project. Also, to provide with limited funds but to cover maximum companies. Looking at the current scenario and economy crisis it is very difficult for companies to execute their plan, because by the time they feel confident that this product can boom in market, they realize that it will take several million dollars to make and launch this product and their ideas start failing. 

We started with gathering data from various sources and categorized the data which was similar to characteristics of healthcare domain. It is important for us to know and check whether how are these companies performing, also what are their weakness and strengths in particular sector and then lastly characterizing them according to certain parameter i.e. stages of companies. As this data will provide us with some better insights and find how these start-ups are reaching out to their targeted audience. 

Further to perform exploratory data analysis, we will be using Tableau, R studio and Excel. These tools will help to locate the potential patterns and examples that are essential to RedCrow and the new companies. It would also help in designing the measurements of how a start-up will conceivably be effective in fundraising for RedCrow. In R we would be performing regression techniques and build prediction models to achieve better insights where we will be concluding with highest accuracy model and lastly add recommendations how it can be more improved. Lastly, with the help to tableau dashboards will be providing with overview of investors and funds. 

# COMPANY OVERVIEW 
RedCrow is a web based direct investment platform that focusses on the healthcare space to connect the early-stage healthcare start-ups with potential investors that can help these early stage companies raise capital. RedCrow’s business objective is that it believes in building an ultimate social community in healthcare where the early stage entrepreneurs not only have a place to market their services and product to the people for investment, but also to gain valuable feedback from healthcare industry experts, and gain buzz and momentum at the same time. Also, to connect those with knowledge and money to early stage medical companies. Data helps RedCrow to perform their initial research and to access and analyze a company’s potential for success while also enabling them to evaluate specific hurdles to success. Apart from this it helps RedCrow to derive vital insights that can increase their own profit-share. 

# DATA COLLECTION AND PREPERATION 
Initially to get started with RedCrow provided us with some spreadsheets which contained information of the crowdfunding startups, their problem statements and recommendations on it. Many of it was scaled on a scale of 1-5. As the data provided to us was quite less for performing data analysis, we gathered data related to healthcare sector from various sources. We decided to proceed further with CrunchBase data which was collected from Kaggle. 

There were several CSV files which has data of startups dated from 1978 to 2014. The dataset included information of stages of companies, total funds raised, sectors, investors, social media engagement, and statistics information. We later filtered out the data and have taken data entries post year 2000 to perform further analysis. Here, we bifurcated the data into three simple categories/sectors i.e. healthcare, biotech and medical.

In an effort to develop a better business proposal and/or a better deliverable for RedCrow, we have taken one more dataset which is much broader macroeconomic perspective in understanding the environment affecting the startup sentiment in the healthcare sector. This data set mainly talks about an evaluative and positive/negative sentiment of a certain number of startups in the healthcare space and related verticals in this age of social media. Here, we will be tracking and evaluating social media metrics for understanding and correlating patterns of significance between a particular startup’s social media presence and their potential scalability for example. 

# METHOD OF ANALYSIS
The filtered dataset on which we have performed data analysis includes these following parameters: category, raised amount, total funding, stage of companies, website URL, twitter account info, location i.e. city & region. The main objective of our project is to predict amount raised by startups with respect to the various funding. This can be affected by various parameters such as startup category, location, stage of company and lastly their presence on social media because during our analysis we saw that companies having twitter account where successful in raising funds. Now, to check for each and every single parameter we build a correlation matrix. Moving forward to check relation between raised amount and each startup parameter we used Linear regression model. Through this Linear regression model, we will be finding whether it has positive or a negative(slope) relation between raised amount and each startup attribute. Lastly, it would help in predicting what are the chances of startup likely to raise funds. Also, we will be checking whether social media presence has helped a particular startup to raise funds or not i.e. how important it is to have a social media presence. 

# EXPLORATORY DATA ANALYSIS 
In an effort to develop a business proposal and/or a deliverable for RedCrow, we have taken a broader macroeconomic perspective in understanding the environment affecting the start-up sentiment in the healthcare sector. 
Accordingly, we have picked up two diverse datasets, one of which we have evaluated from Kaggle: 

1.	The first data set talks about an evaluative and positive/negative sentiment of a certain number of startups in the healthcare space and related verticals in this age of social media. We will be tracking and evaluating social media metrics for understanding and correlating patterns of significance between a particular startup’s social media presence and their potential scalability for example. 

2.	The second data set that we've chosen is a collaborative dataset that one of the teams have used previously for RedCrow. We found that dataset really interesting and we thought of expanding upon structural points built on by them and add on further important insights and patterns that we think might add value to the data according to the world situation today. The second data set, sort of looks at a broader economic environment for startups, by understanding the performance of about 4500 startups in the health care, medical and biotech industries.

Therefore, through this project deliverable, we're having sort of a double-edged perspective, the first one being specifically of the startups in the healthcare sector and how their social media presence would have an impact on their financial performance, especially on the amount of funds raised. On the other hand, we're also looking at a “BIG” data set containing startups across different sectors specifically focused on how the healthcare sector and related verticals, to understand patterns of these startups, and their driving focus into the future.

A representation of summary statistics showed us that a huge amount of values are missing in our healthcare dataset which need to be imputed for further analysis and visualization. 

![image](https://user-images.githubusercontent.com/94198619/142710902-19f395dc-45a0-4158-b495-60694e2d3455.png)

Having an outlook of the percentage of values missing in each of these metrics, helps us gauge, what exactly we can do with these missing values, whether we can impute it or whether removing it would be the best option possible.

# DATA VISUALIZATION AND INTERPRETATION
## DASHBOARD 1 
![image](https://user-images.githubusercontent.com/94198619/142711010-7071d9b9-cc79-4400-bf23-972b4ab114c2.png)

To construct this dashboard, we made use of the publicly available healthcare start-up data which comprises of information related to these early-stage healthcare start-ups. This dataset consists of information that talks about the number of milestones achieved by the early stage start-ups, number of funding rounds along with other details on the total number of funds raised etc. The dataset comprises of features that can provide a significant amount of insights when further analyzed and visualized. Thus, to derive meaningful insights, we constructed this dashboard where in the top-most graph we enlist the number of milestones achieved by the start-ups right from 2000 to 2013. This can provide a business user with a good idea on how a start-up has fared and also how many significant achievements it has collected over the years. The bottom left graph focusses on the overall profile of a start-up and gives a good amount of insight especially on the funding details of the start-up i.e. the number of funding rounds, amount raised by funding, total funding rounds etc. The bottom right graph shows the top 100 start-ups based on the number of funding rounds they have had in the past 10+ years. From the graph, it can be seen that aviir, instamed, galectin therapeutics have been the topmost performing start-ups based on the number of funding rounds from 2000-2013. 

## DASHBOARD 2 
![image](https://user-images.githubusercontent.com/94198619/142711046-a2895e5b-eed8-4a7e-9f97-1ab33616f311.png)

This is a dashboard based on the healthcare funding in USA. The graph on the left gives us an idea about the total funding amount in million for all of the healthcare start-ups present in our data. From the graph we can identify the topmost funded start-ups across the USA with Sigmacare being right at the top with 2600M raised in funding closely followed by Carestream and Relpysa with 2400M and 2200M raised respectively. The bar graph and map on the right tell us about the location of the states with the highest amount of funds raised. Post our analysis, we could conclude that start-ups in California, Massachusetts and New York have by far been more successful in attracting funding than the other states across USA.

## DASHBOARD 3 
![image](https://user-images.githubusercontent.com/94198619/142711066-015583e1-e644-45be-8c08-5cea16712c1a.png)

In the top left heat map of the dashboard, we have split all the start-ups present in our dataset based on their sector. From the heatmap we can conclude that more than 65% of the start-ups belong to the biotech sector. The graph on the right gives us a good idea about the operational status of the start-up companies. It is divided into 4 categories namely: operating, acquired, IPO and closed. From the graph, we can see that more than 50% of the companies are currently operational while a few of them are either in acquired state, IPO status or permanently closed. The bottom graph gives us a good idea on the sector-wise annual raised amount sector from the year 2000 till 2013. From the line graph, we can see that the biotechnology sector witnessed a remarkable growth in terms of funds raised from 2003 till 2013. Similarly, health sector and medical sector have witnessed a slow but steady growth in terms of annual funds raised in the discussed time period. Overall, the amount of funds raised by start-ups have increased tremendously year-on-year in the past decade. This could be attributed to the fact that many new start-ups have resorted to raising funds through campaigns and other online platforms like RedCrow.

## DASHBOARD 4 
![image](https://user-images.githubusercontent.com/94198619/142711079-7fed4de8-eaf4-4aab-bbf7-063767a1a865.png)

We have created a dashboard portraying social media influence of the startups. In this dashboard we have shown how social media can be used to build a startups value. In this new era having a social media account can accelerate the chances of getting funds. The main reason behind this is the Milesians who are very much active on social media. Other than that social media influence can make a startups appearance stronger. Startups who adopt a social media strategy that empowers social media influence provide a significant benefit to their startup in several ways, such as helping the startup company in setting the tone in its niche, exposing the products and services to large audiences, and providing added value by amplifying positive coverage. We have tried to show various factors which can be considered when it comes social media influence like the hotspot zones which have higher rate of healthcare startups funding, having a twitter account can help a startup to reach number of peoples. 

# BUIDING MODEL AND RESULT INTERPRETATION 
## LINEAR REGRESSION 
The main objective of building linear regression model is to predict the amount raised in each funding round with respect to the other independent parameters in the data i.e. total funds, participants, category, location and milestones achieved at. Through this model we predicted that there is a positive correlation between the category and amount raised. Apart from this also the eye catchy part is that companies having twitter account are likely to raise more funds and on the other hand if the particular company has a URL homepage then they are likely to raise less funds. This shows that how important it is to have social media presence but on a particular platform like twitter. Lastly, it also shows that the companies or startups which have newly opened or is operating in hotspot regions for example New York have showed positive sign in raising funds. The accuracy i.e. the R squared (% of variability) we obtained with linear regression model is 76%. 

![image](https://user-images.githubusercontent.com/94198619/142711147-b39a547c-d861-4d12-8320-6f6ac9a93d56.png)
![image](https://user-images.githubusercontent.com/94198619/142711151-bde3a46c-fb57-40ba-8d9e-4d381e458783.png)

## LASSO REGRESSION 
After performing linear regression model, we worked on lasso regression model to check whether we are able to achieve higher accuracy than linear regression or not. Here, too we calculated for the R squared (% of variability). The results were same as the linear regression model i.e. positive correlation between startups and amount raised. Secondly, for having more funds raised startups should have social media presence on platforms like twitter rather than just having URL homepage. The final accuracy i.e. R squared (% of variability) we obtained is 81%. 
So, now if we compare both the models i.e. linear regression model and lasso regression model it shows that lasso regression gave higher accuracy i.e. of 81%. Now, to further increase the accuracy i.e. to predict outcome closer value to the actual value we have applied more machine learning algorithms like XG Boost. 

## XG BOOST 
This machine learning algorithm was built to predict amount raised with respect to each funding rounds. The purpose behind is to closely compare the predicted value with the actual value. The highest accuracy till now we achieved was from lasso regression i.e. 81%. No doubt that lasso regression model helps in reducing the variance and also removing multicollinearity between the various parameters. But as mentioned above that if applied many more machine learning algorithms there are chances of achieving higher accuracy. Here, by applying XG Boost we obtained the accuracy of 87%. This also includes that if the startups haven’t decided location or haven’t created a social media account it can be helpful for such startups. 

## RANDOM FOREST 
We have used the random forest for a different dataset which is companies’ social media dataset. In this dataset it describes having a social media appearance can help companies grow in their fields. Random Forests are similar to a famous Ensemble technique called Bagging but have a different tweak in it. In Random Forests the idea is to decorrelate the several trees which are generated by the different bootstrapped samples from training Data. And then we simply reduce the Variance in the Trees by averaging them. Averaging the Trees helps us to reduce the variance and also improve the Performance of Decision Trees on Test Set and eventually avoid Overfitting. 

In this dataset, we have some target variables which we are planning to use in our model like: twitter account, followers, annual raised amount, tweets, location. 

### INTERPRETATION OF THE RANDOM FOREST 
1.	Predict the amount raised by the startups through their social media influence. 

2.	Startups having a twitter account tend to raise more funds. 

3.	If a company has more followers on social media platform then it will raise more funds. 

4.	Number of tweets also play a role in raising amount, that means if a company tweets often or more actively takes parts in events then it will more likely to raise funds. 

# PREDICTED MODELS

We would also like to recommend some predictive models through which redcrow can evaluate a startup. We have used three model’s linear regression, lasso regression, and XG Boost. However, after getting results we had come to a conclusion that XG Boost is the best model to predict the amount of funding with respect to the funding rounds, which will clear that which sector, state, region or factors affect the funding of startups and their future success. Another reason for recommending XG Boost is that it has given much higher accuracy among these models, about 88% which is really good.







