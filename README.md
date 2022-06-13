# MODULE 14: NYC CITIBIKE WITH TABLEAU

[link to dashboard](https://public.tableau.com/shared/4JYC4RTSG?:display_count=n&:origin=viz_share_link)

## Overview of the Analysis

* My friend Kate and I went on a once-in-a-lifetime trip last summer. For two weeks, we spent in New York City, seeing famous sites such as Central Park, the Statue of Liberty, and the Empire State Building. It was a lovely trip, and as you went home together, you realized something when you looked over your holiday photographs. Citi Bike, an unexpected suspect, was one of the crucial elements in the magic.

* Kate and I had biked everywhere, allowing you to truly get to know the city and engage with the people who live there and commute by bicycle. In your imagination, a brilliant idea emerges. What if you could create a bike-sharing company in your hometown of Des Moines, Iowa?

* Kate and I started brainstorming, when she called me with some amazing news. She has a prospective angel investor who could be interested in contributing startup funds to investigate a Des Moines bike-share program.

* Although this is an exciting potential, I are aware that I must remain practical. The practicalities of making this business operate in Des Moines may differ significantly from those in New York City. I decided that the first step is to learn how the bike-share system in New York City operates. You'll then make a proposal for how it may function in Des Moines.

* Kate is outgoing, pleasant, and unafraid. Your proposal's face should undoubtedly be her. You, on the other hand, have data analytics knowledge and can lead the charge in determining how this project will really operate.

### Purpose
* Through the use of Tableau, understand how NYC Citi Bike service works and present some findings for Des Moines, Iowa, bike sharing business model.

## Results of the Analysis

* Trips are not homogeneously dispersed around the city. On the contrary, they are clustered around tourist centers. This suggests that for Des Moines, there have to be more stations around places of interest.

**Image 1. New York City City Bike Starting Locations** 

![Captura de Pantalla 2022-04-20 a la(s) 15 30 43](https://user-images.githubusercontent.com/65054637/164319781-4ccc0a71-6639-4a81-b76b-3da394c40640.png)

* The start and end of trips follow the same trend. That is, more or less at the same time that a trip begins, another one ends and therefore there will be bicycles available. However, this point does not take into account the peaks in demand around 5:00 p.m. You have to have enough bikes at these times to supply the demand.

**Image 2. Number of Bikes Starting / Ending a Trip According to Hour of the Day**

![Captura de Pantalla 2022-04-20 a la(s) 15 22 26](https://user-images.githubusercontent.com/65054637/164319794-870170cb-8f26-4a9f-9a94-5a2f5cf92dfe.png)

* The most common duration for a trip in New York is around 4 hours. In a deeper analysis, the possible distance to be covered in 4 hours will have to be considered for the specifications of the bicycles to be purchased.

**Image 3. Checkout Time for Users**

![Captura de Pantalla 2022-04-20 a la(s) 15 23 00](https://user-images.githubusercontent.com/65054637/164319801-dfd472c4-7180-46ce-916a-a32bec18bf96.png)

* The vast majority of trips are made by men. This suggests that in launching our bike service in Des Moines, we focus on marketing to men.

**Image 4. Checkout Time by Gender**

![Captura de Pantalla 2022-04-20 a la(s) 15 23 14](https://user-images.githubusercontent.com/65054637/164319815-5f1b1325-e57d-43b5-a750-743b743cb102.png)

** The most common time period that people use a bicycle service in New York is from 7 AM to 7 PM with demand peaking at 9 AM, 4 PM and 7 PM. This may be due to the hours of breakfast, lunch and dinner, which suggests that we could have alliances with restaurants. 

**Image 5. Trips by Weekday per Hour**

![Captura de Pantalla 2022-04-20 a la(s) 15 23 26](https://user-images.githubusercontent.com/65054637/164319825-3fc05ed8-9e00-4946-8ecb-08fcdf223de9.png)

* It is confirmed that the vast majority of bicycle service users in New York are gentlemen. However, it is observed that women have a special interest in bicycle services on Saturdays between 10 AM and 7 PM.

**Image 6. Trips by Gender (Weekday per Hour)**

![Captura de Pantalla 2022-04-20 a la(s) 15 23 36](https://user-images.githubusercontent.com/65054637/164319840-eb5983fc-0872-4871-8f78-e388906c46ed.png)

* Most of the users of bicycle services are subscribers, which suggests that the inhabitants of the city are really the ones who use the service and not the tourists. This has an impact on the business model to propose to Des Moines since we will have to focus on local men who travel at 9 AM, 4 PM and 7 PM.

**Image 7. User Trips by Gender by Weekday**

![Captura de Pantalla 2022-04-20 a la(s) 15 23 59](https://user-images.githubusercontent.com/65054637/164319848-fd9a3bb1-ea54-4ce5-96b8-ed34de9e5338.png)

## Summary of the Analysis

According to the previous visualizations, I would suggest to integrate the following points to the Des Moines Bike Sharing business model:

1. Deploy more bike stations around city centre near historical landmark / turistic spots.
2. People normally tend to use NYC Citi Bike service from 7 AM to 7 PM. With this schedule we can prepare for the following:
    * Prepare for demand peaks which begin at 5 PM and end at 7 PM.
    * Give maintainance to our bikes from 8 PM to 6 AM
3. Look for partnerships with restaurants and turistic spots as people tend to use  NYC Citi Bike around meal times.
4. Focus our marketing campaings around men as the vast majority of people who use this services are men.
5. Generate strategies to attract more women to our service. Given the NYC Citi Bike behaviour, they normally use bicycle services on Saturdays between 10 AM and 7 PM. Once they are already users, we can try to attract them with offers and promotions.
