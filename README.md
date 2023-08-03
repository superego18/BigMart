# BigMart
SNU 핀테크데이터사이언스 전문가 과정 중 기계학습과 딥러닝 과목의 머신러닝 팀프로젝트

### 소속
SNU 핀테크데이터사이언스 전문가 과정 중 통계, 데이터사이언스 과목의 팀프로젝트

### 활동기간
2023.03

### 데이터셋
BigMart Sales Data (https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data?resource=download)
- tabular data
- 설명변수: Item_Outlet_Sales(특정 outlet에서의 판매량)
- 종속변수: Item_Identifier(Item 식별번호), Item_Weight(Item 무게), ...
- 종속변수 수: 11
- 관측치 수: train(8,523), test(5,681)
- 특징: 예측

### 활동내용
목적: 판매량 예측

데이터셋 다원화
- 기본 전처리 후 log 변환과 pca 적용 여부에 따라

모델링 
- 사용 모듈: sklearn
- 사용 모델: RandomForestRegressor, Voting Regressor(Ensemble), ...
- hyperparameter tuning: optuna

### 역할
Base 코드 파이프라인 구축
- 적절한 dataset과 model 선택
- hyperparameter tuning
- K-Fold Cross Validation

모델 테스팅
- Ensemble

### 결과
- 성능지표: RMSE
- 최종 모델: RandomForestRegressor (RMSE: 0.5131)

