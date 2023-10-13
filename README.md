# [Dacon] 데이크루 4기 '한남더힐'팀 활동 기록

## 데이크루 소개
<b>데이크루(DACrew)</b>는 데이콘 플랫폼 커뮤니티의 활성화를 위해 양질의 컨텐츠를 제작하는 서포터즈입니다. <br>
데이크루 4기에서는 그동안 데이콘에서 열렸던 대회의 데이터를 활용하여 프로젝트 기반 학습 자료를 만드는 활동을 진행하였습니다.

<img src="https://user-images.githubusercontent.com/118996664/226500286-59e8b8e6-b68f-471e-9902-b41aa60f4235.png" width="500" height="300"/>


## 활동 내용
* 데이크루 4기의 미션은 <b>프로젝트 기반 학습 자료(Project Based Learning, PBL) 제작</b>입니다. 데이콘의 다양한 경진대회 데이터를 활용하여 총 여섯 단계로 이루어진 PBL 콘텐츠를 만들었습니다.
* 저희 팀이 진행한 프로젝트의 목표는 <b>실제 '직방'의 아파트 거래 데이터를 가지고 지도 학습을 해서 아파트 실거래가를 예측하는 것</b>입니다.   

<br>

### Stage 1
데이터를 분석하려면 가장 먼저 분석할 데이터를 살펴보아야 합니다. Stage 1에는 pandas 패키지를 활용해서 데이터가 어떻게 생겼는지 대략적으로 파악해보고, 앞으로 어떤 분석을 적용하면 좋을지 방향성을 잡는 과정을 담았습니다. 

#### [Stage1_한남더힐 내집마련 프로젝트 🏢.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage1_%ED%95%9C%EB%82%A8%EB%8D%94%ED%9E%90%20%EB%82%B4%EC%A7%91%EB%A7%88%EB%A0%A8%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%F0%9F%8F%A2.ipynb)

<br>

### Stage 2
Stage 2에서는 데이터가 어떻게 생겼는지 시각화해보고, 앞으로 데이터를 어떤 식으로 가공하고 분석해야 할지 고민해보았습니다.

#### [Stage2_넌 모르잖아, 알록달록한 데이터 시각화의 세상.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage2_%EB%84%8C%20%EB%AA%A8%EB%A5%B4%EC%9E%96%EC%95%84%2C%20%EC%95%8C%EB%A1%9D%EB%8B%AC%EB%A1%9D%ED%95%9C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%9C%EA%B0%81%ED%99%94%EC%9D%98%20%EC%84%B8%EC%83%81.ipynb)

<br>

### Stage 3
Stage 3에서는 데이터를 전처리했습니다. 파생변수 생성, 로그변환, 이상치 제거, 필요없는 컬럼 삭제, 범주형 인코딩, 스케일링 등의 과정을 통해 모델이 데이터를 더 잘 이해할 수 있도록 만들었습니다.

#### [Stage3_이런 걸 데이터 전처리라고 하는거야 🤨.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage3_%EC%9D%B4%EB%9F%B0%20%EA%B1%B8%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A0%84%EC%B2%98%EB%A6%AC%EB%9D%BC%EA%B3%A0%20%ED%95%98%EB%8A%94%EA%B1%B0%EC%95%BC%20%F0%9F%A4%A8.ipynb)

<br>

### Stage 4
Stage 4에서는 모델이 예측을 잘 하고 있는지 모델의 성능을 평가하고, 의사결정나무, 랜덤포레스트 등의 모델을 구현한 성능을 평가해보았습니다. 이때 그리드서치, 랜덤서치 방법을 통해 모델의 하이퍼파라미터를 튜닝하는 방법에 대해서도 알아보았습니다.

#### [Stage4_고작 이 성능만 보고 그런 표정이 되는거에요 😶.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage4_%EA%B3%A0%EC%9E%91%20%EC%9D%B4%20%EC%84%B1%EB%8A%A5%EB%A7%8C%20%EB%B3%B4%EA%B3%A0%20%EA%B7%B8%EB%9F%B0%20%ED%91%9C%EC%A0%95%EC%9D%B4%20%EB%90%98%EB%8A%94%EA%B1%B0%EC%97%90%EC%9A%94%20%F0%9F%98%B6.ipynb)

<br>

### Stage 5
Stage 5에서는 성능이 좋은 것으로 알려진 부스팅 모델로 아파트 실거래가를 예측해보고, `Pycaret`이라는 패키지에 대해 알아보았습니다.

#### [Stage5_브라보 ! 멋지다, 부스팅모델 👏👏.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage5_%EB%B8%8C%EB%9D%BC%EB%B3%B4%20!%20%EB%A9%8B%EC%A7%80%EB%8B%A4%2C%20%EB%B6%80%EC%8A%A4%ED%8C%85%EB%AA%A8%EB%8D%B8%20%F0%9F%91%8F%F0%9F%91%8F.ipynb)

<br>

### Stage 6
앞서 Stage 5에서 부스팅 기법을 사용하는 여러 가지 모델과 하이퍼파라미터에 대해 알아보고, 모델의 성능을 측정하여 최종 후보 모델을 선정하였습니다. 하지만 더 좋은 예측을 하기 위해서는 새로운 데이터를 추가적으로 활용하거나 모델의 하이퍼파라미터를 튜닝하는 과정이 필요한데요. Stage 6에서는 이러한 과정을 통해 최적의 모델을 선정해보았습니다.

#### [Stage6_우리 꼭 또 보자, 대회 상위권에서 🏆️.ipynb](https://github.com/jiazzang/Activity-2023-dacon-crew/blob/main/Stage6_%EC%9A%B0%EB%A6%AC%20%EA%BC%AD%20%EB%98%90%20%EB%B3%B4%EC%9E%90%2C%20%EB%8C%80%ED%9A%8C%20%EC%83%81%EC%9C%84%EA%B6%8C%EC%97%90%EC%84%9C%20%F0%9F%8F%86%EF%B8%8F.ipynb)

<br>

### 최종 모형
랜덤포레스트, LGBM, XGB 모델을 각각 최적화한 결과, 세 모델 중에서 <b>LGBM</b>의 성능이 가장 우수했습니다. 모델 선정에 있어서는 성능과 시간이 모두 고려해야 하는데, LGBM의 경우 가장 빠른 랜덤포레스트에 비해 14초 밖에 차이나지 않는 데다가 성능도 가장 좋으므로 최종 모델로 LightGBM을 선택했습니다.

<br>

### 경진대회 결과
제가 소속된 '한남더힐' 팀은 27개의 팀 중 1위를 달성하였습니다.
