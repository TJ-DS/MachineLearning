# MachineLearningUsingPython
![images.png](image/ML1.png)<br><br>
![images.png](image/ML2.png)<br><br>

Machine Learning is a latest buzzword floating around. It desrves to, as it is one of the most interesting subfield of Computer Science.
What does Machine Learning really means?
Machine Learning is an application of artificial intelligence(AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed.
Machine Learning focuses on the development of computer programs that can access data and use it to learn for themsleves.
The process of learning begins with data, such as, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly. 

__Data Science Goals and Deliverables__

		Prediction (predict a value based on inputs)
		Classification (e.g., spam or not spam)
		Recommendations (e.g., Amazon and Netflix recommendations)
		Pattern detection and grouping (e.g., classification without known classes)
		Anomaly detection (e.g., fraud detection)
		Recognition (image, text, audio, video, facial, …)
		Actionable insights (via dashboards, reports, visualizations, …)
		Automated processes and decision-making (e.g., credit card approval)
		Scoring and ranking (e.g., FICO score)
		Segmentation (e.g., demographic-based marketing)
		Optimization (e.g., risk management)
		Forecasts (e.g., sales and revenue)

Each of these is intended to address a specific goal and/or solve a specific problem. The real question is which goal, and whose goal is it?

For example, a data scientist may think that his goal is to create a high performing prediction engine. The business that plans to utilize the prediction engine, on the other hand, may have the goal of increasing revenue, which can be achieved by using this prediction engine.

__The Data Science Process__

	Data acquisition, collection, and storage
	Discovery and goal identification (ask the right questions)
	Access, ingest, and integrate data
	Processing and cleaning data (munging/wrangling)
	Initial data investigation and exploratory data analysis (EDA)
	Choosing one or more potential models and algorithms
	Apply data science methods and techniques (e.g., machine learning, statistical modeling, artificial intelligence, …)
	Measuring and improving results (validation and tuning)
	Delivering, communicating, and/or presenting final results
	Business decisions and/or changes are made based on the results
	Repeat the process to solve a new problem 
	Here is a diagram representing a simpler version of this process.

__Sub-Field Of Data Science__

	Exploratory Data Analyisis
	Machine Learning
	
__Examples__
1.	Whenever traffic on the road then do not cross the road. So basically if you got hit by bike while crossing and your age was 6 or 5-year-old. Hence now you become older and safely you can say that when you have to cross the road.  So last many year, you brain were learning, when you should cross the road, when light is green. So brain learn from experience, so that is called about machine learning.
2.	ML is writing algo/formula in such a way that it learns from Data itself rather that you tell to data what has to do.
3.	Whenever you want to cross the road, you are not thinking that, right side you have 11 cars and left side 2, so you have to cross. No brain automatically will start calculating biased on earlier experience and start making judgment.
4.	Learning from data, learning from past experience that is all about machine learning 

__Common terms used:__

_Labelled data:_ It consists of a set of data, an example would include all the labelled cats or dogs images in a folder, all the prices of the house based on size etc.

_Classification:_ Separating into groups having definite values Eg. 0 or 1, cat or dog or orange etc.

_Regression:_ Estimating the most probable values or relationship among variables. Eg. estimation of the price of the house based on size.

_Association:_ Discovering interesting relations between variables in large databases where the connection found is crucial.

# Types of Machine Learning Algorithms 

![images.png](image/ML_Types.png)

    Supervised learning
    Unsupervised Learning
    Semi-supervised Learning
    Reinforcement Learning
    
# Supervised learning

    Bookies Definition :

A model is prepared through a training process in which it is required to make predictions and is corrected when those predictions are wrong. The training process continues until the model achieves a desired level of accuracy on the training data.

    My Understanding :

Class student has mathematics subject, and you are identify with their marks.

    •	Greater than 75%  Good 
    •	Between 40 – 75%   Average 
    •	Less than 40%    Poor Student 
    
Hence We are doing classified our data, So whenever new data comes in the class, and his score is 99, I should classified in Good. This is called as classification ML algo.
Supervised learning algorithm are once in which Dependent variable is giving into data.
Let’s understand with below examples.

|Student Name |Roll No. |Height|father occupation |Math Score |Student_Stregth |
|---|---|---|---|---|---|
||||||

Dependent variable is totally Dependent question which you are going to asking.
- 	What is going to be salary next month  Salary is going Dependent.
        o	No. hours work in a day in office
        o	Year of experience.
        o	Performance Salary 
-  What category Student belong to   category is going Dependent.
- 	What is going to be father occupation of Student  father occupation is going Dependent.<br>
Whenever you ask something in ML is going be __Dependent__ variable.
You will be ahving only one __Dependent__ variable and others will be independent.

ML is design such way that has only dependent variable, ML can able to answer one question at a time.<br> 
__Question__ What can be salary and medical benefit, this is totally wrong .

|Name |Exp. |Performance| Age  |Salary |Category |
|---|---|---|---|---|---|
||||||

Based on above data, someone is going to ask what is salary of next month, Then Salary is going to be dependent and value will be numeric, Hence its __Regression.__

But when someone is going to ask, this boy has recently joined and math marks is 90 so what is category. So this is going to be __classification,__ hence dependent variable is Math marks. 


# Unsupervised 

    Bookies Definition :
A model is prepared by deducing structures present in the input data. This may be to extract general rules. It may be through a mathematical process to systematically reduce redundancy, or it may be to organize data by similarity.

    My Understanding :
Which has no label, you don’t have any question to ask. All are independent variable.
_Example:_ Lets Amazon and Filpkart data.
What they are doing, based on data which they collected, they will analysis and found pattern, this age group are taking this product and based on that they will give coupon/discount.
_Example:_ Bread and butter always together.

__Association: (Behavior of things)__

        Super market
            Vegetable together 
            
Association tells you what product is highly _co-related or associate_ each other. That means one is bought second mostly product is also bought. From historical data whenever person is buying bread it will also buy butter, those two product is highly associated and co-related.

__Training and Testing__
I have 1000 rows of data of company, labeled data. So i will trained data 800 records with labeled data, make algorithm learn from data. and using that you will predict rest of 200 records and you have 200 actual labeled data.
Hence you will compare predict and actual data.

_Example : How machine will predict, Example: Temperature and Ice Cream_

__Reinforcement Learning__
examples

    Baby  
    Automate car
	Learning with Trying and hit 
    
__Instance Based Learning(cluster) – Model based learning (Supervised learning)__
Instance based Learning --> Whenever new data come it will predict based on previous data and decide this is belong to Bajaj bike, Honda bike. When new thing come you will see similarity and cluster it together.  

