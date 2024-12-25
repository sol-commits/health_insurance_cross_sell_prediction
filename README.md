# 보험사 고객 데이터 분석 프로젝트

## 프로젝트 개요
[Kaggle의 Health Insurance Cross Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)에서 제공된 데이터를 활용하여 보험회사의 고객들이 새로운 자동차 보험에 대해 얼마나 관심을 보일지 예측하는 지표(Score)를 개발한 프로젝트입니다.

### 주요 목표
- 보험사 고객 데이터를 분석하여 자동차 보험 관심 여부를 예측할 수 있는 점수(Score) 생성.
- 다양한 변수들과 고객 응답 간의 상관관계 분석.
- 데이터의 전처리, 시각화 및 모델 개발을 통해 인사이트 도출.

---

## 프로젝트 구조
- **Imports**: 프로젝트에 필요한 라이브러리 및 패키지 불러오기.
- **Functions & Variables**: 프로젝트에서 사용된 주요 함수 및 변수 정의.
- **Data**: 데이터 로드 및 초기 탐색.
- **Analysis**:
  - **Target Column(Response) 살펴보기**:
    - 응답 비율 분석 및 시각화.
  - **UnderSampling 기법 적용**:
    - 데이터 불균형 문제를 해결하기 위해 RandomUnderSampling 적용.
  - **Numerical Column 분석**:
    - 연속형 변수의 분포 확인 및 이상치 처리.
  - **Categorical Column 분석**:
    - 범주형 변수의 데이터 분포 분석.
  - **상관관계 분석**:
    - 주요 변수와 응답 간의 상관관계 시각화 및 분석.
  - **주요 변수에 따른 응답 분석**:
    - Vehicle_Damage, Vehicle_Age, Previously_Insured, Policy_Sales_Channel, Age 등.
  - **Score 계산 및 검증**:
    - 상관관계 상위 변수 기반 점수 계산 및 신뢰성 검증.

---

## 주요 결과
- **연속형 변수**: Annual_Premium 등에서 이상치를 제거하여 데이터 분포 개선.
- **범주형 변수**: Vehicle_Damage, Vehicle_Age 등이 응답과 높은 상관관계를 보임.
- **예측 모델**: 상관관계 높은 변수 기반 점수를 도출하고, Score의 신뢰성을 다양한 방법으로 검증.
- **시각화**: 데이터 분포와 상관관계를 시각적으로 확인하며 인사이트 도출.

---

## 사용 기술 및 라이브러리
- **언어**: Python
- **분석 라이브러리**: pandas, numpy, matplotlib, seaborn
- **모델링**: scikit-learn
- **데이터 전처리**: 데이터 이상치 제거 및 범주형 변수 처리
- **시각화**: matplotlib, seaborn

---
