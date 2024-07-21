# 이미지 하나 박기

# 👷 Co-Labor: 외국인 노동자를 위한 웹?사이트?
- 외국인 노동자들이 한국에서 안정적으로 정착하고 적응할 수 있도록 돕는 웹사이트
- 외국인 노동자들이 겪는 일자리, 정보 부족, 법률 문제 등을 해결하고, 다양한 지원 서비스를 제공
- 궁극적으로 한국 사회의 경제 활성화와 사회 통합에 기여

## ✨ 주요 기능
### 1️⃣ 채용 공고 및 기업 리뷰
&nbsp;다양한 직무, 경력, 고용 형태, 근무 지역 등을 포함한 상세한 채용 공고를 제공합니다. 사용자는 기업의 상세 페이지에서 기업 정보와 함께 다른 근로자들의 리뷰를 통해 기업의 신뢰도를 평가할 수 있습니다. 이를 통해 본인에게 적합한 직무와 신뢰할 수 있는 기업을 효율적으로 찾아 지원할 수 있습니다.

### 2️⃣ AI 검색 기능
&nbsp;DB에서 추출한 데이터를 기반으로 Word2Vec 모델을 학습시켜 유사 키워드를 생성합니다. 사용자가 입력한 키워드와 유사한 키워드를 통해 관련된 데이터를 보다 빠르고 정확하게 검색할 수 있습니다. 이를 통해 사용자는 필요한 정보를 신속하고 효율적으로 찾을 수 있습니다.

### 3️⃣ 법률 챗봇
&nbsp;OpenAI API 모델을 활용하여 외국인 노동자들이 직장에서 겪을 수 있는 법률적인 문제에 대해 도움을 받을 수 있는 법률 상담 챗봇을 제공합니다. 챗봇은 한국의 노동법과 관련된 다양한 질문에 신속하고 정확하게 답변하여 법적 문제를 해결하는 데 도움을 줍니다.

## 🔗 개발 진행 상황
- **Front-end** [FE Repository](https://github.com/Co-Labor-Project/Co-Labor-FE)
- **Back-end** [BE Repository](https://github.com/Co-Labor-Project/Co-Labor-BE)

## 🗂️ 시스템 아키텍처
![colabor drawio](https://github.com/user-attachments/assets/127e0d5d-714e-4416-9334-575a5e4a0209)

### 📚 기술 스택
- Front : HTML, React, css, js
- Back-end : spring
- 버전 및 이슈관리 : Github, Github Issues, Github Project
- 협업 툴 : Discord, Slack, [Notion](https://mixolydian-idea-627.notion.site/ba5857ecea9e498f9b94586421b27ca5)
- 서비스 배포 환경 : github?
- 디자인 : [Figma](https://www.figma.com/design/YddHONkDl0nqcbQVkUEVTa/%EA%B3%B5%EB%AA%A8%EC%A0%84?node-id=33-251&t=ocRWZPY412U61gb0-0)

# 표로 만들기
  
## 🗃️ ERD
![erd](https://github.com/user-attachments/assets/d8bdf38d-52bf-47f8-9e3d-bda802015754)
- erd 설명 넣을까?
- ?
- ?



## 💻 기능별 페이지 설명
### 📍 기업 정보
국세청 사업자등록정보 진위확인 및 상태조회 API를 활용하여 다양한 기업 정보를 제공합니다. 사용자는 기업 상세페이지에서 리뷰를 통해 기업의 신뢰도를 평가할 수 있습니다.

### 📍 채용 공고
다양한 직무, 경력, 고용 형태, 근무지역 등의 정보를 제공하여 적합한 채용 공고를 찾을 수 있습니다. 주요 업무, 자격 요건, 우대 사항, 채용 절차, 복지 및 혜택 등의 상세 정보를 통해 지원자들이 원하는 기업과 직무에 대해 정확히 이해할 수 있습니다.

### 📍 법률 상담 챗봇
외국인 근로자들이 직장에서 겪을 수 있는 법률적인 문제에 대해 도움을 받을 수 있는 법률 상담 챗봇 서비스를 제공합니다. 챗봇은 한국의 노동법과 관련된 다양한 질문에 신속하고 정확하게 답변해줍니다.

### 📍 근처 노동자 지원 센터 및 병원
긴급 상황이나 의료 도움이 필요할 때 근처에서 이용할 수 있는 노동자 지원 센터와 병원을 찾을 수 있는 기능을 제공합니다. 공공데이터와 네이버 지도 API를 이용하여 한눈에 확인할 수 있습니다.

### 📍 AI 검색 기능
MySQL 데이터베이스에서 추출한 데이터를 기반으로 Word2Vec 모델을 학습하여 유사 키워드를 생성합니다. 사용자가 입력한 키워드와 유사한 키워드를 통해 관련된 데이터를 검색하여 더 빠르고 정확하게 원하는 정보를 찾을 수 있습니다.

## 🧑‍💻 팀원 구성

<div align="center">

| **김도현** | **김문기** | **정한울** | **조준화** |
| :------: |  :------: | :------: | :------: |
| <img src="https://github.com/Co-Labor-Project/demo-repository/blob/main/img/kdhqwe1030_img.jpg" height=240 width=180> <br/> [@kdhqwe1030](https://github.com/kdhqwe1030) | <img src="https://github.com/Co-Labor-Project/demo-repository/blob/main/img/mk-isos_img.jpg" height=240 width=180> <br/> [@mk-isos](https://github.com/mk-isos) | <img src="https://github.com/Co-Labor-Project/demo-repository/blob/main/img/jho7535_img.jpg" height=240 width=180> <br/> [@jho7535](https://github.com/jho7535) | <img src="https://github.com/Co-Labor-Project/demo-repository/blob/main/img/jjj5306_img.jpg" height=240 width=180> <br/> [@jjj5306](https://github.com/jjj5306) |




</div>
