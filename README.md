# DATA201-Project
Topic: Covid-19 Impact on Price Indexes in New Zealand
We have three final data sets: final_Monthly, final_Quarterly, and final_long.
The final_Monthly dataset uses month as the period. 
The primary key Period is one month.  
It integrates all data frames with monthly data. It is wide data.
The final_Quarterly dataset uses quarter as the period. 
The primary key Period is three months (i.e. one quarter). 
It integrates all data frames with quarterly data, and also joins final_Monthly data with left join the data in each quarter. 
It is also wide data.
The final_long dataset just simply merges every long data frame by Period, Type and Value. 
It is easy to use its type to extract the same type value and plot.
