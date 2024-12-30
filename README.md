
![image](https://github.com/user-attachments/assets/05fa4947-4226-4ef5-a26f-75e1ec9c4cdf)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)

# 1. 프로젝트 소개

## 프로젝트 목표
- 구직자들에게 AI 관련 기업과 채용에 관련된 데이터 및 서비스 제공
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## 주제 선정 배경

- AI 산업에 대한 관심이 높아짐에 따라 관련 기업들과 일자리 또한 증가하고 있다.
- 하지만 기존 채용사이트에서는 AI 기업과 채용의 정보를 따로 추려내기 어렵다.
- 이에 따라 AI 기업과 채용 데이터에 대한 심층 분석 및 전용 서비스에 대한 필요성을 인지하여 해당 주제를 선정하였다.


## 구성원 및 역할

|이름|업무|
|---|---|
|임주원<br/>(팀장)|프로젝트 총괄<br/>기업 정보 수집 및 데이터 분석 (잡플래닛)<br/>데이터 베이스 관리|
|김재현|기업 정보 수집 및 데이터 분석 (AI Landscape)<br/>기업 데이터 상관 관계 분석<br/>AI 기업 정보 제공 서비스 구현|
|이상범|채용 정보 수집 및 데이터 분석 (잡플래닛)<br/>채용 데이터 상관 관계 분석<br/>데이터 베이스 관리|
|장윤정|채용 정보 수집 및 데이터 분석 (잡플래닛)<br/>채용 데이터 시각화<br/>PPT 제작|

![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## ERD

![image](https://github.com/user-attachments/assets/fab48f6a-1fd5-4a45-bfe5-8671265e0f26)
![image](https://github.com/user-attachments/assets/854c229f-d71f-41fa-9514-121bb3a8bb9b)


## 개발 환경 및 사용 기술

| **구분**             | **상세**                                                                                                                                                                                                                                                                                                       |
|:--------------------:|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **개발 환경**         | ![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?logo=ubuntu&logoColor=white) ![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?logo=visual-studio-code&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?logo=jupyter&logoColor=white) ![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?logo=amazon-aws&logoColor=white) |
| **개발 언어**         | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)                                                                                                                                                                                                                                                                      |
| **DBMS**              | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)                                                                                                                                                                                                                                                           |
| **라이브러리**        | ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)                                                                                                                                            |
| **시각화 도구**       | ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white) ![Folium](https://img.shields.io/badge/Folium-77B829?logo=python&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?logo=google-maps&logoColor=white) |
| **웹 크롤링 및 스크래핑 도구** | ![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-FFD700?logo=beautifulsoup&logoColor=black)                                                                                                            |
| **협업**              | ![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=google-sheets&logoColor=white)                                                                              |





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


# 3. 기업 분석
 ## 데이터 수집 대상 선정
- 채용 사이트에서 기업을 검색하면 현재 채용 중인 정보만 표시된다.
- 'AI'로 검색해도 다양한 카테고리의 기업이 포함되어 AI 기업만의 정보를 얻기 어렵다.
- 완성도 높은 서비스를 위해 한국인공지능산업협회에서 4년간 선정한 기업들을 대상으로 데이터를 수집했다.
- 수집된 AI landscape(기업 기본 정보)와 잡플래닛(평점 등 추가 정보)을 종합하여 데이터 분석 및 시각화 진행
  
![main_visual_2024_pc](https://github.com/user-attachments/assets/a71ebe0c-be00-43af-b932-1afc973e18a5)
    

## AI 기업 정보 시각화
### 지역별 AI 기업 개수
- AI 기업의 대부분이 서울시와 성남시에 있다.
![image](https://github.com/user-attachments/assets/916bd215-7ae3-4dce-9e23-1abe7fc82749)


### 카테고리별 AI 기업 개수
- 자연어처리가 대세이다.
  
![image](https://github.com/user-attachments/assets/9d44e777-cf5d-4578-b62f-4956b86d3091)

## AI 기업 상관관계 분석
### 설립연도와 평점의 상관관계
- 상관관계 거의 없지만 최근에 생긴 AI 기업들의 평점이 높았다.
  
![image](https://github.com/user-attachments/assets/f375cc18-14b5-4ec1-b341-4b8ffe387ffa)


### 설립연도와 성장가능성의 상관관계
- 최근에 생긴 AI 기업이 성장가능성이 높다고 평가됐다.
  
![image](https://github.com/user-attachments/assets/ee41c576-5553-4bbc-a4f6-991bee82180f)

### 종업원수와 평점의 상관관계
- 상관관계 없다.
  
![image](https://github.com/user-attachments/assets/6b7fa0c3-a505-4ccd-97ad-1c510b712a83)

### 종업원수와 성장가능성의 상관관계
- 상관관계 거의 없지만 종업원수가 적은 AI 기업들의 성장가능성이 높다고 평가됐다.
  
![image](https://github.com/user-attachments/assets/5c03e577-ed80-455f-aaaf-c5a8d7d07f35)

## AI 기업 정보 제공 서비스 : AI JOBSORI
### 기능리스트
| **Function**       | **Description**                                                       |
|----------------|--------------------------------------------------------------|
| 기업 정보 제공 기능     | 1. 아이콘 클릭시 기업 정보 표시<br>    |
| 기업 필터링 기능     | 1. 카테고리<br>2. 시/구<br>3. 종업원수<br>4. 매출액<br>5. 평점  |
| 기업 검색 기능       | 1. 기업명 검색<br>2. 필터링 후 기업명 검색                    |
  
### 실행 화면

- 초기 화면
 
![image](https://github.com/user-attachments/assets/f7e33dea-c1b3-42ab-bebb-37b9e48b89e2)
  
- '모빌리티' 카테고리 필터링
 
![image](https://github.com/user-attachments/assets/e2295806-a0b7-424b-9dd2-39beccfcc47c)
  
- '챗봇', '강남구', '100명 이상', '100억 이상', '4점 이상' 필터링

![image](https://github.com/user-attachments/assets/2b3511bf-29ab-47cf-bbde-7ce6827e7ad5)
  
- 기업명 '에이아이' 포함하는 기업 검색

![image](https://github.com/user-attachments/assets/df13fa36-3ddd-4623-a476-56f553a481cc)
  
- '강남구', '4점 이상' 기업명 '에이아이' 포함하는 기업 검색

![image](https://github.com/user-attachments/assets/007aa74d-283a-4aa5-8336-070a1a4ca67e)
  
# __4. 결론__
  
## __결과 및 기대효과__

- 이번 프로젝트로 AI 구직자들이 궁금해할 흥미로운 주제를 분석하고, AI 기업 정보 제공 서비스의 프로토타입을 만들 수 있었다.
- AI 관련 산업뿐만 아니라 다양한 산업의 기업 정보까지 다룰 수 있는 서비스로 확장하면, 구직자들에게 편리하게 정보를 제공할 수 있을 것이다.

## __문제점 및 개선방안__

### 기업 정보의 부족 
- 특정 웹사이트에만 의존하다 보니 기업 정보가 부족했다. DART나 잡코리아 같은 다양한 플랫폼에서 더 많은 기업 정보를 가져오면, 더 신뢰성 있고 유용한 정보를 제공할 수 있을 것이다.

### 기업 정보와 채용 정보의 분리
- 현재 AI 기업에 대한 시각화 정보는 제공할 수 있었지만, 채용 정보를 같이 필터링하는 기능은 추가하지 못했다. 앞으로 데이터베이스를 더 확대하고 통합하면, 기업 정보와 채용 정보를 함께 제공하는 더 편리한 서비스를 만들 수 있을 것이다.


# 5. 발표자료

https://docs.google.com/presentation/d/10gtgD08JYPRTJuCugc3KuVbuZQonLtEF/edit?usp=sharing&ouid=109125789737068453465&rtpof=true&sd=true



