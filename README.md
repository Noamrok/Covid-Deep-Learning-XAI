# An Explainable Machine Learning Model for Predicting the Severity Level of COVID-19 Diagnosed Patient

I’m conducting an academic research, as part of my final degree project, on the capability of Deep Neural Networks to predict the connection between underlying medical conditions and Covid-19’s risk factors. 
I’m implementing deep neural networks models with Keras API and then explaining their predictions using LIME.

Because medical records are classified, I took a dataset from Mexico but it was baised and incomplete.
I built two models: one which distinguish between three severity levels and one with two severity levels.

These are the DNNs:

![image](https://user-images.githubusercontent.com/53267157/126466512-81225294-8873-496d-8321-513af73e3ff4.png)

Confusion matrix:

![image](https://user-images.githubusercontent.com/53267157/126469543-11d230be-7173-4a06-910e-07635b44b53e.png)
![image](https://user-images.githubusercontent.com/53267157/126469558-d0f70ef6-117a-40ee-a356-cc4ba2b89d33.png)

XAI:

![image](https://user-images.githubusercontent.com/53267157/126469626-90a18d4a-66df-4817-891f-4c1a162d4dd2.png)
![image](https://user-images.githubusercontent.com/53267157/126469631-22c4741c-66cf-41e1-83eb-3f1e4afed82d.png)
![image](https://user-images.githubusercontent.com/53267157/126469649-436c55c5-87b1-4a6d-bb34-e71d0e9c747c.png)
