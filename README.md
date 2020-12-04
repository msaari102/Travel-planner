# Traffic planner

Final project for the Building AI course

## Summary

Deciding optimal time to commute takes quite a lot effort. Google maps can estimate time needed to travel and Traffic Management Finland offers up to date information about traffic volumes but these only give information, how long travelling would take at current situation. Improved application is needed to predict how traffic volumes change during travel and use this information to estimate best time to leave according to predictions.


## Background

In densely populated area, traffic jams are common. Typical peaks in traffic volumes in Finland can be seen around 7-9 am. and 15-17 pm. When travelling takes 30-60min, driver should be able to predict traffic jams before they are forming. Traffic jams and slower average speed affect almost everyone travelling during peak hours in major cities. Since writer doens't like to spend time in car, optimal timing gives advantage.

## How is it used?

User gives start and end points and time window when travelling. Application takes historical data from trafic volumes sorted according to date and time and current volumes and predicts how traffic is developing giving user optimal time to leave and which route should be taken if users has applied multiple favorite route. 

## Data sources and AI methods
https://www.digitraffic.fi offer REST/JSON interface to get traffic volumes and average speeds. Combined with Ilmantietoonlaitos open weather data interface AI can be teached to predict data. Since it offers lot of historical data, there is lot of training data available, even from time before Corona affected traffic volumes. Since new data it constantly coming in, lot of test data is also available.

## Challenges

It does not give optimal route at least in the first version. Taking into account major events will make predicting much harder than using regular weekday / holiday and working hours approach. Since user is giving start and end points, they could be used to track and identify users.

## What next?

Next step would be planning optimal routing and even longer trips, for example going to store for 30 minutes and continuing.

