# Statistical-Methods----Factorial-Experiment
Analyze sepal widths of three species of flowers using ANOVA

I.	Introduction: 
There are thousands of genera of flowering plants on earth today. And each genus may contain hundreds of species of flowering plants. However, different species of plants within the same genus can produce flowers with varying features like sepal length, sepal width, petal length and petal width. Any significant difference in these morphological features of flowers can help us in finding out their species (Fisher, R.A, 1936). Even though, the result might not deliver the specific origin, the measurement can help the scientists to bring the close relative from the variates in the same genus.
Based on this understanding, it is natural that one might want to know if there would be any significant differences in the dimensions of botanical parts of flowers produced different species of plants of a single genus. 

II.	Objective Statement: 
In this study, we want to analyze if there is any significant difference between mean values of sepal lengths, sepal widths, petal lengths and petal widths of flowers produced by three species of Iris plants called Setosa, Versicolor and Virginica.  

III.	Statistical Procedure: 
This study applies ANOVA to analyze the difference in mean dimensions of botanical parts of flowers based on Iris dataset collected by the Fisher, R.A, 1936. This study is designed as a one-way ANOVA and Tukey HSD would be performed to test all pair-wise comparisons in case of significant difference among sample means.

IV.	Data Description: 
The dataset used in this study is Iris Dataset from UCI Machine Learning repository. The dataset consists of 150 observations and 5 variables, and variables are namely Sepal Length, Sepal Width, Petal Length, Petal Width and Species.

V.	Discussion:
The results of ANOVA showed that among the three different species of plants within the Iris genus namely Setosa, Versicolor and Virginica, the mean sepal width of at least one species of flowers differ with the mean sepal widths of the other two species of flowers.

However, people would intuitively think that plant species within the same genus will produce flowers with equal sepal widths. But the Tukey test has confirmed that not only there are differences in sepal widths among the flowers of Setosa, Versicolor and Virginica but also that the observed differences are significant. 

VI.	Summary:
This study mainly sheds light on differences in dimensions of botanical parts of flowers produced by three different species of plants namely Setosa, Versicolor and Virginica. It begins by description and preprocessing of Iris dataset collected by Fisher,R.A. in the article "The use of multiple measurements in taxonomic problems".

The study then goes on to check what variables in the dataset satisfy the assumptions of ANOVA. Since only one variable - Sepal Width has met the required assumptions, one-way ANOVA was applied to test if there is any difference between mean Sepal Widths of flowers produced by Setosa, Versicolor and Virginica. 
