# Flyzy Flight Cancellation

Business Objectives

The business objective of this project is to develop a reliable predictive model for flight cancellations to support Flyzy's mission of providing a smooth and hassle-free air travel experience. By accurately predicting flight cancellations, Flyzy can take proactive measures to minimize disruptions for their customers and improve overall operational efficiency for partner airlines. This predictive model will enable Flyzy to:

1. Enhance Customer Satisfaction: By predicting flight cancellations in advance, Flyzy can notify customers promptly, enabling them to make alternative travel arrangements. This proactive communication will lead to improved customer satisfaction and loyalty.

2. Optimize Operational Efficiency: Airlines can take preventive actions, such as adjusting flight schedules, assigning alternative aircraft, and reallocating crew resources, based on the predictions. This optimization will reduce operational disruptions and costs.

3. Improve Business Reputation: By effectively managing and minimizing flight cancellations, Flyzy and its partner airlines can build a reputation for reliability and punctuality, attracting more customers and business opportunities.

4. Increase Profitability: Minimizing flight cancellations will lead to increased revenue generation as flights will operate more efficiently, reducing revenue losses due to

cancellations and missed opportunities.

Overall, the successful implementation of this predictive model aligns with Flyzy's vision of redefining the future of air travel through a personalized and connected experience, improving customer satisfaction, operational efficiency, and overall business success.

Problem Statement

Flyzy is a company focused on providing a smooth and hassle-free air travel experience. They offer personalized in-flight and airport recommendations, and they also provide real-time flight tracking, mobile check-in, and more. Flyzy aims to redefine the future of air travel with a more personalized and connected experience from the beginning of the trip to the end.

Flight cancellation is a significant issue in the aviation industry. It not only disrupts the customers' plans but also impacts the airlines' reputation and profitability. Therefore, predicting flight cancellations can help airlines take preventive measures and minimize disruptions.

Dataset

The dataset you will be using is a dataset of flight cancellations. It contains the following columns:



Flight_ID (Numeric): This is a unique identifier for each flight. The values are randomly generated and have no particular meaning. This column will not be used in the analysis and modeling, as it does not contain any useful information.



Airline (Categorical): This column represents the airline that operates the flight. It is a categorical variable with five different airlines. Each airline has a different reputation and operational efficiency, which might affect the likelihood of flight cancellations.



Flight_Distance (Numeric): This column represents the distance of the flight in kilometers. The values have been scaled to have a mean of 0 and a standard deviation of 1. Longer flights might have a higher chance of cancellation due to more complex logistics and higher chances of

encountering issues.



Origin_Airport and Destination_Airport (Categorical): These columns represent the airport from where the flight departs and the airport to which the flight arrives, respectively. They are categorical variables with five different airports each. Some airports might have a higher chance of flight cancellations due to factors like weather conditions, operational efficiency, and local regulations.



Scheduled_Departure_Time (Numeric): This column represents the time when the flight is scheduled to depart. The time is represented as the number of minutes past midnight. The departure time might affect the likelihood of flight cancellations. For example, flights scheduled to depart late at night might have a higher chance of cancellation due to less operational staff or

unfavorable weather conditions.



Day_of_Week (Numeric): This column represents the day of the week when the flight is scheduled. The days are represented as numbers from 1 (Monday) to 7 (Sunday). The day of the week might affect the likelihood of flight cancellations. For example, flights scheduled on

weekends might have a higher chance of cancellation due to higher passenger load.



Month (Numeric): This column represents the month when the flight is scheduled. The months are represented as numbers from 1 (January) to 12 (December). The month might affect the likelihood of flight cancellations. For example, flights scheduled in winter months might have a higher chance of cancellation due to bad weather conditions.



Airplane_Type (Categorical): This column represents the model or type of the airplane. It is a categorical variable with five different airplane types. Some airplane types might have a higher chance of flight cancellations due to factors like age, maintenance issues, and fuel efficiency.



Weather_Score (Numeric): This column represents a score of the severity of the weather conditions, with higher scores indicating worse weather. Bad weather is one of the most common reasons for flight cancellations.



Previous_Flight_Delay_Minutes (Numeric): This column represents the delay of the previous flight by the same airplane in minutes. If the previous flight was delayed, it might affect the current flight's schedule and lead to its cancellation.



Airline_Rating (Numeric): This column represents a score of the quality or reputation of the airline, with higher scores indicating better airlines.Better-rated airlines might have lower chances of flight cancellations due to higher operational efficiency and customer service.



Passenger_Load (Numeric): This column represents the load or capacity utilization of the flight, represented as a percentage. Flights with a higher passenger load might have a lower chance of cancellation, as airlines want to avoid inconveniencing a large number of passengers.



Flight_Cancelled (Binary): This is the target variable, represented as a binary variable where '1' means the flight was cancelled and '0' means it was not cancelled. The flight cancellations are based on various factors and some randomness.
