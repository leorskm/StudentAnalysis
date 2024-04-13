## Student Analysis with Excel and Python

#### Project Description
This project was part of an assignment in a module during my final year at university. 
The idea was that each student in the module would complete two surveys - one about some basic facts about themselves and the other about personality ratings after taking a personality test. As expected, not all students completed this task, or did so inconsistently. Therefore, the dataset was not in perfect condition and was further tempered by the professor. So I had to use linear regression in _excel_ to impute the data and fill in the missing values. I also used _python_ for outlier detection to highlight inconsistencies in the data. The report, excel file and python file are all linked in this repository. 

#### Data Description
As mentioned above, the data was information provided anonymously by the students on various categories such as height, shoe size, distance travelled to university and seat row in class. The data on personality traits were based on students' scores on the 16Personalities test, including whether they were more extraverted or introverted, intuitive or observant, and feeling or thinking. 

#### Tasks Performed
In order to complete this task, I ran linear regressions on all columns with missing data using data analysis tools in Excel, as shown in the attached file. To merge the different survey tables I used the VLOOKUP function, but found that due to the fact that many students had not completed both surveys, the dataset with full rows was considerably smaller. I therefore decided to do the second part of the assignment - creating a story within the dataset - based on the first table only, identifying outliers and anomalies and finding reasons that could explain the occurrence of these outliers. I calculated the outliers using Python, as shown in the attached file. 
