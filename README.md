# DATA201-Project
## Topic: Covid-19 Impact on Price Indexes in New Zealand
## Conclusion
If you look at just a few of the industries that we analyzed, the impact of COVID-19 on New Zealand has not been significant. But across all industries, the damage is irreversible. A lot of things are linked together. It is like the butterfly effect, when one small event has an impact, the next series of events will be affected. In other words, COVID-19 has not only had a negative impact on the economy, yet on all aspects of society, all aspects of the country. Therefore, controlling Covid-19 and decreasing daily new cases are the first target of the country and everyone. The price index of food has risen severely, which is related to people’s lives, and government intervention is needed to reduce the negative impact. Production costs and prices have fallen, which is not a good economic trend.

## Data availability and data status
The data sources of our project are all legal and publicly used, and anyone who is interested in these data can use it.
The charts generated in this project reflect the various industries and different residents' living price indices in New Zealand. Economists or scholars can directly use these diagrams, saving them the trouble of sorting out.

We have combined all the data into two different tables, both of them are driven by time. one is on a monthly basis and another one is on a quarterly basis. Those in need can use these two forms according to different needs. Both tables have clear classifications, which are very convenient for selection and application.

We have three final data sets: final_Monthly, final_Quarterly, and final_long.

## final_Monthly dataset
The final_Monthly dataset uses month as the period. 

The primary key Period is one month.  

It integrates all data frames with monthly data. 

It is wide data.
## final_Quarterly dataset
The final_Quarterly dataset uses quarter as the period. 

The primary key Period is three months (i.e. one quarter). 

It integrates all data frames with quarterly data, and also joins final_Monthly data with left join the data in each quarter. 

It is also wide data.
## final_long dataset
The final_long dataset just simply merges every long data frame by Period, Type and Value. 

It is easy to use its type to extract the same type value and plot.




