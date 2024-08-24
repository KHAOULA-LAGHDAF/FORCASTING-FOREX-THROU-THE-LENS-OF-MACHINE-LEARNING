# FORCASTING-FOREX-THROU-THE-LENS-OF-MACHINE-LEARNING
Making Trading easy, with machine learning predictions.


# Trading
is a term we've been hearing a lot lately, often associated with high risks. But what if there were an automated robot that could track market trends, buy and sell at the right time, and minimize risks as much as possible? This idea inspired was behind this exciting project.

DOES IT FEEL LIKE TRADING ISN’T YOUR THING? 
DOES IT LOOK LIKE IT’S A BIG RISK TO YOU AS A BEGINNER?
WHAT IF THERE WAS A WAY TO MINIMIZE THE RISKS ASSOCIATED WITH FOREX TRADING!
CAN YOU IMAGINE A TOOL THAT GUIDES YOU ON THE BEST TIMES TO BUY AND SELL CURRENCIES!!
WHAT IF I TOLD YOU THIS IS POSSIBLE USING MACHINE LEARNING MODELS!


Machine learning has indeed made trading easier, and it was demonstrated in this project. Let's take a look on the project structure: 
This project involved three main steps:

1️⃣Step 1: Understanding Trading

This journey started by learning the fundamentals of trading and how it works, the key details, and the principles of buying and selling. Several courses were completed to build a solid foundation.

![image](https://github.com/user-attachments/assets/b774f5af-fb42-4f7b-b3ce-65ed71ca93f9)


2️⃣Step 2: Creating a Machine Learning Model 

First thing was done was gathering real-time data from MetaTrader 5 (From IcMarket, which is the main broker) using specific commands. After processing and cleaning the data, the next step was choosing a ML approach, and it was using neural networks, specifically the Long Short-Term Memory (LSTM) algorithm. LSTM is particularly effective for sequential data, making it ideal for the project purposes. The model was trained, tested, and evaluated/optimized until we achieved the desired results.

![image](https://github.com/user-attachments/assets/6b9eed0f-4bc5-443c-91bf-ef27a454bb2d)


3️⃣Step 3: Deployment

The most challenging step was deployment. Using MQL5, a programming language for MetaTrader 5, the model was deployed into MT5, and it was integrated in the final trading strategy. The strategy focused the most on excuting actions BUY/SELL based on the model predictions. This allowed the robot to buy and sell based on real-time data and the results from our model.

![image](https://github.com/user-attachments/assets/9c4d670f-6f1c-4883-be17-c4e959f26109)


Now, with ONLY one click, the robot can start buying and selling using our trained model's results. And those are the Backtesting Results: 
![image](https://github.com/user-attachments/assets/a650a5ee-0e7e-4b72-9d61-75eb545a8796)
![image](https://github.com/user-attachments/assets/64443874-b3a6-4e25-8a69-8572b915bff2)

