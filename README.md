## Hi there 👋

안녕하세요, 컴퓨터·인공지능공학부에서 AI/ML에 집중하고 있는 개발자 Kwon입니다.  
Python 기반 데이터 분석과 머신러닝, 그리고 웹 API 개발을 중심으로 공부하며, 실전 프로젝트로 날씨 웹 서비스와 **부산 부동산 데이터 분석 파이프라인**을 진행해왔습니다.

---

## 🎓 전공 / 관심 분야

- 전공: 컴퓨터·인공지능공학부 / 고신뢰성 인공지능 반도체 융합 전공
- 관심 분야:
  - 머신러닝·데이터 분석, 엔지니어링 파이프라인 설계
  - MLOps, 모델 서빙(REST API 기반)
  - 네트워크·인프라 기본, API 연동 및 자동화
  - **데이터 파이프라인(ETL) + FastAPI 분석 결과 서빙**

---

## 🛠 Tech Stack

- Languages: Python, C++
- ML / Data: scikit-learn, XGBoost, Optuna, pandas, NumPy, **PostgreSQL**, Kaggle 실습 경험
- Backend: Flask, **FastAPI**, OpenWeather API 연동 경험
- Tools: Git, GitHub, VS Code, Jupyter Notebook, Google Colab, **Docker Compose**, macOS (M3)
- Etc: 네트워크 기초(DHCP, NAT, DDNS, VPN, 패킷 캡처 등)

### Skill Badges

![Skills](https://skillicons.dev/icons?i=python,cpp,git,github,vscode,docker,postgresql,fastapi)

---

## 💻 관심 개발 분야

- AI·머신러닝 모델링 및 서빙
- 데이터 파이프라인·MLOps, 모델 배포 자동화
- 웹 서비스(간단한 대시보드, API 기반 서비스)
- **ETL 파이프라인 + Docker 컨테이너화 + REST API 서빙**

---

## 📫 Contact

<div align="center">
  <a href="mailto:ksh03616@gmail.com">
    <img src="https://img.shields.io/badge/Email-ksh03616@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" style="margin: 0 10px 12px 0;" />
  </a>
  <a href="https://github.com/pttnekh">
    <img src="https://img.shields.io/badge/GitHub-pttnekh-181717?style=for-the-badge&logo=github&logoColor=white" style="margin: 0 10px 12px 0;" />
  </a>
  <a href="https://deluxe-rubidium-ea3.notion.site/Kwon-2c17174f477d8171b546fa887cc70045?pvs=143">
    <img src="https://img.shields.io/badge/Notion-Resume-000000?style=for-the-badge&logo=notion&logoColor=white" style="margin: 0 0 12px 0;" />
  </a>
</div>





---

## 🚀 현재 진행 중인 프로젝트

### 🌤 오늘의 하늘 (Today’s Sky)

간단하고 직관적인 UI로 날씨 정보를 제공하는 웹 서비스입니다.  
Flask 백엔드와 공공/외부 날씨 API를 연동해 현재 날씨, 단기·주간 예보, 공기질 정보를 한 번에 조회할 수 있습니다.

- GitHub: [https://github.com/OSS-teamproject-Todays-sky/todays-sky.git](https://github.com/OSS-teamproject-Todays-sky/todays-sky.git)

#### 프로젝트 목적

- 기존 날씨 서비스의 광고 과다·복잡한 UI 문제를 개선해, 필요한 정보만 직관적으로 제공
- OpenWeather 및 공공데이터 API를 활용하여 현재 날씨·예보·미세먼지 등을 통합 제공

---

### 🏠 부산 부동산 분석 파이프라인 (Busan RealEstate Analytics Pipeline)

**MP1→MP2→MP3 완성된 3단계 데이터 파이프라인** 프로젝트. 부산 아파트 거래 데이터를 수집→변환→FastAPI로 분석 결과 API 서빙까지 구현했습니다.

- GitHub: [https://github.com/pttnekh/busan-realestate-analytics-pipeline](https://github.com/pttnekh/busan-realestate-analytics-pipeline)
- **Tech**: Python, PostgreSQL, FastAPI, Docker Compose
- **구현 내용**:
  - MP1: 부동산 공공데이터 수집
  - MP2: `analytics.apartment_transactions` 테이블 변환
  - **MP3: `/api/stats/busan` 구별 평균 거래가 분석 API (>?gu=26350 필터링)**

#### API 데모

```bash
curl http://localhost:8000/api/stats/busan
→ {"status":"success","data":[{"gu":"26350","avg_deal_amount":67357,...}]}
```


---

## 🎯 프로젝트 내 역할

### 오늘의 하늘 – 커미터 / 백엔드·API 담당

- 역할: 커미터(Committer) – 백엔드/API 중심 개발과 문서화 담당
- 수행 업무:
  - OpenWeather One Call / Air Pollution API, 기상청 단기예보 API 연동 및 예외 처리
  - Python + Flask 기반 백엔드 설계, 날씨/미세먼지 데이터를 통합한 JSON 응답 포맷 설계 및 구현
  - API 사용 예시, 응답 예시(JSON) 등을 포함한 README 문서 작성 및 정리

### 부산 부동산 분석 파이프라인 – **주 개발자 (Solo)**

- **3단계 파이프라인 설계/구현**: 데이터 수집→변환→FastAPI 분석 API 서빙
- Docker Compose로 PostgreSQL + API 통합 실행 환경 구축
- **구별 평균 거래가 분석** + `?gu=` 필터링 + `/health` 헬스체크 완성

---

## 📊 GitHub 활동

### 🔹 GitHub Stats & Trophy

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=pttnekh&theme=tokyonight)](https://git.io/streak-stats)


### 🔹 최근 활동 / 학습용 저장소

- **부산 부동산 분석 파이프라인**: FastAPI + Docker + PostgreSQL 데이터 파이프라인 (MP3 완성)
- Kaggle 대회용 ML 실험 레포지토리 (XGBoost, VotingClassifier, Optuna 튜닝 등)
- 오늘의 하늘: Flask + 공공/외부 날씨 API 연동, README에 API 사용법·응답 예시 정리

---

## 🧭 앞으로의 기술 로드맵

- PyTorch, TensorFlow를 활용한 딥러닝 기초 및 비전·해석가능성 프로젝트
- **FastAPI 기반 ML 서빙, Docker·GitHub Actions를 활용한 MLOps 파이프라인 심화**
- 오디오 DSP + ML 결합(JUCE 기반 플러그인, 톤 모델링) 프로젝트 도전
- AI를 보조 도구로서 어떻게 활용할 것인가?
