# School_District_Analysis
## Overview
This study uses Python, pandas & jupyter notebook to perform an analysis on highschools from a city school system. The purpose of the analysis is to help the school board make informed decisions regarding schools & their allocated budgets. 
### Background
The data used in this analysis is pulled from two separate resources csv files that show shools data & students data.
### Purpose
The purpose of this analysis is to allow the school board to view the descriptive values of the data available as well as filter it by different parameters to see the effect of each factor on the output of the student scores

Another requirement of the analysis was to allow the board to see adjusted results of the data after removing the scores of a certain school grade that was believed to be tampered with 
## Results
Firstly, to be able to perform the analysis, the data had to be cleaned, this was achieved by writing a code that allows us to clean studen names, to only include first & last names.
<img width="731" alt="Capture 1" src="https://user-images.githubusercontent.com/79733383/112784297-491dae80-901f-11eb-96a5-46de3c8b50b0.PNG">

Then We had to remove the data from the suspected tampered school & replace it by NaN values to ensure the integrity of the analysis

<img width="721" alt="Capture 2" src="https://user-images.githubusercontent.com/79733383/112784396-9c8ffc80-901f-11eb-8962-72884662c5ee.PNG">

After performing this adjustment, the results are as follows:

1. The district analysis changed from the following image:

<img width="696" alt="Capture before" src="https://user-images.githubusercontent.com/79733383/112784662-3c4d8a80-9020-11eb-8097-31703b778a82.PNG">

To the following:
<img width="699" alt="Capture after" src="https://user-images.githubusercontent.com/79733383/112784683-496a7980-9020-11eb-8f80-51c9831d135c.PNG">

