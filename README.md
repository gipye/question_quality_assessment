# Question quality assessment

# Dataset
- We will use Task 3 of [Diagnostic Questions competition](https://www.microsoft.com/en-us/research/academic-program/diagnostic-questions/), which was one of the [NeurIPS 2020 Competitions](https://neurips.cc/Conferences/2020/CompetitionTrack).
- We can download the dataset from [here](https://dqanonymousdata.blob.core.windows.net/neurips-public/data.zip) and put it under ```data``` folder.
- subfolder structure
  - ```image```: Actual questions.
  - ```metadata```: Some information about question and students.
  - ```train_data```: We will use ```train_data_3_4.csv``` for training. It is for Task 3 and Task 4.
  - ```test_data```: We will use ```quality_response_remapped_public.csv``` for validation and ```quality_response_remapped_private.csv``` for test.

# Task
- Estimate the quality of questions from students responses and other information about questions.
- Calculate the rankings of the questions using the template in ```submission/template.csv```. The file calculating ranking is ```20182610.csv```, which was submitted in LMS.
