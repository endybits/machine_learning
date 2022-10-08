# MACHINE LEARNING AS A PART OF DATA SCIENCE

Nowadays, Data Science has become a too robust IT topic for one person. Well, its core is made up of several components that complement each other, to achieve incredible solutions and results to almost any area of academic, business or social field.

In this sense, Machine Learning makes its significant contribution to Data Science, making it easier to solve complex problems with data-driven prediction and automation processes techniques.

Maybe you have a question about the scope of the Machine Learning component in Data Science. Keep calm, a diagram will solve it.

![Data Scicence methodology representation](https://github.com/endybits/machine_learning/blob/main/regression/asset/ML_and_Ds_model.png)

## The Data Science Methodology

In the image above, I try to simplify the methodology proposed by IBM, because the idea that brings us together is to deepen the role of Machine Learning in the Data Science process.

However, I’ll try to make a minimum approximation to each component:

#### Ask the right question:
The aim is to find the question that will guide the whole process. This question should be carefully iterated, discussed and agreed upon between the IT team and the stakeholders; those who seek to solve the problem.

#### Data component:
In this componente, the team takes responsibility for ensuring the data is accurate and able to solve the given question.
To achieve this, some underlying stages are provided.
- List required data.
- Collect the data: go get the data where it is. If it doesn’t exist, create it.
- Selection of features and target variables.
- Data cleaning and preparation
- Data visualization: identify hidden patterns and provide insights.
- Data segmentation for training and testing.

It’s important to note that in some cases It is necessary to go back to the previous steps to improve the data quality.

#### Machine learning component:
Before listing a step by step of this component, It’s important to explain that Machine Learning is the piece that brings Artificial Intelligence to life (As a song is to music or a poem is to poetry).

Artificial Intelligence went from being a utopia in the heads of some academics who conceived the idea that machines could simulate patterns of behavior similar to those of a human brain; to which we can easily explain today by evidencing that a machine, through a large volume of data, can identify patterns that lead it to predict behaviors, forecast the weather, identify objects, translate texts, recognize faces and drive themselves.


Now, let’s talk a little bit about its role in Data Science. Machine learning team receives the previously processed data, and puts it through a series of internal steps within this componente, to get results as accurate as possible.
An ideal order could be as follows:

**Choose a training method:** In this step it is crucial to know about what the target is, because It will be the starting point to know if we will use a Regression, a Decision Tree, a Clustering nearest neighbor, among others. (Missing to link a real example to each model)

**Train the model:** Do you remember that in the previous component I told you about data segmentation? The largest percentage of data is used to train the model. That is, learn to identify the common patterns between data features and the target variable.

**Test the model:** Usually, the remaining data percentage is used to check if the model works correctly. This technique consists of testing the model with data that It has not yet seen, but that we know, so that It makes its predictions. An advantage in our favor is that we can measure the accuracy of the model’s prediction against the known data in the test segment.
:tada:*It's amazing!!!*:tada:

Before closing, It’s important to mention that when the accuracy of the prediction is too low, regarding the data test, It’s extremely necessary to re-thinking the model and, maybe change it, or even return to the previous components to identify possible causes and correct them. 

Finally, when the Machine Learning model has achieved a high level of accuracy, it is put into production in some service or application to respond in real time if an user is eligible for a home loan, how much the sales of a product will increase in relation to the marketing investment, What is the estimated salary to a new employee based on the education level and job experience, or any other question that no one has asked yet, and It’s inside your head waiting for your genius.