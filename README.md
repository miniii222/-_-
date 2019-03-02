# Kaggle_kernel
- 캐글 커널 공부

## New York City Taxi Trip Duration : [link](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)

## kaggle 우승작으로 배우는 머신러닝_탐구생활 공부 
##### 저자 github : [link](https://github.com/bjpublic/kaggleml)


### 1. Santander Product Recommendation Competition : [link](https://www.kaggle.com/c/santander-product-recommendation)
### 대회 설명
##### - 진행기간 : 2016.10.27~ 2016.12.22
##### - 데이터 설명
   - 산탄데르 은행 고객들의 데이터를 갖고 적절한 금융 제품 추천
   - 지난 달에 이미 보유하고 있는 제품 지속 사용 -> 신규 구매 x
   - 지난 달에 보유한 제품 이번 달에 해지 -> 신규 구매 x
##### - 예측값 : 지난 달 에 보유하지 않은 금융 제품 중, 이번 달에 구매할 것으로 예측되는 제품 상위 7개 (고객별로)
##### - 평가 척도 : Mean Average Precision(MAP)@7
   - 구매할 확률이 높은 값을 많이 맞출수록 값이 크다.
   - 구매할 확률이 낮은 값을 맞출수록 작아진다.
##### - data 설명
   - train(13647309, 48) - 24개의 제품 
   - test(929615, 24)
