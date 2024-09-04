# boombike_niha_patne
# PROBLEM STATEMENT: The objective is to analyze the factors on which the demand for these shared bikes depends and the demand for these bikes among the people after this ongoing quarantine situation ends. 

# SUMMARY:
## Technical Aspect -
1. The above model so far looks the best one of all, with no higher p-values which means all the rest of the variables are pretty significant.
2. The VIF of all variables is also less than equal to 5, which suggests no multicollinearity.
3. After feature selection, 0.81 R-squared value shows that, the best fit line explains the features perfectly.

## Assumptions while dropping a few variables -
1. temp_diff, temp - Reason behind keeping atemp is because a lot of people decide to take a bike ride based on their intuition of whether the weather will be good/bad. (basically to track customer decision pattern)

## Business Aspect
1. Weather-driven Marketing: Adjust marketing efforts based on weather forecasts. Promote bike rentals more aggressively on days when the "feels-like" temperature is comfortable, and offer weather-related promotions during uncomfortable weather conditions (e.g., rain, mist, strong winds).
2. Seasonal Campaigns: Address the drop in demand during spring by launching targeted campaigns to overcome weather-related hesitations. Promote summer and winter biking with special offers, particularly on working days.
3. Commuting Strategies: Focus on targeting regular commuters during working days and weekdays. Create subscription or loyalty programs tailored for daily users, especially those commuting to work.
