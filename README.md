Mobile Price Classification using Machine Learning

This project involves building a classification model to predict the price range of mobile phones based on various specifications such as battery power, RAM, camera quality, and connectivity.

About the Project

In a highly competitive mobile phone market, companies need to understand the relationship between hardware features and price points. This project implements a Multiclass Classification model that categorizes mobile phones into four price ranges (0: Low Cost, 1: Medium Cost, 2: High Cost, 3: Very High Cost).

The dataset used in this project is the Mobile Price Classification dataset from Kaggle. It contains 2,000 samples with 21 features (20 input features and 1 target variable).https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

Key Features include:
battery_power: Total energy a battery can store in one time measured in mAh
blue: Has bluetooth or not
clock_speed: speed at which microprocessor executes instructions
dual_sim: Has dual sim support or not
fc: Front Camera mega pixels
four_g: Has 4G or not
int_memory: Internal Memory in Gigabytes
m_dep: Mobile Depth in cm
mobile_wt: Weight of mobile phone
n_cores: Number of cores of processor
pc: Primary Camera mega pixels
px_height: Pixel Resolution Height
px_width: Pixel Resolution Width
ram: Random Access Memory in Megabytes
sc_h: Screen Height of mobile in cm
sc_w: Screen Width of mobile in cm
talk_time: longest time that a single battery charge will last
three_g: Has 3G or not
touch_screen: Has touch screen or not
wifi: Has wifi or not


Language: Python

Libraries:
pandas & numpy (Data Manipulation)
matplotlib & seaborn (Data Visualization)
scikit-learn (Model Building & Evaluation)

Methodology
Exploratory Data Analysis (EDA): Visualizing correlations between features like RAM and Price Range.
Data Preprocessing: Checking for missing values and scaling features.
Model Selection: Implementing algorithms like Logistic Regression, Random Forest, or SVM.
Evaluation: Assessing performance using Accuracy Score and Confusion Matrix.


Author: Aung Ko Min

