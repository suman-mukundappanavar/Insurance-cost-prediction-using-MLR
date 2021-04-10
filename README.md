# multiple-linear-regression

<h1> Step 1 </h1>
<p> Importing the required packages. <br> If you are have never used any of the packages before then you need to install it. </p> 
<p> Command for installing the pakages is [Cmd Command] <br> 
  <i> pip3 install 'package name' </i>
<h1> Step 2 </h2> 
<p> Once the packages are installed we need to read the data file. <br> Ensure that the dataset file (with extension .csv) is present is same folder. </p> 

<h1> Step 3</h1> 
<p> Check if any null values are present in the dataset. </p> 
<p> Here in my case no null values are present </p> 

<h1> Step 4 </h1> 
<p> Then extract X and Y values </p> 

<h1> Step 5 </h1> 
<p> We have string values in the data set and ML algorithm cant handle string values hence we need to convert them to numerical value. This is done using OneHotEncoder. 
  
  <h1> Step 6 </h1> 
  <p> Then we split the dataset into test set and traning set </p> 
  
  <h1> step 7 </h1> 
  <p> We pass the dataset to linear regression model and train it. <br> Later we test it with test set</p> 
  
  <p> Here in our example we got an accuracy of 79.9% which is not bad!! </p> 
  
  <h1> step 8 </h1> 
  <p> We can visualize the results using matplotlib.pyplot library. </p> 
