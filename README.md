
![image](https://github.com/user-attachments/assets/05fa4947-4226-4ef5-a26f-75e1ec9c4cdf)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)

# 1. 프로젝트 소개

## 주제 선정 배경

![image](https://github.com/user-attachments/assets/4c180284-1104-424c-9bd6-50caebe7a13c)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## 구성원 및 역할

|이름|업무|
|---|---|
|임주원<br/>(팀장)|전반적인 프로젝트 진행상황 관리<br/>기업 정보 수집 및 데이터 분석 (잡플래닛)<br/>데이터 베이스 관리|
|김재현|기업 정보 수집 및 데이터 분석 (AI Landscape)<br/>기업 데이터 시각화<br/>AI 기업 정보 제공 서비스 구현|
|이상범|채용 정보 수집 및 데이터 분석 (잡플래닛)<br/>기업&채용 데이터 상관 관계 분석<br/>데이터 베이스 관리|
|장윤정|채용 정보 수집 및 데이터 분석 (잡플래닛)<br/>채용 데이터 시각화<br/>PPT 제작|

![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## ERD

![image](https://github.com/user-attachments/assets/fab48f6a-1fd5-4a45-bfe5-8671265e0f26)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## 활용 기술

|구분|상세|
| :-------: |:----------------------------------------------------------------------:|
| 개발 환경 | ![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?logo=ubuntu&logoColor=white) ![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?logo=visual-studio-code&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)|
|Tools|![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?logo=amazon-aws&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-FFD700?logo=beautifulsoup&logoColor=black) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?logo=python&logoColor=white) ![Folium](https://img.shields.io/badge/Folium-77B829?logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?logo=google-maps&logoColor=white)|
|협업|![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=google-sheets&logoColor=white)|

![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


# 2. 채용 분석
## 지역별 채용중인 AI 기업 수
- AI 기업이 주로 성남시 분당구(판교)와 강남구 쪽에 많이 밀집하고 있음을 확인함
- 전국을 기준으로 봤을 때, AI기업은 서울에 몰려 있는 것을 확인할 수 있음

![image](https://github.com/user-attachments/assets/33a37ddb-a308-4bbf-897b-b89d80ea9e62)
![image](https://github.com/user-attachments/assets/79b6b782-3b3f-45a3-964f-d5c40d5dcf40)
![image](https://github.com/user-attachments/assets/6f452119-afd4-437d-b2f8-7aad19342d52)

## 경력별 채용 현황
- AI 산업에서 신입사원 채용 건수는 5건 미만으로, 매우 적은 비율로 채용이 이뤄지고 있음
- 경력직에서는, 경력이 3년 이상인 사람을 가장 많이 뽑는 것으로 확인됨
  
![image](https://github.com/user-attachments/assets/5f33ba4e-dc71-4a17-afdf-6dff919328c8)
![image](https://github.com/user-attachments/assets/a233ca85-1673-4a47-ae11-a6f2f5404054)

## 산업 및 직무별 채용 현황 
- 산업과 직무별로 채용 현황을 봤을 때, IT 계열에서 압도적으로 채용이 많이 이뤄지고 있음을 확인할 수 있음
  
![image](https://github.com/user-attachments/assets/2712103b-2e9b-4609-bff6-ce2762e06275)
![image](https://github.com/user-attachments/assets/e1a4d420-d774-4bea-9aa2-c35758ae4d2e)

## 데이터 관계 분석
### 연봉 & 워라벨 
- 상관관계 분석을 통해 대부분의 직업에서 연봉이 높을 수록 워라밸이 안 좋은 것을 확인할 수 있었음
  
![image](https://github.com/user-attachments/assets/374abc89-faf6-41de-bf66-a4bd607c4dbb)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)

### 사내문화 & 기업평점
- 사내문화가 좋으면 대부분 기업의 평점이 좋은 것을 확인할 수 있었음
  
![image](https://github.com/user-attachments/assets/21a38b2f-7934-44d1-956c-e2e5f592a832)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)

### 복지개수 & 복지평점
- 복지 개수가 많다고 복지 평점이 좋은 건 아닌 것 같음
- 복지가 많은 것 보다 복지의 질이 더 중요하다는 것을 확인할 수 있음
  
![image](https://github.com/user-attachments/assets/12cd1e64-8685-45b4-8ea0-bc22f3ad9afa)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)
