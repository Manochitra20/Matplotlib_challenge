# Matplotlib Homework - The Power of Plots

# Pymaceuticals data analysis observations:
Results and Discussion:
    The pymaceuticals data consisted a total of 1893 observations. The number of unique mice ID was calculated to be 249. 
    There was duplication in the data for a specific mouse ID (g989). 
    The dataframe was cleaned by remvoing the duplicated mouse ID and further analysis was conducted.
    
    Of the total 1880 mice included in data analysis, 51% were  male and 49% were female. 
    Further, to quantitatively determine if the data consisted of any potential outliers, the IQR was calculated for the final tumor volume of each mouse across   four of the treatment regimens:  
    Capomulin, Ramicane, Infubinol, and Ceftamin.
    The data for Infubinol showed a potential outlier in the final tumor volume (outlier value: 36.321346).
    This was also qualitatively represented in a box and whisker plot.
    
    
    The purpose of this study was to compare the performance of Pymaceuticals drug of interest, Capomulin, versus the other treatment regimens.
    So the data was grouped based on the mouse treated with Capomulin.
    Mouse ID "l509" that was treated with Capomulin was selected and line plot of tumor volume vs. time point was generated.
    
    Based on the line plot, it is evident that the tumor volume drastically decreased during the timepoint of 30-40 days when treated with Capomulin.
    
    A scatter plot was generated with average tumor volume vs. mouse weight for the Capomulin regimen, which showed that as the weight increases the tumor volume also increased.
    
    The correlation between mouse weight and the average tumor volume was calculated to be 0.84 based on Pearsons correlation coefficient.
    Since the value is more inclined towards 1, there is said to be a moderate positive correlation between the variables, 
    which means that the weight of the tumor volume is directly proportional to the mouse weight.
