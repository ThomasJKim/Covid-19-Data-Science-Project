# Covid-19-Data-Science-Project
Using data collected using survey responses on questions regarding life satisfaction and different life factors, machine learning models were applied to try and predict how people respond to situations like the Covid-19 Pandemic

The questions from the survey were renamed to the variables on the left and variables with multiple choice responses like hobbies were split up even more later in the code. 

time       &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   | Timestamp\
gender     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp;   | What is your gender?\
ls_before     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Generally, how would you say you felt about life BEFORE the impacts the pandemic and social distancing?\
ls_after      &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Generally, how would you say you felt about life DURING the impacts the pandemic and social distancing?\
affected      &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Did anyone you know (including yourself) get seriously affected by the COVID-19 Virus in which it brought great stress to your life?\
lost_job       &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Did you lose your job during this pandemic? (And you are still unemployed)\
work_method    &nbsp; &nbsp; &nbsp; &nbsp; | If you worked through this pandemic, what was your main method of work? Select N/A if you did not work\
residents       &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Who did you live with during this pandemic?\
outdoor_time  &nbsp; &nbsp;  | On average, how much time do you spend outside per day?\
exercise_time  &nbsp; &nbsp;  | On average, how much time do you spend exercising per day?\
sleep_time    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Using this scale, where one bubble is one hour, around how many hours of sleep do you get per night? If you sleep over 10 hours a night, select 10.\
importance     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Which areas of life are highly important to you?\
hobbies     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;    |What were your main hobbies during the pandemic? (Hobbies you spend around 3-4+ hours doing a week)\
news        &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;    |Do you keep up to date with current events and news?\

sample_bias   (Not used in feeature variables) |  This question is completely optional and will only be used to more accurately understand any sampling bias at play. How did you hear of this survey? (i.e. Tom's instagram story)
