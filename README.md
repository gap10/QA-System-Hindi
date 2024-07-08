# Question Answering System for Hindi Language

# Abstract
This project aims to create an end-to-end application for Hindi language question answering system. In the past few years, there has been growth in the interest of researchers towards processing of Indian languages. India being a diverse country with thousands of languages with not much data, this task is difficult. A question answering system enables people to get general or domain specific knowledge faster, anywhere and anytime.

# Dataset Source
The dataset used in this project is taken form Kaggle.
https://www.kaggle.com/datasets/ramisaalam/squad-translated-to-hindi

# Dataset Description
The Stanford Question Answering Dataset (SQuAD) is a widely used reading comprehension dataset designed for training and evaluating question answering systems. 
For this project a Hindi translated version of SQuAD is used. 

Number of Instances: 4734
Number of Columns: 5

1. Context: This field contains the comprehension based on which the questions will be framed, and the answers will be taken.
2. Question: This field contains the question framed from the corresponding comprehension.
3. Answer start: This specifies the beginning of the answer text in the context.
4. Answer: This field contains the answer to the respective question taken from the context.
5. Language: This field mentions the language of the context, question and the answer.

# Sample data instance
The data looks like this,
![image](https://github.com/gap10/QA-System-Hindi/assets/61880360/b007e3ba-143f-412a-bacd-391cdc9405d3)



![image](https://github.com/gap10/QA-System-Hindi/assets/61880360/a79b9aa6-3104-42d3-9ad9-64ccab719646)
 


# Model
IndicBERT, DistilBERT

# Hyper parameters: 
![image](https://github.com/gap10/QA-System-Hindi/assets/61880360/e58c88dc-f08f-456d-aa6e-34d79fbc4b94)

# Overview
![image](https://github.com/gap10/QA-System-Hindi/assets/61880360/e93e897b-2ff9-4c9a-8338-b4f9eea780ab)
