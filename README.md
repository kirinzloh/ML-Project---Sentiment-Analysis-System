# ML-Project --- Sentiment Analysis System

Many start-up companies are interested in developing automated systems for analyzing sentiment information associated with social media data. Such sentiment information can be used for making important decisions such as making product recommendations, predicting social stance and forecasting financial market trends. 

The idea behind sentiment analysis is to analyze the natural language texts typed, shared and read by users through services such as Twitter and Weibo and analyze such texts to infer the users’ sentiment information towards certain targets. Such social texts can be different from standard texts that appear, for example, on news articles. They are often very informal, and can be very noisy. It is very essential to build machine learning systems that can automatically analyze and comprehend the underlying sentiment information associated with such informal texts. 

In this design project, we would like to design our sequence labelling model for informal texts using the hidden Markov model (HMM) that we have learned in class. In particular, we are working on building a sentiment analysis system for tweets on Twitter. 

For the challenge: improving the sentiment analysis system, we also used Conditional Random Fields (CRF) as an alternative approach to design the system.


### Requirements
  - Python 3.6 and above (previous Python 3 versions might work - not tested)
  - Codes are in jupyter notebook format


### Data
The labelled data that we are handling has the format of one token per line with token and tag separated by tab and a single empty line that separates sentences. 

For the EN dataset, the format can be something like the following:

Best O 

Deal O 

Chiang B-positive 

mai I-positive 

Tours I-positive , O


### Scripts
The source codes are easy to work with, for all the parts, simply run the kernel in the jupyter notebook.

The notebook contains all relevant and required information to understand the codes.

The output files are in their individual folders in /Scripts.

- EN/ 
1. dev.p2.out 
2. dev.p3.out 
3. dev.p4.out 
4. dev.p5.out 
- FR/ 
1. dev.p2.out 
2. dev.p3.out 
3. dev.p4.out 
4. dev.p5.out 
- CN/
1. dev.p2.out
2. dev.p3.out
- SG/
1. dev.p2.out
2. dev.p3.out
- test/
  - EN/
  1. dev.p5.out
  - FR/
  1. dev.p5.out

### Contributors
Loh Wei Quan, Bryan Phua
