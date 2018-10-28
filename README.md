# TDI_dataChal
Graphic demostration for the proposed project for The Data Incubator

### Demo graph 1

A time slice vs. popularity scatter plot to show trends for different topic on different social media. Facebook has the most popularity, while GooglePlus is the least. I also include a linear regression line in the graph to show its general trend.

<a href="https://github.com/yingeddi2008/TDI_dataChal/blob/master/source.vs.section.png"><img src="https://github.com/yingeddi2008/TDI_dataChal/blob/master/source.vs.section.png" alt="Popularity across time for different social media" style="float: right" width="850"/></a>

### Demo graph 2

Taking a close look at the previous plot, I can spot some news has a steep slope, meaning they draw a lot of attention as time goes by. I want to identify those news articles, and see what is the word composition for their headlines. I performed simple linear regression using time points vs. popularity, and take out the headline of the news with the top 100 largest coefficient. 

<a href="https://github.com/yingeddi2008/TDI_dataChal/blob/master/headline.wordcloud.png"><img src="https://github.com/yingeddi2008/TDI_dataChal/blob/master/headline.wordcloud.png" alt="Wordcloud for the top 100 largest coefficient news " style="float: right" width="450"/></a>