# MachineLearningKeplerSpace

This work involves downloading telescope data which was used to determine if other planets existed in the universe.  I then applied ML to it to determine the accuracy of the results.

The data itself was downloaded from Kaggle and is a bit opaque, with a number of the columns things which I didn't understand.  Frankly, I wish there was a different dataset we had access to for this exercise.  Not knowing the data makes me nervous about the results.

After importing the data into pandas, some data cleanup took place, dropping some columns and deleting rows with all null values.  Next I divided the data into training and testing sets, then scaled the X-values.  

I proceeded to select two different models to run the data on.  THe first was a basic logistic regression model.  I also chose to use a Sequential neural network.  I then trained both models and evaluated the test data.  

The results were incredibly accurate, to the point where I believe the data to be almost too clean.  The logistic regression had an accuracy ratee of .994 and the neural network .993.  Both of these numbers are simply too high.  

While this exercise was a good test of using machine learning, I would like to further work on my skills using datasets which aren't as clean.
