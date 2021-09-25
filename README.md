# Movie-Collection-Prediction---ANN
--------------------------------------------------------
Dataset contains data of movies, where our task is to predict the collection (revenue) the movie is going to make using variables such as expense, rating genre, etc.
--------------------------------------------------------
Steps Involved ---->
 -  Import ‘Movie_collection’ csv files in data_x and data_y variables.
 -  Look at the shape and first five rows of both dataframes to understand the data
 -  Split the data into test, train, and validation
 -  Take a look at the shape of the test, train, and validation set
 -  Standardize the data
 -  Create an ANN model with 2 dense layers of 30 neurons each
 -  Compile the model with loss="mean_squared_error", optimizer=keras.optimizers.SGD(lr=1e-2) and metrics=['mae'])
 -  Train the model for 100 epochs
 -  Evaluate the model performance on the test set
 -  Predict the values of the first 5 test records

![image](https://user-images.githubusercontent.com/68370376/134771526-0d7ff0e2-8c5d-4f79-bbf1-7b3f1f3e0a7f.png)

![image](https://user-images.githubusercontent.com/68370376/134771540-70ee344e-4131-45e5-908f-5248fc6e1b61.png)

![image](https://user-images.githubusercontent.com/68370376/134771563-ee96aa30-daa8-444c-8899-40aa96618aac.png)

![image](https://user-images.githubusercontent.com/68370376/134771586-eb1c58ea-e726-44e0-ba7c-10755039ab70.png)

![image](https://user-images.githubusercontent.com/68370376/134771610-603b62e0-c46a-42d9-838e-465018a49514.png)

![image](https://user-images.githubusercontent.com/68370376/134771639-a492cb03-a347-4e6f-b4cb-9daa6b6db1ae.png)

