# Statistical Analysis Web Program

## Service Introduction

This web program offers various statistical analysis services. The main services currently provided are:

1. **Descriptive Statistics**: Summarizes and describes basic features of the data. Calculates measures such as mean, median, and standard deviation to understand data distribution and characteristics.
2. **T-Test**: 
   - **One-sample T-Test**: Tests if the mean of a single sample differs from a specific value.
   - **Paired-sample T-Test**: Tests the mean difference between two related samples.
   - **Independent-sample T-Test**: Tests the mean difference between two independent samples.
3. **ANOVA**: 
   - **One-way ANOVA**: Tests mean differences among multiple groups.
   - **Two-way ANOVA**: Tests effects of two independent variables and their interaction on a dependent variable.
   - **Multivariate ANOVA (MANOVA)**: Tests mean differences among groups on multiple dependent variables simultaneously.
4. **REGRESSION**: Models the relationship between an independent variable and a dependent variable through simple regression analysis.

### Technology Stack

- **Statistical Analysis Server**: Python FastAPI
- **Backend**: Golang
- **Frontend**: Next.js App Router

Website: [https://www.analyze-hub.com](https://www.analyze-hub.com)

** For the best experience, we recommend accessing the website on a desktop environment. **

### Demonstration Videos

#### Paired-sample T-Test Demonstration
![Paired-sample T-Test Demonstration](paired.mp4)

#### Two-way ANOVA Demonstration
![Two-way ANOVA Demonstration](two_way_anova.mov)

### TODO

1. Currently, user registration/login is implemented using bcrypt and base64. We plan to introduce SSO (Single Sign-On) with providers like Google, Apple, and Kakao in the future.
2. Implementing features to save analysis results as images or CSV files and generate textual summaries of the analysis results.

# 통계 분석 웹 프로그램

## 서비스 소개

이 웹 프로그램은 다양한 통계 분석 서비스를 제공합니다. 현재 제공되는 주요 서비스는 다음과 같습니다:

1. **기술통계분석**: 데이터의 기본적인 특성을 요약하고 설명합니다. 평균, 중앙값, 표준편차 등의 통계량을 계산하여 데이터의 분포와 특성을 파악합니다.
2. **T-Test**: 
   - **일표본 통계분석**: 단일 표본의 평균이 특정 값과 다른지 검정합니다.
   - **대응표본분석**: 두 관련 표본 간의 평균 차이를 검정합니다.
   - **독립표본분석**: 두 독립된 표본 간의 평균 차이를 검정합니다.
3. **ANOVA**: 
   - **일원분산분석**: 여러 그룹 간의 평균 차이를 검정합니다.
   - **이원분산분석**: 두 개의 독립 변수와 그 상호작용이 종속 변수에 미치는 영향을 검정합니다.
   - **다원분산분석(MANOVA)**: 여러 종속 변수에 대한 그룹 간의 평균 차이를 동시에 검정합니다.
4. **REGRESSION**: 단순 회귀 분석을 통해 독립 변수와 종속 변수 간의 관계를 모델링합니다.

### 사용된 기술 스택

- **통계 분석 서버**: Python FastAPI
- **백엔드**: Golang
- **프론트엔드**: Next.js App Router

웹사이트 주소: [https://www.analyze-hub.com](https://www.analyze-hub.com)

** 최적의 경험을 위해 데스크탑 환경에서 접속하는 것을 권장합니다. **

### 시연 영상

#### 대응표본 검정 시연
![대응표본 검정 시연](paired.mp4)

#### 이원분산분석 시연
![이원분산분석 시연](two_way_anova.mov)

### TODO

1. 현재 회원가입/로그인은 bcrypt와 base64를 함께 사용해서 사용하고 있으며, 추후에 Google, Apple, Kakao 등의 SSO를 도입할 예정입니다.
2. 분석 결과 이미지 / CSV 저장 및 분석 결과 텍스트 생성 기능을 구현할 예정입니다.
