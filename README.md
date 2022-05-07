# 리그오브레전드 사전 승패예측

픽창에서 승패를 알 수 있다. 

## 문제

#### 1. Pick & Ban 단계에서 전적 검색만으로 승패를 객관적으로 예측할 수 없음.
#### 2. 사전 승패예측을 할 수 있는 모델에 대한 연구가 없음

## 선행연구


#### 1. 양방향 순환신경망 임베딩을 이용한 리그오브레전드 승패 예측 : LSTM / 58.07% 
낮은 정확도, random 50% 와 단 8% 차이.
#### 2. 딥 러닝을 이용한 리그 오브 레전드 승패 예측 예비 연구 : DNN / 99.29%
이론상 정확도는 높으나, 현실적으로 불가능한 모델.
사후 데이터를 바탕으로 승패를 예측하고 있음.
예측모델을 적용하려면 게임 시작 전에 예측을 해야하는데, 이에 대한 설명 및 대안이 없음.
#### 3. 기계학습을 활용한 E-Sports 승·패 예측에 관한 연구 : Decision Tree, NaiveBayes, Logistic Analysis / 92%
2번 논문과 마찬가지로 실전에 적용할 수 있는 모델이 아닌, "학습을 위한 예측 모델"임.
#### 4. DNN을 활용한 ‘League of Legends’ 승부 예측 : DNN / 93.75%
상기 논문들과 마찬가지로 실전 적용 불가. 학습 데이터셋은 26000개, 테스트 데이터 셋은 단 16개에서 나온 정확도이므로 신뢰할 수 없음.

## 
