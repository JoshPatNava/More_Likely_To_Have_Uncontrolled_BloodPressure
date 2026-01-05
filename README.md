# More_Likely_To_Have_Uncontrolled_BloodPressure

## 🏥 Description
In this project I created a synthetic dataframe using numpy, and then transforming it so I am able to use it for logistical regression. Which this will be looking how common uncontrolled bloodpressure is in different groups. In order to find this I used the logistic regression model to esitmate the odds of it happening across different categories.

## 📖 What am I learning
- Generating a Synthetic Dataframe
- Creating an clinical outcome that can be used for analysis
- Use a logistic regression model(fit and interpret it)
- Changed the model coefficients into odds ratio and confidence intervals
- Using a forest plot to visualize the logistic regression

## 🔢 Data Description
This dataset is a synthetic set of 5,000 patients which each of the rows represents that patient.
The Data:
- **uncontrolled_bp**: Has uncontrolled blood pressure(Yes / No)
- **age_group**: Age categories (18–34, 35–49, 50–64, 65+)
- **sex**: Male or Female
- **bmi_category**: Normal, Overweight, or Obese
- **smoker**: Smoking status (Yes / No)
- **diabetes**: Has diabetes (Yes / No)

## 📈 Analysis Approach
1. Binary outcome variable for Uncontrolled BP was created for the logistic regression analysis
2. Use an adjusted logistic regression model was fit using the age groupm, sex, BMI category, smoking status, and diabetes as the predictors
3. Used the Models Coefficients that were exponentiated to obtain odd ratios with the 95% interval
4. Created a forest plot to visualize and highlight the results that were found.

## Summary 
This project is created with a synthetic data so there are some limiations to the realness behind these finding. The results would suggest that older age, obesity, and diabetes are associated with the higher odds of uncontrolled blood pressure. While the gender of a patient show very little association. 