# Porto_Seguro_Safe_Driver

## 승자의 지혜
### Feature Engineering
1. missing자체의 개수를 피쳐로 사용!
- missing을 지우거나, imputation하는 것이 아닌 그대로 사용!
- missing is useful!
- MCAR이 아니라는 가정이 필요하겠지?

2. 기존의 변수를 이용하여 파생 변수를 regression을 통한 예측으로 만든다!(신기허네,,,)
- 변수들의 이름을 잘 보면, 'car', 'idn','reg' 대분류로 나누어져있다. 각각 대분류별 변수들을 이용해서 xgboost를 이용하여 새로운 변수를 만들어낸다
- 단, xgboost모델을 너무 깊게 사용하지 않는다.(generality를 유지하기 위해) max_depth = 6

3. 
