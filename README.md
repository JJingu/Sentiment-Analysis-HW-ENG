### 자연어처리 감정분석 실습: 시트콤 프렌즈 대사 데이터를 활용한 영어 데이터 감정 분석

- 실습 및 코드 수정자: 김진구
- 메일: kim.jin.gu@hanmail.net

코드원본(https://github.com/jiwonny/nlp_emotion_classification)
- Friends 영화 대본 데이터 감정 분석
- 원본 제작자: jiwonny
---

### 실행방법

`★자연어처리 기말과제 제출코드_Sentiment Analysis using ELECTRA Transformer(eng).ipynb`  

- 학습데이터
 `friends_train.json`, `friends_dev.json`, `friends_test.json`

- 시험데이터
 'en_data_new.csv'

 


#### Overview

네이버 영화 리뷰데이터(Naver Sentiment Movie Corpus,NSMC)를 활용한 감정분석 과제(사실상 실습코드)


* 데이터 준비
* 토큰화
* 정수인코딩
* 패딩
* 모델구현
* 학습
* 결과 추출

---

#### Data

학습데이터는 [github]( http://doraemon.iis.sinica.edu.tw/emotionlines/)에서 받음


---
#### Package
필요한 패키지는 다음과 같습니.

* torch
* Tensorflow
* Pandas
* Numpy
* random
* time
* datetime
* json
* keras
* konlpy (okt 사용)

---
