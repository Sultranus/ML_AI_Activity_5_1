# ML_AI_Activity_5_1
This repository holds the Practical Application Assignment 5.1 which was assigned in the AI/ML Professional Certification course

This assignment considers, "will the customer accept the coupon?" After an analysis of the data, below are my findings:

## Cleaning the data
1. The "Car" data was uninformative. This column included almost all NaN values. This field was dropped due to being uninformative for the vast majority of the data set.
2. The "toCoupon_GEQ5min" contained only one value for all rows. This field was dropped due to being uninformative.
3. The "passangar" field was misspelled. This was renamed "passenger"
4. While other columns included a mix of numeric values, or non-numeric values that clearly implied a lesser-to-greater value, these were left as categorical values since the raw data was unknown and I didn't think it was wise, at this point, to convert these values to numeric when the actual values were unknown.

## Exploring the data
### Coupon Acceptance
The coupon acceptance rate for the entire data set was 56.84%.

As we can see from the bar plot below, coupon acceptance was greatest for Carryout and Cheap Restaurants.
![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/090644ed-6903-4def-a99c-bf789b91c341)

### Weather pattern
Throughout the study, most of the coupons were offered when the temperature was 80 degrees.
![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/476a728a-b392-4817-960e-88dfb16c126a)

## Investigating the Bar Coupons
In this section, we attempt to answer a few questions about customers who were offered a Bar coupon.

1. First, we created a dataset of only those customers who were offered a Bar coupon.
2. What proportion of bar coupons were accepted?
   The Bar coupon acceptance rate was 41.00%
3. Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more
   Those who go to the bar more than 3 times per month have a bar coupon acceptance rate of 77%
   Those who go to the bar 3 or less times per month have a bar coupon acceptance rate of 37%
   Those who go to the bar more than 3 times per month arre more than twice as likely to accept a bar coupon
   ![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/2f606fbd-8325-4084-b765-0d5a339e8d76)
4. Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?
   Those who go to the bar more than once a month and are over 25 have a bar coupon acceptance rate of 70%
   Others who were offered a bar coupon accepted 34% of the time
   Those who go to the bar more than once a month and are over 25 have a bar coupon acceptance rate twice as high as others who were offered a bar coupon
   ![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/11528494-6b01-48e5-a2be-413781882a46)
5. Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.
   Those who meet the specified criteria have a bar coupon acceptance rate of 72%
   Others who were offered a bar coupon accepted 38% of the time
   Those who meet the specified criteria have a significantly higher likelihood of accepting a bar coupon
   ![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/99e132c3-6dbf-413f-88bb-062b84c9a89b)
6. Compare the acceptance rates between those drivers who:
      go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
      go to bars more than once a month and are under the age of 30 OR
      go to cheap restaurants more than 4 times a month and income is less than 50K.
   acceptance rate of person 1 is 7.01%
   acceptance rate of person 2 is 8.07%
   acceptance rate of person 3 is 40.87%

## Independent Investigation - Investigating House Coupon Acceptance
1. Create a data set of customers who were offered a Coffee House coupon.
2. Calculate the acceptance of Coffee House coupons.
   The Coffee House coupon acceptance rate is 49.92%
3. It was identified that customers under 21 were more likely to accept a Coffee House coupon. As well, coupons that expired in 1 day, as opposed to 2 hours, were more likely to be accepted. Consider individuals under 21 who are offered a coupon that expires in 1 day as compared to others.
   As we can see below, individuals under 21 who were offered a 1 day coupon were 82% likely to accept the coupon as opposed everyone else, whos acceptance rate was 50%.
   ![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/43c85d7d-5baf-49db-a2fc-ad7f6598df7a)
4. What time of day are Coffee House coupons most likely to be accepted?
   As we can see from the chart below, 10AM is the most likely time for a Coffee House coupon to be accepted.
   Evenings show the lowest Coffee House acceptance rate.
   ![image](https://github.com/Sultranus/ML_AI_Activity_5_1/assets/64758981/f5a7f168-2d4a-4c46-8e0a-3f1066302141)



