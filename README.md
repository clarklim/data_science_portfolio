Table of Contents
=================

   * [Personal Projects](#Personal-Projects)
      * [Hardware / OS Platform Used](#hardware--os-platform-used)
      * [Contents](#contents)
         * [Titanic_Machine Learning from Disaster](#Titanic_Machine-Learning-from-Disaster)
         * [Bike Sharing Demand ](#Bike-Sharing-Demand )
         * [Startup Data analysis_Healthcare](#Startup-Data-analysis_Healthcare)
         * [Startup Data analysis_Freelancer Openmarket](#Startup-Data-analysis_Freelancer-Openmarket)
         * [Startup Data analysis_Fashion Shoppingmall Recommendation](#Startup-Data-analysis_Fashion-Shoppingmall-Recommendation)
         * [Otto Group Product Classification Challenge](#Otto-Group-Product-Classification-Challenge)

# Personal Projects

본 저장소는 개인적으로 진행한 프로젝트와 Kaggle에 참여했던 프로젝트,
고려대학교 컴퓨터정보통신 대학원에서 진행한 프로젝트를 정리하는 곳입니다. 
내용과 관련한 문의는 언제든지 clarklimr@korea.ac.kr 로 해주시면 감사하겠습니다.

This repository is a personal project, a project that participated in the Kagle,
It includes a project conducted by the Department of Big Data Convergence at Korea University.
Please fell free to contact me at clarklimr@korea.ac.kr

몇몇 프로젝트 자료에서 데이터가 누락된 경우는 용량 문제나 공개가 불가능하기 때문입니다.

If some project material such as data are missing, it is not possible to upload because the data exceeded the file size limit or the data cannot be public.


## Portfolio

[PDF](https://github.com/clarklim/data_science_portfolio/blob/master/portfolio.pdf) (Updated 19.09.29)

본 포트폴리오는 프로젝트 중 일부만을 간략히 다루고 있습니다. 자세한 프로젝트 내용이나 수록되어 있지 않은 내용은 본 깃허브 저장소를 통해서 확인해주시기 바랍니다.

This portfolio covers briefly only some of my projects. Please check this repository for the details of the projects or the contents that are not included in this portfolio. 

## Hardware / OS Platform Used

- 13.3" Samsung Notebook9 2.5GHz Core i5-7200U, 8GB Ram
- Windows10
- Python 3.73 with `jupyter==1.0.0`
  - `numpy==1.16.2`
  - `pandas==0.24.2`
  - `sklearn==0.20.3`
  - `scipy==0.2.1`
  - `statsmodels==0.9.0`
  - `matplotlib==3.0.3`
  - `seaborn==0.9.0`
  - `lightgbm=2.3.1`
  - `tensorflow=1.9.0`
- R 3.5.3 with RStudio 1.1.463

## Contents

### Titanic_Machine Learning from Disaster
(April 2019, Kaggle competition)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Titanic%Machine%Learning%from%Disaster/titanic_randomforest.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Titanic%Machine%Learning%from%Disaster/titanic_summary.pdf)

- https://www.kaggle.com/c/titanic

- 캐글의 Titanic: Machine Learning from Disaster 경진대회에 참가 했습니다. 타이타닉 해상사고 당시의 기록을 담아둔 Encyclopedia Titanica의 데이터를 참고하여, 유사한 해상 사고가 발생했을 시 어떤 승객이 생존하며, 또한 어떤 승객이 사망하는지를 예측하는 예측 모델을 만들었습니다.탐험적 데이터 분석(Exploratory Data Analysis)과 RandomForest를 통해 예측모델을 구현해보았으며 최종적으로 캐글 컴피티션에서 상위 6%를 기록했습니다.

- I participated in Kaggle's 'Titanic: Machine Learning from Disaster' contest. 
Based on the data from Encycledia Titanica, which contained records from the Titanic maritime accident, we created a predictive model that predicts which passengers will survive in the event of a similar maritime accident and which passengers will die. I've implemented the predictor model through 'Explory Data Analysis' and 'RandomForest'.Finally I've ranked the top 6% in the Kaggle Compute.


### Bike Sharing Demand 
(May 2019, Kaggle competition)


- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Bike%Sharing%Demand/bike-sharing-demand_LightGBM.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Bike%Sharing%Demand/bike-sharing-demand_summary.pdf)

- https://www.kaggle.com/c/bike-sharing-demand

- 워싱턴 D.C 소재의 자전거 대여 스타트업 Capital Bikeshare의 데이터를 활용하여, 특정 시간대에 얼마나 많은 사람들이 자전거를 대여하는지 예측했습니다. 탐험적 데이터 분석(Exploratory Data Analysis)과 RandomForest(Coarse & Finer Search), lightGBM을 통해 예측모델을 구현해보았으며 최종적으로 캐글 컴피티션에서 상위 2.9%를 기록했습니다.

- Using data from Capital Bikeshare, a bicycle rental startup based in Washington, D.C., we predicted how many people rent bicycles at a certain time. I've implemented the predictor model through 'Explory Data Analysis' and 'RandomForest(Coarse & Finer Search)', 'lightGBM'. Finally I've ranked the top 2.9% in the Kaggle Compute.

### Startup Data analysis_Healthcare
(June 2019, 데이터 분석 프로젝트)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Healthcare)/startup-healthcare_analysis.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Healthcare)/startup-healthcare_analysis.pdf)

- 헬스케어 스타트업 'n***'의 회원 정보와 행동 데이터를 정리하고 분석하였습니다. Data Cleaning을 진행한 뒤, Pandas를 통해 데이터를 분석했습니다. 
아래와 같이 질문을 설정하고 데이터에 기반한 솔루션을 제시하였습니다.
 * 'N***'을 사용하는 무료 사용자 중, 유료 사용자로 전환할 확률이 가장 높은 연령/성별은 어디인가?
 * 'N***'을 사용하는 무료 사용자들은 주로 조건하에 유료 사용자로 전환하는가?
 * 유료 사용자를 코칭하는 코치 중, 어느 코치가 가장 만족도가 높은가? 

- I compiled and analyzed the membership information and behavior data of the 'n***' healthcare startup. After Data Cleaning, I analyzed the data through Pandas. 
The following hypotheses have been answered based on data:
* Among free users using 'N***', which age/sex is the most likely to switch to paid users?
* When do free users usually switch to paid users?
* Among coaches coaching paid users, which coach is the most satisfactory

### Startup Data analysis_Freelancer Openmarket
(June 2019, 데이터 분석 프로젝트)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Openmarket))/startup-openmarket_analysis.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Openmarket)/startup-openmarket_analysis.pdf)

- 프리랜서 오픈마켓 서비스 k****의 데이터를 분석하기 전 가장 중요한 과정인 데이터 클리닝(Data Cleaning)을 맡아 진행했습니다. 웹, 아이폰, 안드로이드등 다앙한 디바이스와 OS로 서비스를 이용하고 있는 사용자의 웹,앱 행동 데이터를 정리한 뒤, pandas 의 merge나 concat등을 활용해 하나로 묶어주는 작업을 진행했습니다. 

- Before analyzing the data from the freelance open market service "k****," I was responsible for the most important process, Data Cleaning. After organizing the web and app behavior data of the users who are using the service with the web, iPhone, and Android devices and the OS, I used pandas's 'merge' and 'concat' to bring them together.

### Startup Data analysis_Fashion Shoppingmall Recommendation
(July 2019, 데이터 분석 프로젝트)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Fashion))/startup-fashion_analysis.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Startup%Data%Analysis(Fashion)/startup-fashion_analysis.pdf)

