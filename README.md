# Odor-Prediction
Using the dataset, determine the source of the odor as quickly as possible
Data Science Project: Gas Sensor Data for timely Prediction


Introduction
This document is an outline of the “Gas Sensor” data science project to familiarize students or employees with sensor data and practice building a prediction algorithm.


Context of data collection
A group of researchers placed 10 sensors (8 MOX sensors, 1 temperature sensor and 1 humidity sensor) in one of the researchers’ residence, recording the sensor levels for 2 years, trying to determine if the MOX sensors would detect the presence of odors in a room. The data has the recordings of 3 situations: 
    1) measurements of sensors before, during, and after the presence of a banana
    2) measurements of sensors before, during, and after the presence of wine
    3) measurements of sensors with no odors in the room (baseline)

For more information and for the dataset, here are important links:
Relevant paper: 
https://arxiv.org/pdf/1608.01719v1.pdf 
Dataset and description: https://archive.ics.uci.edu/ml/datasets/Gas+sensors+for+home+activity+monitoring


Objectives
Using the dataset available only, determine the source of the odor (banana, wine or background) as quickly as possible. Here are some steps to help develop this prediction model:
    • Understand and visualize the data 
    • Identify relevant data and features 
    • What will be the mechanics to detect the right odor as fast as possible?
        ◦ Question: Do you need to have all of the data to identify the odor?

Answering the following questions will help determine the structure of the model:
        ◦ What are the in-scope data?
        What are the input variables/features? 
        Which input variables are most helpful in predicting the type of odor? Alternatively, which input variables help predict the type of odor the fastest?
        What kind of predictive models should you use? Which one performs best?
        Should this model be implemented in real time, how long would it take for your model to correctly determine which odor is present?
        
