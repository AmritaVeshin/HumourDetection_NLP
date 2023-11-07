# HUMOUR DETECTION USING NLP
Leveraging Natural Language Processing (NLP) techniques and advanced pre-trained transformer models such as BERT and XLNet to classify texts into humorous and non-humorous categories.

## CONTRIBUTORS:
1. Amrita Veshin
2. Atharva Vetal

## PROBLEM STATEMENT:
The field of Natural Language Processing (NLP) has experienced a notable surge in interest in the domain of humour detection, aiming to computationally discern the nuanced aspects of humour in text. This research addresses the multifaceted challenge of understanding and identifying humour in written content, centring around jokes. The ultimate goal of this study is to advance our comprehension of humour detection using NLP techniques and provide practical solutions for applications that require the recognition of humour in text.

## KEY OBJECTIVES:
1.	__Exploration of Humour in Text Data:__ The primary objective of this research is to delve into the distinctive characteristics of humour, encompassing elements like wordplay, punctuation ratio, and tag ratio, by conducting an Exploratory Data Analysis (EDA) on a dataset of textual content classified as either humorous (jokes) or non-humorous (plain text).
2.	__Feature Engineering for Humour Identification:__ The study aims to develop effective feature engineering techniques, including Part-of-Speech (POS) tagging, tokenization, and punctuation ratio analysis, to gain insights into linguistic and structural attributes that distinguish humorous texts from non-humorous ones.
3.	__Visualizing Elements that Construct Humour:__ By constructing box plots and other visual representations, the research intends to depict the distribution of linguistic and structural features across humorous and non-humorous text categories, shedding light on the differences that contribute to humour identification.
4.	__Supervised Learning Models:__ Employing various supervised learning techniques, such as the Naive Bayes classifier, Random Forest, and advanced Pre-Trained Language Models like XLNet and BERT, the study seeks to classify text as humorous or non-humorous, providing a systematic approach for automating humour detection.
5.	__Comparative Analysis of Models:__ The research will undertake a comprehensive comparative analysis of the performance of different models in humour classification, aiming to determine which techniques and architectures are most effective for identifying humour in text.

## ABOUT THE DATASET:
The dataset that has been used in this research has been taken from Kaggle, titled ‘Jokes Detection’. It is a very popular dataset and is widely used by researchers in the NLP domain. It has 2,00,000 unique text records, which are classified as humorous or non-humorous (joke or plain text) via the ‘humour’ variable. The dataset is balanced, containing 50% True and 50% False values for the humour variable. Following is the snapshot of the data as a pandas data frame:

![image](https://github.com/AmritaVeshin/HumourDetection_NLP/assets/118504567/198f5416-04a5-40c2-b4e2-1d7a52485f0c)

## RESEARCH DESIGN FLOWCHART:
![image](https://github.com/AmritaVeshin/HumourDetection_NLP/assets/118504567/3eaefd31-e8c4-405d-8350-8adc910925a7)

## DATA PREPROCESSING:
* Tokenization

## EDA (EXPLORATORY DATA ANALYSIS):
1. Wordplay Comparisons w.r.t Humorous and Non-Humorous Texts
2. Checking The Proportion of Data
3. Punctuation Analysis
4. POS Tags Analysis

## CLASSIFYING TEXTS AS HUMOROUS AND NON-HUMOROUS VIA PRE-TRAINED LANGUAGE MODELS:
1. BERT
2. XLNET
3. Naiive Baye's Classifier
4. Random Forest Classifier

## RESULTS:
1.	The frequency of non-humorous texts having a lower character count is higher as compared to humorous texts, which tend to have a higher character count.
2.	The frequency of low-word-counted (8 to 12 words) non-humorous texts is quite higher than the humorous texts (for the given dataset), which tend to have a higher word count comparatively.
3.	Question marks were found to be more prevalent amongst texts classified as jokes. Consequently, we can conclude that humorous texts have a greater tendency to include question marks.
4.	On average, humorous content contains more punctuation marks compared to non-humorous content. A good joke is both surprising and follows a familiar comedic structure, often consisting of setups that lead to a punchline. Punctuation plays a significant role in maintaining this structure, which is why jokes tend to have more of it.
5.	Non-joke texts tend to contain a higher number of Proper Nouns, Adjectives, and Nouns. This suggests that non-joke texts may lean towards formality, resulting in an increased occurrence of these language elements.
6.	The BERT pre-trained model is more effective than the Naiive Baye's and Random Forest classifier models. Amongst the latter two, Naiive Baye’s Classifier proved to be slightly more effective than the Random Forest model. 

## CONCLUSION:
The field of natural language processing (NLP) is currently dominated by the Transformer architecture, which is evident by our research via implementing the BERT model and comparing it with the other Supervised ML techniques. This trend is expected to continue for several years. As demonstrated in this study, we've showcased the effectiveness of this approach. With a relatively short training time, we were able to achieve excellent model performance via the BERT pre-trained language model. In the realm of humour detection, we customized the BERT model and fine-tuned it for our specific task, which, in this instance, involves classifying text as either a joke or not.

## FILE DESCRIPTIONS:
1. 22122104_22122109_CAC2_Report.pdf: Full Study Report
2. JokeDetectionDataset_classified.csv: CSV file of the dataset used in the study
3. NLP_CAC2Flowchart.jpg: Study Design Flowchart  
4. NLP_CAC2_MiniProject_XLNetImplementation.ipynb: Python notebook containing the XLNet implementation
5.   
