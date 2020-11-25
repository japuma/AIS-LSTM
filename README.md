# AIS - LSTM

About
------------
LSTM Keras Neural Network to predict ship location using Danish AIS data  
Data Found [Here](ftp://ftp.ais.dk/ais_data/) ftp://ftp.ais.dk/ais_data/ - CSV files too large to include in repository 


Project Folder Structure
------------

    │── README.md          <- The top-level README.
    │── data
    │   │── interim        <- Intermediate data that has been transformed.
    │   │── processed      <- The final, canonical data sets for modeling. In .npz format.
    │   │── raw            <- The original, immutable data dump.
    │
    │── models             <- Trained and serialized models, model predictions, or model summaries
    │
    │── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    │── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    │── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    │── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │── src                <- Source code for use in this project.
    │   │── __init__.py    <- Makes src a Python module
    │   │
    │   │── data           <- Scripts to download or generate data
    │   │   │── pull_danish_data.py
    │   │
    │   │── preproc		   <- Scripts to turn raw data into features for modeling
    │   │   ├── danish_preproc.py
    │   │
    │   │── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   │── danish_predict_model.py
    │   │   │── danish_train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── danish_graph_tracks.py
    │
	│
	│
	└────────────────────────────────────────────────────────────────────────────────────────────────────
--------

About (KOR ver)
------------
덴마크 AIS 데이터를 사용하여 선박 위치를 예측하는 LSTM 케라스 신경망
찾은 데이터: [Here](ftp://ftp.ais.dk/ais_data/) ftp://ftp.ais.dk/ais_data/ - CSV파일이 커서 본 파일에 포함시키지 않았습니다.

Project Folder Structure (KOR ver)
------------

    │── README.md          <- README.
    │── data
    │   │── interim        <- 변형된 중간 데이터 (데이터 정규화)
    │   │── processed      <- 모델링을 위한 최종 데이터 세트. (npz 형식) (데이터 전처리) 
    │   │── raw            <- 원시 데이터
    │
    │── models             <- 훈련되고 직렬화된 모델, 모델 예측 또는 모델 요약
    │
    │── references         <- 데이터 사전, 설명서, 기타 모든 설명 자료
    │
    │── reports            <- HTML, PDF, LaTeX 등으로 생성된 분석 보고서
    │   └── figures        <- 분석 보고서에 사용한 그래픽과 그림 
    │
    │── requirements.txt   <- 분석 환경 재현을 위한 요구사항 파일, 예.
    │                         generated with `pip freeze > requirements.txt`
    │
    │── setup.py           <- 모듈 import가 가능하게 하기 위한 pip 설치 (pip install -e .)
    │── src                <- 프로젝트에서 사용하기 위한 소스 코드
    │   │── __init__.py    <- src를 파이썬 모듈로 만듦
    │   │
    │   │── data           <- 데이터를 다운로드하거나 생성하기 위한 코드 (데이터 정규화)
    │   │   │── pull_danish_data.py
    │   │
    │   │── preproc		   <- 원시 데이터를 전처리하는 코드 (데이터 전처리)
    │   │   ├── danish_preproc.py
    │   │
    │   │── models         <- 모델을 교육한 다음 교육된 모델을 사용하여 예측하는 코드
    │   │   │── danish_predict_model.py
    │   │   │── danish_train_model.py
    │   │
    │   └── visualization  <- 분석, 결과를 시각화하는 코드
    │       └── danish_graph_tracks.py
    │
	│
	│
	└────────────────────────────────────────────────────────────────────────────────────────────────────
--------
