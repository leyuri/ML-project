# 2019 데이터 크리에이터 캠프


### 공모개요

- 비즈니스 환경에서 직면할 수 있는 문제에 대해 빅데이터 및 지능정보 기술로 해결 해 나가는 관련 지식 및 문제해결 능력 습득 기회 제공 


### 공모주제

- 2019 데이터 크리에이터 캠프
- 캠프활동
  * 빅데이터 관련 분야 전문가 특강
  * 비즈니스 문제 해결 및 핸즈온 랩(HOL)
  * 분석 도구를 활용한 데이터 모델링 해커톤
  * 문제 해결을 위한 팀별 프로젝트 및 발표평가
  * 입상팀 프로젝트 제작과정 YouTube 게시 

___


아나콘다 설치 시 미리 파이썬 제거를 해야 한다! 근데 난 안했음...
예전에 이미 아나콘다를 설치했던 전적이 있었음. 근데 그때 설정한 경로랑 아마 충돌이 있었던 것 같다.
. bashrc등에 있는  path 를 모두 삭제해줌

그리고 .zshrc 에 export PATH="/anaconda3/bin":$PATH 추가해주니까 갑자기 작동됨;;;;;

이것 때문에 몇시간 동안 애먹었던 거 해결..역시 개발환경 구축하는 게 다인듯

전에는 `python —version`  터미널에서 2.7 이 자동으로 떴는데(맥 os 는 이게 기본임...) `python3 —version` 하면 3.7 이렇게 따로 떴는데 이제 3만 뜬다~



```
No module named tensorflow in jupyter

Jupyter runs under the conda environment where as your tensorflow install lives outside conda. In order to install tensorflow under the conda virtual environment run the following command in your terminal:
```

모듈 사용할 때마다 설치해주자!

`conda install -c conda-forge tensorflow`




#### 엑셀처럼 사용해볼 수 있는 판다스
https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html

판다스를 통해서도 왠만한 시각화를 할 수 있다.
엠스코의 4인방? 플럿라인? ggplot라인, 이 문법을 쓰는 라인은 업데이트가 안되는 편
판다스나 멧플랏에 의존성이 높은편, 그래서 판다스로 시각화하는 것으로 변경함…..



#### **다양한 모델 사용법**
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html



#### **Matplotlib**
정보 시각화는 데이터 분석에서 매우 중요하다. 시각화는 특잇값을 찾아내거나 데이터 변형이 필요한지 알아보거나 모델에 대한 아이디어를 찾기 위한 과정의 일부이다. matplotlib 기반의 시각화 도구를 살펴보자. 주로 2D 기반 그래프를 위한 파이썬 패키지 내부적으로 matplotlib를 사용하는 seaborn 라이브러리도 살펴보자. 


#### Seaborn
**seaborn: matplotlib**를 사용하기 쉽게 맵핑해놓은 라이브러리라고 한다. matplotlib보다 훨씬 더 간결하게 사용할 수 있다. 쓰고 싶은 라이브러리가 있을 경우 예제를 참고하여 그려주면 된다.  


seaborn에서 검은색 선이 표시되어있다. 
왜?????? estimator=<function mean at.. 
Ci? Ci 이라는 옵션은 신뢰의 구간을 의미한다. 여기의 95%샘플이 이정도에 위치한다
검은색 선은 ,,,,양 극단에 있는 이상치라고 볼 수 있다…(어렵네,,1학년 때 들었던 통계학개론 가물가물...;;)?

변동 계수 변동 계수(coefficient of variation, CV)는 표준 편차( )를 산술 평균( )으로 나눈 것이다.변동 계수의 값이 클수록 상대적인 차이가 크다는 것을 의미


[[11,6],[19,21],[22,22],[8,21],[19,23],[22,10],[17,12],[13,8],[6,7],[13,10],[44,40],[27,36],
    [45,28],[39,47],[44,39],[28,25],[32,25],[26,44],[26,29],[38,26]]

 
