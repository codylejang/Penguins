# Penguin species prediction
Group members Cody Lejang, Megan Tieu, and Arely Perez, collaborated on data acquisition, preparation, and use of several models to analyze penguin features and classify them into species.
## Frameworks
We used penguin data from "https://philchodrow.github.io/PIC16A/datasets/palmer_penguins.csv", along with python libraries, such as matplotlib, scikit-learn, and pandas.
## Conclusions
We decided to use the Culmen Length vs. Culmen Depth relationship to generate a species predicting model. The features were selected through analysis of measures of center and overall trends in the dataset. This relationship had a clear distinction, in terms of spread, between each of the species. The body mass vs. species relationship was not selected because there was too little of a difference in body mass across each of the species. In the final figure involving species vs culmen depth with sex as a qualitative variable, it was determined that the center of the Adelie and the Chinstrap penguins are too similar. Consequently, this relationship would be a poor choice for predicting species.
All machine learning models have a high cross value score and therefore would be accurate predictors for species based on the two quantitative variables/features we selected.
