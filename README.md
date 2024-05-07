Introduction
The project is consisting of number of algorithm. To do the project, I have used the python pandas, numpy and sklearn within different algorithms such as k means clustering, Logistic regression, Linear Regression and neural networking. 
The data set I have used for this project is downloaded from kaggle.com. The data set contains the information about vehicle accidents in Canada within the year 20-year period.

DataSet 
To start with the project, I was looking for something unique. So, after looking at number of different data sets from kaggle.com, finally I found one interesting data set which is based on the car accidents in Canada from 1994-2014. The data set is consisting is number of different aspects, which are as following:
Year of accident with time, month, day of week, number of vehicles involved, road condition, type of vehicle, model and year of the vehicle, number of people involved in the accident, weather condition, person sex, age, position and medical treatment required.

Project Planning
To start the project, I used the weather condition and number of vehicles involved in the accident. The main reason for looking at these statistics was as we are trying to see the number of accidents we are watching in daily life. So, I wanted to know what kind of vehicles that are and how the weather conditions are affecting them and causing a number of people to die and go to hospital. 
For K means clustering, I have used the weather condition with the number of vehicles involved in the crash.
For Logistic Regression, I have used the number of vehicles, weather condition and for a predictor is person age.
For Linear Regression, I have used weather conditions with the number of vehicles involved in the crash and divided the data into test and training data. .
For neural networking, I have used a different approach which I have explained in the neural network part.




Clustering
For this project the data set I used is big. It consists of 1,048,575 rows. For clustering, I used the two rows named C_VEHS and C_WTHR. The C_WTHR consists of 1-10 types of codes that are kind of types of weather when the collision occurred. In the beginning, I scaled both data frames and created the scatter plot to just see C_VEHS vs C_WTHR. 
After this, I used the same approach that I did in the class lab. I used 2 and 3 numbers of clusters and compared the results and created the scatter plots. I used inertia to sum the closet cluster samples in the set. The results were surprising and it was approximately 347003, which means the clusters were far away because of the big data set. Whereas, in the lab activity the data set was small, and the gap was just 19. I tried with a number of other rows from the data set and because of the large data set, I was still getting the big gap between clusters.

Logistic Regression
For this part, I used python pandas, numpy and sklearn. I divided the data set into training and testing data. The data was divided into half. After dividing the data into testing training, I fitted the model for logistic regression and got the coefficients for the data set that I used. My model consists of the number of vehicles, weather condition and the person's age.
Moving further, I tried the probability with different thresholds, with the increase in threshold, the accuracy of the model was decreasing. Which was affecting f-score, which I tried with micro and macro values.
In this model, I was trying to predict the age factor of the person with vehicle crash with the weather conditions.

Linear Regression 
The main reason for using this model was that I wanted to know how many vehicles got into accidents directly because of which kind of weather. So, I just used a single linear regression model.
This model consists of a number of vehicles and for a predictor I have used the condition of weather. After all this, again I divide the data set into training and testing data and fitted the linear regression model. 
When I created the scatter plot C_Wthr and C_vehs, I noticed that most of the collisions occurred from weather condition 2 and 3.




Neural Network  
In the neural networking, I just used year of Collison, number of vehicles, weather condition and age of the person into the data set. After fitting the model, I created the prediction using neural network, perceptron and logistic regression. The logistic regression was giving the full accuracy which was 1.0.
 
Problems Encountered during the project
The main problem that I was facing in the project was with the data set because it was too big and while compiling every part of the project it was taking too long and giving a number of errors. Moving along, the most interesting part was logistic regression because the results were interesting that I never expected, and It was the most difficult part too because I was having hard time to fit the model, because the data set was I was trying random number of columns for the prediction and trying to get some unique results. 
The second problem that I encountered was with the neural network because I was trying to implement different layers for every model and I was having a hard time with dummy variables. In the end, I was able to figure out everything.

Conclusion 
Overall, the project gives me deep knowledge of clustering, regression and neural networks. The most interesting fact about the project was the results because on the flip side, I was running the small data set with some different data set and the results that I was getting were also so different. The fact that I loved during this project was that I was able to find a number of interesting facts about the accidents that occur in Canada, I was able to figure them out according to the vehicle and the weather. Because the weather and age of the driver plays a crucial role for driving. 
