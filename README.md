# Text-Classsification-Model

뉴스 기사 제목을 입력하면 ESG 관련 기사 여부를 분류하는 텍스트 분류 모델


Data: 2020년 이후 네이버 뉴스 기사 중 '기업 사회 책임'을 keyword 로 크롤링

![image](https://user-images.githubusercontent.com/79688191/147721904-a5115b0d-b26a-474e-9c45-315f57fa3859.png)

ESG 관련 기사는 1, 일반 기사는 0으로 labeling 후 BERT 기반 학습

### 학습 결과
![image](https://user-images.githubusercontent.com/79688191/147721942-091deb48-339e-4b83-99c5-4e7eabe63beb.png)
![image](https://user-images.githubusercontent.com/79688191/147721975-cec450b3-e76c-4da7-9651-49c656660582.png)

제목만을 가지고 91%의 정확도로 뉴스 분류 가능
