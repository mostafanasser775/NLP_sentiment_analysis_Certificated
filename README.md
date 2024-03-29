# Movie Review Sentiment Analysis

## Data Description
<ul>
<li>  Sentiment polarity dataset Consists of 1000 positive and 1000 negative processed reviews. Introduced in Pang/Lee ACL 2004. Released June 2004. </li>

  <li><a href="https://www.cs.cornell.edu/people/pabo/movie-review-data/poldata.README.2.0.txt">Click to read more about dataset</a></li>
</ul>
<br>

## Installation
<ol>
  <li>unzip the Data.rar file</li>
  <li>take path and update it in code</li>
  <li>run the program</li>
  </ol>
  
#                   Project Details For more  
# ***Data Exploration***
![Screenshot 2022-09-07 064912](https://user-images.githubusercontent.com/67934296/188791240-4ecb2947-c390-42f1-a26a-f29666de939e.png)

![Screenshot 2022-09-07 065031](https://user-images.githubusercontent.com/67934296/188791361-68f08da9-8778-4081-9126-91ddb4542074.png)

![Screenshot 2022-09-07 065224](https://user-images.githubusercontent.com/67934296/188791565-42cadaf2-fedb-4802-867f-72973bb28c1e.png)

## Most common sentences in data that are not stop words.

![bdc9f313-4e99-4121-b458-fb883687c456](https://user-images.githubusercontent.com/67934296/188792436-a24ca5df-4cff-4a7b-b767-b543750bb699.png)

## N-gram exploration with n = 2
![40a9309f-b4e5-4fab-a410-769f4c03e327](https://user-images.githubusercontent.com/67934296/188792481-a91a18e9-76b0-4127-b483-510f8c86ffbf.png)
## N-gram exploration with n = 3
![ed376b22-b5a3-4db7-b3f1-e388577147e0](https://user-images.githubusercontent.com/67934296/188792511-f527b5a2-1cd2-4684-9b57-bec641030da9.png)

# Data Preprocessing
* Case Normalization
* Remove Stopwords
* Stemming & Lemmatization (***PorterStemmer***)
* Text Cleaning using built Functions


## Top Stopwords
![9d1539e0-5ffb-4b98-befb-cfee6008ba21](https://user-images.githubusercontent.com/67934296/188792799-a172550e-edb1-4599-be59-c0e16b3486de.png)

# Word Cloud Data Sample Visualization
![93820e16-3c7f-44e5-bfac-d4ae1418e6a0](https://user-images.githubusercontent.com/67934296/188793458-02095c65-a9c1-4b20-92f9-0aee105814fd.png)

# sample of Model testing Results
  LogisticRegression(C=2.0)
  
  Accuracy:  0.84
  
  ![bdcab37c-625d-4b42-973b-f7f9e0afe5b7](https://user-images.githubusercontent.com/67934296/188793816-5b998841-04f5-4f38-a0fa-55b1266c0930.png)

LinearSVC()

Accuracy:  0.852

![3a8ac6a4-930a-454c-a999-2f5691d386a1](https://user-images.githubusercontent.com/67934296/188794118-c4dd6907-60b1-471b-9e57-df0696c4c3d2.png)

KNeighborsClassifier(n_neighbors=3)

Accuracy:  0.7

![5e0152e5-cb0e-4efc-bdba-acd636b4d188](https://user-images.githubusercontent.com/67934296/188794918-95a5e451-affb-4ce4-9cba-440ba1da45ab.png)

RandomForestClassifier(n_estimators=150)

Accuracy:  0.798

![543c9fcb-5d23-4fcc-8ec1-75e73c045f3b](https://user-images.githubusercontent.com/67934296/188794983-13922e9f-e59f-4d83-aa6f-a00059919e65.png)

SGDClassifier(max_iter=6)

Accuracy:  0.852

![7ca28938-a48d-4e29-80de-915ff6322b9b](https://user-images.githubusercontent.com/67934296/188795045-096f8372-90ef-48b6-a701-845cd3a9f607.png)

## LSTM CNN Classification model
![Screenshot 2022-09-07 072349](https://user-images.githubusercontent.com/67934296/188795388-caab8548-67cd-41f9-87eb-e3c9039a4bce.png)
## training model
![Screenshot 2022-09-07 072451](https://user-images.githubusercontent.com/67934296/188795503-64042c3a-5aa7-4e3e-8ae5-2ab4ca37bb03.png)
## loss visualization
![f5ef0e25-28bb-43ac-90ac-9eee003c4008](https://user-images.githubusercontent.com/67934296/188795659-ff143dde-8ce5-496c-82e9-22fe704a5751.png)
## Accuracy visualization
![7c3f2500-0af5-4847-a6a9-750e05a8bc17](https://user-images.githubusercontent.com/67934296/188795763-91468692-cedc-4011-b1c3-25ea0298dbae.png)
### best Accuracy got with lstm cnn was 84%
# Models Results visualization
![f5b3ebbe-e4b4-4f57-bc97-062ad2d44072](https://user-images.githubusercontent.com/67934296/188795915-43d0c8dc-33fc-4692-8fc2-c4cbe3409065.png)
### best Accuracy got for this project was 87%
# Certification
![IMG_20220907_125119](https://user-images.githubusercontent.com/67934296/188865245-57f9beb7-c85b-4b81-9931-9cf32683cbba.jpg)


