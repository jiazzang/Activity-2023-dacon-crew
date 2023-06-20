# [Dacon] 데이크루 4기 '한남더힐'팀 최우수상 수상

### 데이크루 소개
데이크루(DACrew)는 데이콘 플랫폼 커뮤니티의 활성화를 위해 양질의 컨텐츠를 제작하는 서포터즈입니다. 데이크루 4기에서는 그동안 데이콘에서 열렸던 대회의 데이터를 활용하여 프로젝트 기반 학습 자료를 만드는 활동을 진행하였습니다.

<img src="https://user-images.githubusercontent.com/118996664/226500286-59e8b8e6-b68f-471e-9902-b41aa60f4235.png" width="500" height="300"/>


### 활동 내용
* 데이크루 4기의 미션은 프로젝트 기반 학습 자료(Project Based Learning, PBL) 제작입니다. 데이콘의 다양한 경진대회 데이터를 활용하여 총 여섯 단계로 이루어진 PBL 콘텐츠를 만들었습니다.
* 저희 팀이 진행한 프로젝트의 목표는 실제 '직방'의 아파트 거래 데이터를 가지고 지도 학습을 해서 아파트 실거래가를 예측하는 것입니다.

#### Stage 1
데이터를 분석하려면 가장 먼저 분석할 데이터를 살펴보아야 합니다. Stage 1에는 pandas 패키지를 활용해서 데이터가 어떻게 생겼는지 대략적으로 파악해보고, 앞으로 어떤 분석을 적용하면 좋을지 방향성을 잡는 과정을 담았습니다. 

#### Stage 2
Stage 2에서는 데이터가 어떻게 생겼는지 시각화해보고, 앞으로 데이터를 어떤 식으로 가공하고 분석해야 할지 고민해보았습니다.

#### Stage 3
Stage 3에서는 데이터를 전처리했습니다. 파생변수 생성, 로그변환, 이상치 제거, 필요없는 컬럼 삭제, 범주형 인코딩, 스케일링 등의 과정을 통해 모델이 데이터를 더 잘 이해할 수 있도록 만들었습니다.

#### Stage 4
Stage 4에서는 모델이 예측을 잘 하고 있는지 모델의 성능을 평가하고, 의사결정나무, 랜덤포레스트 등의 모델을 구현한 성능을 평가해보았습니다. 이때 그리드서치/랜덤서치 방법을 통해 모델의 하이퍼파라미터를 튜닝하는 방법에 대해서도 알아보았습니다.

#### Stage 5
Stage 5에서는 성능이 좋다고 알려진 부스팅 모델과 Pycaret에 대해 알아보았습니다.

#### Stage 6
앞서 Stage 5에서 부스팅 기법을 사용하는 여러 가지 모델과 하이퍼파라미터에 대해 알아보고, 모델의 성능을 측정하여 최종 후보 모델을 선정하였습니다. 하지만 더 좋은 예측을 하기 위해서는 새로운 데이터를 추가적으로 활용하거나 모델의 하이퍼파라미터를 튜닝하는 과정이 필요한데요. Stage 6에서는 이러한 과정을 통해 최적의 모델을 선정해보았습니다.

#### 최종 모형
랜덤포레스트, LGBM, XGB 모델을 각각 최적화한 결과, 세 모델 중에서 LGBM의 성능이 가장 우수했습니다. 모델 선정에 있어서는 성능과 시간이 모두 고려해야 하는데, LGBM의 경우 가장 빠른 랜덤포레스트에 비해 14초 밖에 차이나지 않으므로 최종 모델로 LightGBM을 선택했습니다.


### 경진대회 결과
제가 소속된 '한남더힐' 팀은 27개의 팀 중 1위를 달성하였습니다.
