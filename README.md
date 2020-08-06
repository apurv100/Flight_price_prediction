# Flight Ticket Price Prediction
* Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. 
* Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.

<img src = "https://user-images.githubusercontent.com/39961205/56277175-7ff3a600-6121-11e9-85cc-64fc59ae44df.PNG" width = "600">

## Data Overview
Here each data point corresponds to trip of flight from one city to another.
* Airline: The name of the airline.

* Date_of_Journey: The date of the journey

* Source: The source from which the service begins.

* Destination: The destination where the service ends.

* Route: The route taken by the flight to reach the destination.

* Dep_Time: The time when the journey starts from the source.

* Arrival_Time: Time of arrival at the destination.

* Duration: Total duration of the flight.

* Total_Stops: Total stops between the source and destination.

* Additional_Info: Additional information about the flight

* Price(target): The price of the ticket

#### Type of Machine Learning task : 
It is an regression problem where given a set of features we need to predict the price of ticket from one city to another.

#### Performace Metric
Since it is an regression problem we will use Root Mean Squared error (RMSE) and R-squared as regression metric.
