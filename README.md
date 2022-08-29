# Resume-Analysis-Using-NLP

## Problem Statement
Resume Parsing can be very tricky as a recruiter needs to process multiple number of them. Recruiters face many dilemmas when it comes to hiring candidates as it is quite ambiguous to understand how much of exposure and practical knowledge a candidate possesses concerning a given skill. It is particularly important in understanding this as it might help a recruiter get a fair idea about the suitability of the candidate for a given project. 


## Approach

1. A dictionary or table which has various skill sets categorised is maintained. If we have  words like keras, tensorflow, CNN, RNN appearing in the candidate CV, then they are merged  under one column titled ‘Deep Learning’.

2. We have used NLP algorithm that parses the whole resume and  searches  for the words mentioned in the dictionary or table.

3. The next step is to count the occurrence of the words under various category for each candidate. 

4. We represent the above information in a visualized  manner  so that it becomes easier  for the recruiter  to choose the candidate. At the same time a csv file is also created which gives a score card of the different skills acquired by each candidate.


## Output

<img width=400 src="https://user-images.githubusercontent.com/59830753/187107424-ffeee74e-c919-4a6e-bfb7-8287d7293fb9.png">

<img width=500 src="https://user-images.githubusercontent.com/59830753/187107685-012c8e68-43ff-41d1-9d0c-94af118f833b.png">