- 패션 쇼핑몰 추천 스타트업 'z*****'의 로그 데이터를 바탕으로 매출 분석 등 데이터 탐색을 진행 하였습니다. 
 * 데이터베이스에서 SQL을 통해 고객 정보, 거래 정보, 상품 정보, 그리고 고객의 행동 정보를 로드하여, 데이터 시각화를 통해 데이터를 이해하고 분석하는데 중점을 두었습니다. 
 * 로그 데이터분석의 핵심 수치(page duration, session, 체류 시간)를 구하고  이를 위한 전처리를 진행했습니다. 매출개선을 위한 인사이트를 얻는데 목적을 두고 데이터 분석을 진행 했습니다. 

- Based on the log data from the fashion mall-recommended startup 'z***', I conducted a sales analysis and other data exploration.
 * Through SQL in the database, I loaded customer information, transaction information, product information, and customer behavior information. I focused on understanding and analyzing data through data visualization.
 * I obtained key values of log data analysis (page duration, session, duration time) and conducted pre-processing. I conducted a data analysis with the aim of obtaining Insight to improve sales.

### Otto Group Product Classification Challenge
(August 2019, Kaggle competition)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/Otto%Group%Product%Classification%Challenge/otto-group-product-classification-challenge.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/Otto%Group%Product%Classification%Challenge/otto-group-product-classification-challenge.pdf)

- https://www.kaggle.com/c/bike-sharing-demand

- 세계 최대의 전자상거래 회사 중 하나인 Otto Group에서 주최하는 Otto Group Product Classification Challenge 경진대회에 참여했습니다. 
데이터셋으로 익명화(anonymization)된 상품 정보를 제공하는데, 이 데이터를 통해 주어진 상품 카테고리(target)를 예측했습니다. 머신러닝 모델은 Random Forest,  Gradient Boosting Machine(sklearn), LightGBM을 활용하여 세가지 모델을 비교했습니다. 최종 LightGBM을 적용하였으며, 중요 Hyperparameter(트리의 깊이, 갯수 등)는 Random Search를 통해 동시에 튜닝하였습니다.

- I participated in the Otto Group Product Classification Challenge hosted by Otto Group, one of the largest e-commerce companies in the world.
Kaggle has provided an anonymous product dataset.
I predicted product categories with this dataset.
I compared three machine learning models using Random Forest, Gradient Boosting Machine (Sklearn), and LightGBM. I finally applied LightGBM and tuned important Hyperparameters (depth of tree, count of tree, etc.) through Random Search.