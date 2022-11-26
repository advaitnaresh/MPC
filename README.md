# MPC 

This is a Readme file for the Project under Professor Amit Setia. 
The title for the project is Model Predictive Control in Robotics.

By using Model Predictive Control one can accurately predict the next most optimised step to take in order to reach your destination faster. 
This is done by predicting from a large number of predictions based on our control horizon and choosing the first most optimised prediction and following the same
for the other predictions. 

This concept is currently being used in chemical plants , with a large number of applications in autonomous vehicals , obstacle avoidance etc.

# Results

![image](https://user-images.githubusercontent.com/94890363/204078094-972ae6ae-9683-4c65-b6b0-8c51960628e3.png)
 

This is a graphical illustration of the model that the most basic MPC controller gave us 

We had two start states , x0 = 10 and X1= 5 and our goal was to bring them to the origin as fast and in the most optimised way as possible.
We had our own set of control inputs which were predefined and our model worked past them by optimising the result till the end which can be seen in the figure.
More about this can be read in the Uploaded PDF. 

# Multivariable Linear MPC

![image](https://user-images.githubusercontent.com/94890363/204093927-9c9df760-823d-4871-b293-52371e5130e4.png)

This is a graphical illustration of the 3 state model of the same Linear MPC controller. 
Here we have 3 state variables namely , x0=10 , x1=5 , x2=2 . 
These all start at the given initial points and try to converge towards the origin( which is our target destination) following the control parameters defined by u.
