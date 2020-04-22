# IBM Sales Analysis



## Table of Contents
[1.0 Directory Structure](#1.0-Directory-Structure)
[2.0 Project Outline / Problem Statement](#2.0-Project-Outline-/-Problem-Statement)
[3.0 Description of Data](#3.0-Description-of-Data)
>- [3.1 Size](#3.1-Size)<br>
- [3.2 Source](#3.2-Source)<br>
- [3.3 Data Dictionary](#3.3-Data-Dictionary)

[4.0 Data Visualization](#4.0-Data-Visualization)
[5.0 Conclusion](#5.0-Conclusion)<br>
>- [5.1 Next Steps](#5.1-Next-Steps)

[6.0 Outside Sources](#6.0-Outside-Sources)<br>

## 1.0 Directory Structure

```
.
├── project_1
    ├── code
        ├── starter-code.ipynb
    ├── data
        ├── act_2018.csv
        ├── act_2017.csv
        ├── sat_2018.csv
        ├── sat_2017.csv
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

<img src="./data/graph.png">

---
## 5.0 Conclusion
#### Conclusion


SAT/ACT data is heavily skewed (Hard to Analyze accurately)



Increasing ACT/SAT participation will providee better reading



There is a lot of room for error, the average recorded scores could
 be very far from the true population mean.



### 5.1 Next Steps
Next steps would be to collect more data to paint a better picture of how SAT/ACT predict college success


---
## 6.0 Outside Sources

- Link 1
<p href='https://www.forbes.com/sites/prestoncooper2/2018/06/11/what-predicts-college-completion-high-school-gpa-beats-sat-score/#2957732e4b09'>Preston Cooper</p>
