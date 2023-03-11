<h1>Predicting Satisfaction of Airline Passengers with Decision Tree & Random Forest Classification.</h1>
<br><br>
Project Overview:<br>
<ul>
  <li>This is a project for satisfaction prediction of passengers.</li>
  <li>The dataset used is <b>"Airline Passenger Satisfaction"</b> from Kaggle.</li>
  <li>Dataset containes <b>120000+</b> records.</li>
  <li>Steps performed:
    <ul>
      <li>Importing necessary libraries.</li>
      <li>Loading dataset.</li>
      <li>Exploratory data analysis</li>
      <li>Data cleansing</li>
      <li>Data preparation</li>
      <li>Model preparation</li>
      <li>Model training</li>
      <li>Prediction and testing</li>
    </ul></li>
  <li>Plot for feature importance for each model is shown.</li>
</ul>

![image](https://user-images.githubusercontent.com/72664379/183853302-652caa80-f3e7-4e9a-afc0-1973a80e607b.png) <br>
This is a pie chart showing the distribution of satisfied vs neutral_dissatisfied passengers. <br><br>



![image](https://user-images.githubusercontent.com/72664379/183853403-8af2828a-d877-40f4-a8e5-b52f12f4e89e.png) <br>
This is a bar graph showing the distribution of "Type of Travel" vs "Class of Travel". <br><br>



![image](https://user-images.githubusercontent.com/72664379/183853510-b044a1f5-149e-49f9-a0e6-01d544165227.png) <br>
This plot shows the significance of all the independent features in predicting the satisfaction of a passenger for decison tree classifier model. <br><br>



![image](https://user-images.githubusercontent.com/72664379/183853563-18cb411f-2589-489b-9a64-a963f45937fe.png) <br>
This plot shows the significance of all the independent features in predicting the satisfaction of a passenger for random forest classifier model. <br><br>
<br>
Accuracies achieved:
<ul>
  <li>Decision Tree Classifier:
    <ul>
      <li>Training: <b>100%</b></li>
      <li>Testing: <b>94%</b></li>
    </ul>
  </li>
  <li>Random Forest Classifier:
    <ul>
      <li>Training: <b>99%</b></li>
      <li>Testing: <b>96%</b></li>
    </ul> 
  </li>
</ul>

<h3>Conclusions</h3>
<ul>
<li>We can conclude that the independent feature "Online Boarding" has the greatest significance in predicting the passenger satisfaction.</li>
<li>"In-flight Wifi Service", "Type of Travel", "Class" also play efficient role in the prediction.</li>
<li>"Gender" of the passenger has the least significance in the prediction.</li>
</ul>
