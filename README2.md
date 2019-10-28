# Pima Indians Diabetes Dataset

The Pima Indians Diabetes dataset contains 768 records from females over the age of 21 who are of Pima Indian decent. It contains 8 variables containing medical/health information from each person and also containes one outcome variable of whether or not the person has diabetes. It was collected with the objective to create a machine learning algorithm to forecast onset diabetes. With this assignmet we will prepare the data for a similar objective.

## Variables

Variables inlude:
- pregnant: number of times pregnant
- pressure: diabolic blood pressure (mm Hg)
- glucose: glucose concentration after 2 hours in an oral glucose tolerance test
- triceps: triceps skinfold thickness (mm)
- insulin: 2-Hour serum insulin level (mu U/ml)
- mass: body mass index (BMI)
- pedigree: diabetes pedigee function, indicating the liklihood of diabetes based upon family history
- age: age in years

## Question

Can we predict whether or not someone has diabetes based on the data in their health records?

This problem, given a binary target variable of whether or not someone has diabetes, seems like it lends itself to a classification problem. Our 8 predictor varaibles are all numeric type which also already helps for modeling, however the are many missing values within some of these varaibles making them possibly less relevant to the question at hand. Also, with a relatively small sample size and a genetically biased sample (since we are pooling data all from people with similar ancestry and heritage), findings may not be accurate in applying them to a population. But regardless we will look to prepare the data in a way allows for interesting findings and comparisons.
