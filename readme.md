# IBM Sales Analysis



## Table of Contents
[1.0 Directory Structure](#1.0-Directory-Structure)<br>
[2.0 Project Outline / Problem Statement](#2.0-Project-Outline-/-Problem-Statement)<br>
[3.0 Description of Data](#3.0-Description-of-Data)<br>
>- [3.1 Size](#3.1-Size)<br>
- [3.2 Source](#3.2-Source)<br>
- [3.3 Data Dictionary](#3.3-Data-Dictionary)

[4.0 Data Visualization](#4.0-Data-Visualization)
[5.0 Conclusion](#5.0-Conclusion)<br>
>- [5.1 Next Steps](#5.1-Next-Steps)


## 1.0 Directory Structure

```
.
├── IBM Sales Analysis
    ├── code
        ├── EDA.ipynb
    ├── data
        ├── sales_data.csv
        ├── cleaned_data.csv
    ├── plots
        ├── ACT_plot.jpg
        ├── SAT_plot.jpg
        ├── ACT_SAT_plot.jpg
    ├── README.md
    └── sat_project.pdf
```

## 2.0 Project Outline / Problem Statement


The SAT/ACT are strong determinant of higher educational success, but how accurate are they?


How do we get a more accurate representation of the population mean SAT/ACT?



Can we trust this data?


---
## 3.0 Description of Data\
For this analysis I used [IBM Sales data](https://www.kaggle.com/thatbrock/ibm-watson-saleswinloss)  from [kaggle.com](https://kaggle.com).
### 3.1 Size
A few kb. Working with a very small DataFrame
### 3.2 Source
These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.
Provided Data
For this project, you'll have four provided datasets:

2017 SAT Scores<br>
2017 ACT Scores<br>
2018 SAT Scores<br>
2018 ACT Scores<br>
### 3.3 Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT|List of states in the United States, plus Washington D.C.|
|act_2017_participation_rate|float|ACT|The participation rate of students within the state who took the ACT exam in 2017.|
|act_2017_english|float|ACT|The average English score of the ACT exam within the state in 2017.|
|act_2017_math|float|ACT|The average Math score of the ACT exam within the state in 2017.|
|act_2017_reading|float|ACT|The average Reading score of the ACT exam within the state in 2017.|
|act_2017_science|float|ACT|The average Science score of the ACT exam within the state in 2017.|

---
## 4.0 Data Visualization


<img src="./pictures/Route to Market(RTM) by Deal size Category - (Conversion Rate).jpg">
In the above
<br>

<img src='./pictures/RTM & Supplies Group by Deal size Category - (Conversion Rate).jpg' >

<br>
<img src='./pictures/CSR & RTM by Deal size Category - (Conversion Rate).jpg' >
sales channel
<br>
<img src= './pictures/Conversion Rates by RTM Over Time.jpg'>


<br>
<img src='./pictures/Conversion Rates by RTM & Region Over Time.jpg' >


<br>
<img src='./pictures/Conversion Rates by RTM & Region - (Bar Chart).png' >

<br>
<img src='./pictures/Total Opporuties by RTM & Region - (Bar Chart).png' >

<br>
<img src= './pictures/Total Wins by RTM & Region - (Bar Chart).png'>

---
## 5.0 Conclusion
#### Conclusion


SAT/ACT data is heavily skewed (Hard to Analyze accurately)



Increasing ACT/SAT participation will providee better reading



There is a lot of room for error, the average recorded scores could
 be very far from the true population mean.


---
### 5.1 Next Steps
Next steps would be to collect more data to paint a better picture of how SAT/ACT predict college success

---