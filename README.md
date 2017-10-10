# MovieReview
Machine Learning Project, Sentimental Analysis for movie reviews and also having a search engine UI
ReadMe file for MoReview APPLICATION - MOVIE REVIEWS SENTIMENT ANALYSIS 

TABLE OF CONTENT
* DATE OF RELEASE 
* ABOUT MoReview APPLICATION
* CONFIGURATION INSTRUCTIONS AND PRE-INSTALLED SOFTWARE
* INSTALLATION INSTRUCTIONS
* OPERATING INSTRUCTIONS
* COPYRIGHT AND LICENSING INFORMATION

-----DATE OF RELEASE ------ 

April 30th, 2017 - Checkpoint 4 release 

-----ABOUT MoReview APPLICATION----------

MoReview Application is being developed as part of the ISTE-612 Knowledge Processing Technologies
Class by Group 8 members. This application will provide sentimental analysis for movie reviews 
present in Rotten Tomatoes. This release contains the core classifier and the integration with the UI.
The sentiment values range from 0 to 4.  

----CONFIGURATION INSTRUCTIONS AND PRE-INSTALLED SOFTWARE----
To run this application, the operating machines needs to have downloaded the following software

Java Eclipse for Developers Neon 3 (Release 4.6.3).
JRE 1.8.0._121 
Apache Tomcat v8.5 (Make sure to have Apache Tomcat v8.5 in the Eclipse Neon 3). 


 
-----INSTALLATION INSTRUCTIONS ----- 
To install this application, the program with corresponding files have to be downloaded. Have the program
imported in Eclipse. Download the 'train' and 'test' folders. In order to have the program running, some paths have to be updated.
Update the FirstServlet.java file, row 52, with the path where the train folder is located. 
E.g. NBClassifier matrix = new NBClassifier("C:/Users/asejfia/Desktop/train"); 
Update the NBClassifier.java file, row 207, with the path where the test folder is located. 
E.g. String supplyData = "C:/Users/asejfia/Desktop/test2";

Rightclick on the program and select Run on Server. Select the Apache Tomcat v8.5 
server.  

------OPERATING INSTRUCTIONS ---------
The application, in this release, contains the Naive Bayes Classifier and a specific amount of 
train and test data. The program will be trained based on the training data and will classify 
the test data based on a sentiment range of 0 to 4. Once the first page comes up, you can provide a title of the movie,
such as Blood Work, and the program gives the percentage distribution of people’s sentiment for each movie. 


The accompanying training folders and test folders are divided based on the sentiments. The training phrases that 
belong to the sentiment 0 are in the train/0.txt file and so on. The test phrases that belong to the sentiment 0 
are in the test/0.txt file and so on. 

