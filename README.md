# ap_final_project


GitHub: https://github.com/ostararo/ap_final_project
Final report
I.	Introduction
Problem: 
Personally, I have never faced up with services or websites that can provide you an opportunity to recognize architectural styles.
However, many people who are fond of this type of art find it uncomfortable to search on Wikipedia or other websites to find out a style of building. Also, information on the Internet can differ. And it would be user-friendly to combine such functions as generating samples, displaying new information and recognition in one website.
Literature review:
1)	https://colab.research.google.com/drive/1iG0NAsiKj-3LtU3kjMTbOJnhuiWOxaGF#scrollTo=b-hjUdSAHDpI – Architectural style recognition (code in Google Colab)

It is also a model for architectural style recognition, however, in the implementation of the model itself, the FastAi library is mainly used. 
The main idea of this solution was to display the prediction on each architectural style. 25 styles available – 25 predictions in percentage.
I personally liked and implemented the idea of importing Kaggle dataset with API, without downloading it on your PC. 

2)	‘Architectural Style Classification Using Multinomial Latent Logistic Regression’ by Zhe Xu, Dacheng Tao, Ya Zhang, Junjie Wu, and Ah Chung Tsoi.

It is a scientific paper whose main problem is architectural style recognition. Authors found this topic interesting due to some challenges: the absence of a proper dataset for working and architecture’s features. This feature is that all styles are mixed with each other and have no strict distinctions. This happened because of the gradual development of architecture in different countries and cross-cultural sharing, so one style can have a few elements of another one. In general, the authors created a method called Multinomial Latent Logistic Regression. 
Current work:
For now I can only present model for recognition.
Note: Today, when I wanted to record the video and submit everything, I found out that the antivirus detected the project file as malicious, and deleted it without a chance to restore it. Unfortunately, there are no such evidences to prove it, because I hadn’t worked with backups, however, from now I will ) 
I understand that there are no reasons for you to believe. And, also, you gave enough time before to work and submit the project, so, it is only my fault. However, I wanted to warn you.
Today I had time only to recreate the model, and its training was too long and not so well. But, I decided to submit everything that I could do by now. It is report, proposal, and ipynb file with model. So, please, grade what I have. 
II.	Data and methods
Information about the data: 
In this project, I used a dataset on architectural styles from Kaggle.com. Link: https://www.kaggle.com/datasets/wwymak/architecture-dataset. Originally this dataset was created for the scientific work ‘Architectural Style Classification Using Multinomial Latent Logistic Regression’ by Zhe Xu, Dacheng Tao, Ya Zhang, Junjie Wu, and Ah Chung Tsoi.
The dataset consists of 4794 files belonging to 25 classes, which you can see below.
 
Fig 1, https://link.springer.com/content/pdf/10.1007/978-3-319-10590-1_39.pdf, page 4

Description of the ML models:
For implementing the model I used Sequential API. First of all, I had experience working with it. Secondly, there is no need for higher flexibility of the model(for example, not a few inputs).
Architecture of the model:
 

III.	Results
Results of training:
I tried dropouts, manipulation with datasets, but it is a maximum for which I could increase accuracy.
 
IV.	Discussion
Next steps:
1)	Increasing the accuracy and effectiveness of the model
2)	Widening the functional part of the project: develop  parts mentioned in the project proposal – such as printing images for certain asked styles, displaying brief information about style by choosing it in the drop-down list
3)	Not only to recognize the main style but recognize sub-styles and elements of other styles 
Reflection:
In a nutshell, the part with architectural styles was more complicated than I thought. After a more accurate examination of the articles, I realized the feature of architecture which I mentioned in the literature review. Here I should have been preparing and analyzing the topic more carefully and deeply taking into consideration all details. To sum up, my knowledge of statistics and its application in programming was not enough to complete this project as perfect as I wanted. Especially after this situation with antivirus.
V.	Sources
https://www.youtube.com/watch?v=57N1g8k2Hwc – How to Import (use) Kaggle datasets in Google Colab
https://www.youtube.com/watch?v=jztwpsIzEGc&t=1578s - Build a Deep CNN Image Classifier with ANY Images
https://colab.research.google.com/drive/1iG0NAsiKj-3LtU3kjMTbOJnhuiWOxaGF#scrollTo=b-hjUdSAHDpI – Architectural style recognition (code in Google Colab)
https://link.springer.com/content/pdf/10.1007/978-3-319-10590-1_39.pdf - Architectural Style Classification Using Multinomial Latent Logistic Regression’ by Zhe Xu, Dacheng Tao, Ya Zhang, Junjie Wu, and Ah Chung Tsoi.
