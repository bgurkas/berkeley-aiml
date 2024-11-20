# Part 2
The prompt for Part 2 was "What Drives the Price of a Car?"

Details of the investigation can be found <a href="prompt_II.ipynb">here</a>.

# Non-technical Report of Findings
First, the data was visually inspected. Upon consideration of the available features, a select, relevant few were chosen to make predictions on. After an automated calculation of which features were most closely correlated with an increase in price, it was found that:
- The year that a car was built, 
- Whether it was a truck or a pickup, and 
- Whether it was manufactured by Ford or Ram 
were closely related to a direct increase in price. 

Conversely, the features that correlated with a decrease in price were:
- The odometer reading, and
- Whether the car was a sedan.

With these relationships in mind, predictive models were built on the aforementioned factors that contributed to an increase in price. Among these, the one that directly correlated the Year of the car to its price made the best predictions. The second-best model was one that considered all non-numeric features about a car: the type, manufacturer, and title status.

With these observations, it can be concluded that:
- <mark>Year:</mark> A car's price tends to increase with how recently it was built. Then the price decreases for some older cars, but it increases again for cars that are considered "vintage" (built between the 1940s and 1970s)
- <mark>Type:</mark> Customers consider the type of a car when buying/selling, and certain types of cars (such as trucks or pickups) tend to be sold for higher.
- <mark>Manufacturer:</mark> Certain manufacturers make high-selling cars due to their prestige, durability, reputation, etc.
- <mark>Title Status:</mark> Whether the car has been bought/sold legally, and other matters related to the registration of the car are also considered by buyers.
- <mark>Odometer:</mark> The lower the odometer, the higher the price.
