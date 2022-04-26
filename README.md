# Steam game review sentiment analysis based on DL

전 세계 최대 디지털 멀티플레이어 게임 플랫폼인 스팀 내 게임 리뷰 데이터를 활용한 감성 분석 프로젝트를 진행했습니다.

```
데이터 셋 가공 (텍스트 전처리)
Okt를 활용한 토큰화 진행 및 Wordcloud 도식을 통한 긍/부정으로 분류된 리뷰의 특징 확인
BiLSTM을 활용한 감성분석 실시 및 모델을 활용한 실제 리뷰 예측해보기
```

#### 텍스트 전처리 (정규화)
![image](https://user-images.githubusercontent.com/70729822/165372224-ce9d8b5a-27a8-482b-b3c2-9d22e7a9458c.png)

#### Okt를 활용한 토큰화 진행 (불용어 추가)
![image](https://user-images.githubusercontent.com/70729822/165372687-0200bb8b-b2f6-4351-a163-1623672cbd02.png)
![image](https://user-images.githubusercontent.com/70729822/165372746-a2f55b7c-6404-4111-9b5c-5f8502c5e819.png)

#### 부정으로 분류된 리뷰 단어 특징
![image](https://user-images.githubusercontent.com/70729822/165372817-e84c88d4-f8e6-495d-b917-40ee79243287.png)

#### 긍정으로 분류된 리뷰 단어 특징
![image](https://user-images.githubusercontent.com/70729822/165372834-01bba2ea-199a-4a0b-9716-68513bf5b2d4.png)

#### BiLSTM을 활용한 감성 분석 실시
![image](https://user-images.githubusercontent.com/70729822/165373032-c4944112-e377-4d32-884a-a0c8b3c360d9.png)

#### 실제 리뷰 예측해보기
![image](https://user-images.githubusercontent.com/70729822/165373108-b538fd0c-0e06-4cbd-a39c-df0e330ea273.png)
![image](https://user-images.githubusercontent.com/70729822/165373137-a008b7e6-0e3e-42ce-8b9c-1f54a0dc8ba4.png)
![image](https://user-images.githubusercontent.com/70729822/165373168-e25752bb-a91f-4dc6-9d60-b899cbbfd0d8.png)
