# 🗺️공간정보활용공모전
합성곱 신경망(CNN)을 활용한 공간정보 데이터 기반 지형형상 분류 모델 개발

<div style="display: flex;">
<p align="center"><img width="270" alt="스크린샷 2024-02-21 오후 9 32 05" src="https://github.com/dbtjgus6988/-/assets/144633320/4ba1e961-e3cb-4a65-a47b-dbe54c96158c"></p>
</div>
 공간정보를 활용하여 딥러닝을 통한 지형형상 정보 구축 <br>
<br>


## 📌Introduction

### Service Info
▶️ ‘표준지공시지가 공간정보’를 데이터로 사용하는 딥러닝을 통한 토지형상 예측 알고리즘 개발
  
### Project Goal
1️⃣ 이미지 분류 알고리즘을 이용하여 모호한 지형형상 구분 <br>
2️⃣ 전문가와 협의하는 불필요한 과정 축소

<br>
     
## 🖥️Model

### Dataset
- 데이터: 2022년, 2021년, 2020년, 2019년, 2018년, 2016년 경기도 표준지공시지가공간정보
- 출처: 국가공간정보포털(http://openapi.nsdi.go.kr/nsdi/eios/ServiceDetail.do)
∘ 데이터(X) : geometry (Shapely Polygon)
∘ 라벨(Y) : 지형형상코드

### Modeling
- PyTorch deep-learning Framework
- CNN(Resnet 참고)
- CrossEntropyLoss
  
<br>

## 💻Technology Stack
✅ [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) <br>
✅ [![GeoPandas](https://img.shields.io/badge/GeoPandas-43B02A?style=flat-square&logo=GeoPandas&logoColor=green
)](https://geopandas.org/en/stable/getting_started/introduction.html) <br>
✅ ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

<br>

## ❗️Contribution
- 공간정보를 이미지로 변화하여 데이터셋을 제작
- 약 80% 정확도로 지형형상을 분류 가능한 이미 지 분류 모델을 구축
- 인접 도로에 대한 정보를 모델에 추가적으로 입력하는 등 모델 성능을 향상시킬 수 있는 방안에 대해 모색

<br>

## ❗️Future work
이러한 공간정보화에서 우리의 지형형상 분석 모델은 보다 데이터를 효율적으로 분석하는 데 도움을 줄 수 있습니다. <br>
1) 특히 토지특성조사 업무에 자동화 과정을 도입에 기여할 것으로 기대해 볼 수 있습니다.<br>
   - 직접 지형 형상을 조사하지 않아도 공간정보를 바탕으로 형상을 예측할 수 있습니다.<br>
   - 조사 기간 및 예산, 인력투입이 절감될 것이라 예상되며, 조사결과의 신뢰도, 일관성, 검증가능성 증대까지 기대해 볼 수 있습니다. <br>
2) 효율적인 토지형상 예측을 통해 해당 토지의 사용 용도를 손쉽게 구상 가능할 것으로 예상됩니다.
+ 인접 도로에 대한 정보를 반영하는 이미지 분류 알고리즘 기반 토지형상 분류 모델에 대한 후속 연구가 이루어지기 를 기대합니다.
  
<br>

## 👩‍👩‍👧‍👦Team
- 곽승민(Hanyang univ.)
