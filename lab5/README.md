Task 1
One new engineered feature I created is called FamilySize. This feature represents the total number of family members traveling with the passenger. It is calculated by adding SibSp and Parch and then adding one to include the passenger. I believe this feature can help predict survival because passengers traveling with family members may have had more support during the evacuation compared to passengers traveling alone. Family groups might also have tried to stay together, which could influence survival chances.

Task 2
I tried a different rule for the IsAlone feature. Instead of defining a passenger as alone only when FamilySize equals 1, I tested a rule where passengers with FamilySize less than or equal to 2 were considered effectively alone. After retraining the model with this new rule, the accuracy changed slightly but not significantly. This suggests that family size does have some influence on survival, but small adjustments to the rule do not dramatically change the model’s performance.

Task 3
I experimented with changing the value of top_k when reducing the categories of the Title feature extracted from the passenger name. For example, I tested values such as 3, 5, and 10. When top_k was small, many rare titles were grouped into the “Other” category, which simplified the feature but removed some detailed information. When top_k was larger, more title categories were kept in the dataset. The accuracy changed slightly between these settings, but the most important features remained similar.

Task 4
I also ran the optional feature selection step using the Random Forest model. This process removes features that have low importance and keeps the most useful ones for prediction. In my case, the performance of the model stayed almost the same after feature selection. This indicates that some features were not very important for the model, and removing them did not negatively affect the results.