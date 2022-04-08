# Classification of Sub-Categories under Fake News
A Classification model to correctly classify the news into suitable sub-categories of Fake News based on features extracted.
The condensed table for the classification is as follows:
![clip](https://user-images.githubusercontent.com/53210156/162459702-b03af5ca-0a3b-4655-9b64-b98d89bbaf74.PNG)

The datasets used are FakeNewsNet and BSDetector for the purpose, which has features like Title, Text, Source, Author, Images, Metadata etc. 

From the dataset (1536 samples) I extracted the features listed in the table and ran the Partitioning Around Mediods(K-Mediods) Clustering and K-modes Clustering on it. The clusters generated are then analysed and labelled.

I also prepared a test dataset of about 100 samples (from the Politifact Dataset). I manually labelled this test dataset and ran the selected algorithms using it. I then compared the clusters the algorithms assigns each data-point to, with the label I assigned to it and calculated the accuracy. 

The K-Mediods Clustering gave the accuracy of about 84 %, while the K-Modes Clustering gave the accuracy of about 81 %.

![image](https://user-images.githubusercontent.com/53210156/162462839-c2db3d20-cc9b-4a07-a79b-508ecb3016f4.png)



