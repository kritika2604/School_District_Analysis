# School_District_Analysis
Module 4 Pandas

## Overview of the school district analysis: 
A funding analysis was made in a particular district with few schools on the basis of the school size, type and school spending by the school board.
An evidence of academic dishonesty was reported from Thomas High School, especially in the 9th Graders reading and math scores, which were altered. 

For the purpose of correct analysis, the values of Thomas High School was made NaN and the effect of the overall results was analysed. 
 
# Results
## How is the district summary affected? 
Almost negligible effect

<img width="806" alt="image" src="https://user-images.githubusercontent.com/94858846/151202611-1ccb143c-9b67-448d-89a2-e26f82fff77d.png"> <img width="720" alt="image" src="https://user-images.githubusercontent.com/94858846/151202695-3036900d-bad5-489a-b7cf-ece59477c8da.png">

## How is the school summary affected? 

There was a marginal effect which can be seen below - 

<img width="731" alt="image" src="https://user-images.githubusercontent.com/94858846/151205897-ab17960a-569a-476d-87e3-9bab366620dc.png"> <img width="725" alt="image" src="https://user-images.githubusercontent.com/94858846/151206006-a81407c7-be52-4774-bd99-b75410667298.png">


## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Results show that there some inflation showing up in the grades before the Thomas high school's 9th grader's math and reading scores were replaced. 

Originally -

<img width="731" alt="image" src="https://user-images.githubusercontent.com/94858846/151207883-87455f94-8357-45ae-9e44-f6d09aa988f3.png">

After Thomas High School replacements -

<img width="591" alt="image" src="https://user-images.githubusercontent.com/94858846/151208045-b9a3dbaf-7a37-429a-a89e-f443ea228f6e.png">

## How does replacing the ninth-grade scores affect the following:

Math scores by grade-

<img width="236" alt="image" src="https://user-images.githubusercontent.com/94858846/151209947-54a2e3f3-f1e1-4164-b04e-4a835d2f7a45.png">

Reading Scores by grade-

<img width="249" alt="image" src="https://user-images.githubusercontent.com/94858846/151210300-8bcb70c8-0179-4065-9d02-5947ca350d7b.png">


## Scores by school spending - 
 - Was not affected 
 
Originally - 

<img width="728" alt="image" src="https://user-images.githubusercontent.com/94858846/151210747-d4286d00-5a4e-42ef-a479-81450916d9d8.png">

After Thomas High School replacements - 

<img width="731" alt="image" src="https://user-images.githubusercontent.com/94858846/151210961-4c880c15-19ce-452a-ac49-5eb3457ed7ee.png">

## Scores by school size - 
 - Was not affected 
 
Originally - 

<img width="570" alt="image" src="https://user-images.githubusercontent.com/94858846/151213408-bb02ed58-4185-476a-a1b3-e5296ea1ab68.png">

After Thomas High School replacements - 

<img width="563" alt="image" src="https://user-images.githubusercontent.com/94858846/151213510-04a2d242-ad76-4e63-853e-6dba7c570ddc.png">

## Scores by school type - 
- Was not affected 

Originally - 

<img width="536" alt="image" src="https://user-images.githubusercontent.com/94858846/151213612-b2b547c0-b3b7-4edc-bae8-813889e0e400.png">

After Thomas High School replacements - 

<img width="545" alt="image" src="https://user-images.githubusercontent.com/94858846/151213731-3cea536a-0aa6-4c81-af4c-4bc09303e6a6.png">


# Summary: 
Thomas High School's academic dishonesty can be seen in the summary for top 5 schools. 

Originally - 
- Math Score        = 83.4
- Reading Score     = 83.8
- % Pass Math       = 93.2%
- % Pass Reading    = 97.3%
- % Overall Passing = 90.9%

Aftet the values were replaced the same values beacame - 

- Math Score        = 83.3
- Reading Score     = 83.9
- % Pass Math       = 93.2%
- % Pass Reading    = 97.01%
- % Overall Passing = 90.6%

The passing percentage for reading has reduced quite a bit and is also affecting the overall passing percentage. 

