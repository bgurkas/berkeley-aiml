# Part 1

The prompt for Part 1 was "Will the Customer Accept the Coupon?". 

From the project writeup: This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver.

Upon investigation of the dataset's features, it was discovered that factors such as visit frequency, age, income, distance to the venue offering the coupon, and the original destination of the driver have an effect on whether the driver will accept the coupon offered to them.

Details of the investigation can be found <a href="part1/prompt.ipynb">here</a>.

# Findings
The Question: What are the characteristics of drivers who received coupons for cheap restaurants? To gauge these characteristics, I looked into the income level, distance, and destination.

## Income Level
I decided to look into the income level because I thought that people receiving coupons for cheap restaurants might be frequenting these venues on their own time since they cannot afford to dine at expensive restaurants.

I used an overlapping bar chart to compare the number of accepted coupons to all given coupons, grouped by income level.

The highest acceptances occurred for people whose incomes fell between 
62,500. This fell in line with my initial assumption. However, there was also a high acceptance rate for people who had an income of $100,000 or more. I was surprised to see this, since it seemed like outlying data compared to the section of income that supported my assumption. I didn't assume that people with a high income would still be willing to dine at cheap restaurants.

## Distance
I decided to look into the correlation between distance and acceptance, since I assumed that people would be less likely to accept a coupon if it was too far away.

I computed the number of acceptances for each of the distance features provided within the dataset.

In line with my assumption, distance and acceptance have an inverse relationship. The number of acceptances decreases as the distance increases.

## Destination
I decided to look into the destination of the drivers since the urgency of their drive could affect whether they are willing to take a detour.

I used a pie chart to demonstrate the size of each destination category in relation to the others.

The most acceptances occurred when drivers had no urgent destination. The least acceptances occurred when drivers were headed home. This could be attributed to a number of different factors. Perhaps they already had food at home or were on their way to make some, or they were too tired to eat outside and just wanted to get home. This is an aspect of the data that we cannot prove with the data that we have.
