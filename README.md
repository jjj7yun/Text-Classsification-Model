# Text-Classsification-Model

뉴스 기사 제목을 입력하면 ESG 관련 기사 여부를 분류하는 텍스트 분류 모델


Data: 2020년 이후 네이버 뉴스 기사 중 '기업 사회 책임'을 keyword 로 크롤링

![image](https://user-images.githubusercontent.com/79688191/147721904-a5115b0d-b26a-474e-9c45-315f57fa3859.png)
(Github에는 용량 문제로 일부 데이터만 업로드하였음)

ESG 관련 기사는 1, 일반 기사는 0으로 labeling 후 BERT 기반 학습

### 학습 결과
![image](https://user-images.githubusercontent.com/79688191/147721942-091deb48-339e-4b83-99c5-4e7eabe63beb.png)
![image](https://user-images.githubusercontent.com/79688191/147721975-cec450b3-e76c-4da7-9651-49c656660582.png)

뉴스 제목 만으로 정확도 91% 분류 성능을 보임


### KoBERT
:훈련용 폴더
텍스트 분류 모델 생성을 위해 학습한 KoBERT 모델
트위터 크롤링 및 전처리 코드와 모델 생성 이전 연습했던 네이버 댓글 분류 모델링 포함
