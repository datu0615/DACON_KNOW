# DACON_KNOW
![20220524_113417](https://user-images.githubusercontent.com/84311270/169937125-53bab8ab-9e41-4c2e-bf76-27e67b52c4a8.png)
KNOW(한국직업정보) 설문 데이터셋을 활용한 직업 추천 알고리즘 개발 및 직업과 연관이 높은 설문지 문항 분석 및 영향변수 발굴

## Dataset
1. KNOW 메타데이터 [Folder]  
 ├ 2017_KNOW_재직자조사_설문지.pdf  
 ├ 2018_KNOW_재직자조사_설문지.pdf  
 ├ 2019_KNOW_재직자조사_설문지.pdf  
 ├ 2020_KNOW_재직자조사_설문지.pdf  
 ├ 2017_변수값.pdf  
 ├ 2017_변수설명.pdf  
 ├ 2018_변수값.pdf  
 ├ 2018_변수설명.pdf  
 ├ 2019_변수값.pdf  
 ├ 2019_변수설명.pdf  
 ├ 2020_변수값.pdf  
 └ 2020_변수설명.pdf  

2. train [Folder].  
 ├ KNOW_2017.csv  
 ├ KNOW_2018.csv  
 ├ KNOW_2019.csv  
 └ KNOW_2020.csv  

3. train [Folder].  
 ├ KNOW_2017_test.csv  
 ├ KNOW_2018_test.csv  
 ├ KNOW_2019_test.csv  
 └ KNOW_2020_test.csv   

4. sample_submission.csv  

## Model
데이터의 결측치 처리 및 이상치 전처리를 진행하였으며 최종적으로 Catboost 모델을 사용.

## Results
Public Score : 0.5898, Private Score : 0.58949로 최종 59등으로 마무리.
![20220524_113521](https://user-images.githubusercontent.com/84311270/169937893-501238bc-0fd4-4689-a953-5331a0567658.png)
