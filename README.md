# Top_Youtube_Channels_Exploratory_data_analysis

This notebook is based on the [Top 5000 Youtube channels data from Socialblade.](https://www.kaggle.com/mdhrumil/top-5000-youtube-channels-data-from-socialblade)

This notebook contains data analysis on the Socialblade's data of top 5000 Youtube Channels. I have mainly relied only on Exploratory Data Analysis in this project. The main motives of doing this project:

* I am quite comfortable in doing predictive and mathematical analysis on various datasets, but felt the need to practice the art of Exploratory Data Analysis. Hence I have relied only on it in this project.
* The current hype surrounding Youtube also caused curiosity within me as to how the various features affect the number of subscribers of a channel and in general, how these features interact with each other.
* I have tried including various statistical concepts in the project.

The notebook contains cleaning of data, visualisation of distribution of data, and also visualisation of relationship between the two variables.

The conclusion derived from the analysis are:
1. There is a clear demarcation between various grades of channels based on their ranks, thus, the ranks of channels are very good indicators of grade of a channel.
2. The number of subscribers is not a very good indicator of the Grade of the channel.
3. Video views seems to influence the rank of the channel (although there are a few exceptions).
4. Higher the number of video views, higher is the grade (roughly).
5. There is a clear positive trend between the two variables, i.e more video views generally have strong positive correlation with number of subscribers.
6.  Generally number of subscribers are low for the channels having very large number of videos uploaded, while for channels having very low number of videos uploaded, there is a large variance. There is no strong linear relationship between the two variables though.
7. Video Uploads per view feature has a more strong relationship with the number of Subscribers than Video Uploads.The same is suggested mathematically too. Hence is a better feature for predicting number of subscribers of a channel.
