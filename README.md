## 🙋‍♂️ 안녕하세요, 문제 해결의 본질에 집중하는 AI/SW 개발자 배수한입니다

- **"AI가 할 수 없는 '본질적 문제 정의'에 강점이 있습니다."**
- 데이터의 양보다는 의미를 우선하며, 다양한 활용 관점을 통해 효율적인 솔루션을 도출합니다.
- 빠르게 변하는 트렌드보다 사용자 경험과 신뢰 등 '변하지 않는 가치'를 중심으로 지속 가능한 시스템을 설계하고자 합니다.
- 메타인지를 기반으로 스스로 점검하고, 더 나은 전략을 찾아 꾸준히 성장하고 있습니다.

## 🛠️ Tech Stack

### 💻 Languages
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>

### 🧠 AI
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/RAG-4B0082?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/LangGraph-1C1C1C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logo=chroma&logoColor=white"/> <img src="https://img.shields.io/badge/Prompt_Engineering-00A67E?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/TTS-4B0082?style=flat-square&logo=soundcharts&logoColor=white"/> 

<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/> <img src="https://img.shields.io/badge/MediaPipe-00A67E?style=flat-square&logo=google&logoColor=white"/>

### ⚙️ Backend & DB
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>

### 🔧 Tools
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/>

## 🚀 Projects

<details>
<summary><b>SmartChain-HD</b> | AI 기반 협력사 리스크 관리 플랫폼 <i>(2026.02 ~)</i></summary>

<br>

**"HD현대중공업 협력사 컴플라이언스 자동검증 및 규정 Q&A 챗봇 구축"**

* **🎯 Situation & Task (배경 및 목표)**
  * 협력사 제출 증빙 수기 검토 프로세스의 누락/판단 편차/처리 지연 문제 정의
  * 컴플라이언스 사전 리스크 필터링 체계 및 규정 질의 대응 채널 구축 목표 설정
* **💡 Action (나의 역할 및 해결 과정)**
  * **컴플라이언스 파트:** PDF/XLSX/이미지 자동 분류, OCR·데이터 추출, 슬롯 기반 검증, 교차검증, 최종 판정까지의 6단계 파이프라인 설계 및 구현
  * **챗봇 파트:** 규정 문서 임베딩·적재, 벡터 검색+BM25 재정렬, 대화 맥락 기반 질의 재작성 적용 RAG Q&A API 설계 및 구현
* **📈 Result (성과 및 배운 점)**
  * 문서 검토 프로세스 표준화 및 핵심 수작업 단계 자동화
  * 평균 검토시간 **10분 → 1분 (90% 단축)**, 보완요청 재작업률 **30% → 5%** 개선
  * 규정 문의 응답시간 평균 **15분 → 5초** 개선
  * OCR/LLM/검색 실패 대비 fallback 구조를 통한 운영 안정성 확보 경험 축적
* **🛠️ Tech:** Python, FastAPI, OpenAI API, ChromaDB, LangChain, Pandas, PyMuPDF, Naver Clova OCR, BM25(rank-bm25), Streamlit, Pydantic, httpx
* 🔗 [GitHub Repository](https://github.com/SmartChain-HD)
</details>

<details>
<summary><b>ai_lecture-generator</b> | AI 강사 ppt 기반 강의 영상 생성 <i>(2025.11 ~)</i></summary>

<br>

**"PPT 자료만 입력하면 AI 강사가 자동으로 내용을 설명하는 강의 영상 생성 서비스를 개발했습니다."**

* **🎯 Situation & Task:** 기존 영상 제작의 비효율성을 개선하기 위한 자동화 파이프라인 기획
* **💡 Action (나의 역할 및 해결 과정):**
  * (PPT 내용 추출 및 요약 로직 구현 등 본인의 핵심 기여)
  * (TTS나 영상 생성 모델 연동 등)
* **📈 Result (성과 및 배운 점):** (파이프라인 구축 완료, 특정 문제 해결 경험 등)
* **🛠️ Tech:** (사용 기술 작성)
* 🔗 [GitHub Repository](https://github.com/uh004/ai_lecture-generator)
</details>

<details>
<summary><b>ai_interview_agent</b> | 이력서 기반 AI 면접관 <i>(2025.10 ~)</i></summary>

<br>

**"사용자의 이력서 데이터를 분석하여 맞춤형 질문을 던지는 AI 면접관 서비스를 구현했습니다."**

* **🎯 Situation & Task:** 개인화된 면접 경험을 제공하기 위한 LLM 프롬프트 및 시스템 설계
* **💡 Action (나의 역할 및 해결 과정):**
  * (이력서 데이터 파싱 및 RAG/프롬프트 엔지니어링 수행 내역 등)
* **📈 Result (성과 및 배운 점):** (AI 응답 품질 개선 경험 등)
* **🛠️ Tech:** (사용 기술 작성)
* 🔗 [GitHub Repository](https://github.com/uh004/ai_interview_agent)
</details>

<details>
<summary><b>ShowRoom</b> | 3D 공간 재구성 서비스 기획 <i>(2025.07 ~)</i></summary>

<br>

**"2D 이미지만으로 3D 공간을 재구성하는 혁신적인 서비스 아이디어를 기획하고 시스템 구조를 설계했습니다."**

* **🎯 Situation & Task:** 공간 재구성의 진입 장벽을 낮추기 위한 2D to 3D 변환 아이디어 도출
* **💡 Action (나의 역할 및 기획 과정):**
  * KOBERT, OpenCV 등을 활용한 기술적 실현 가능성 검토 및 시스템 아키텍처 설계
  * 핵심 기능 명세 및 UI/UX 시나리오 기획
* **📈 Result (성과 및 배운 점):** (기획력 및 기술 설계 역량 강화)
* **🛠️ Tech:** Python, PyTorch, TensorFlow, KOBERT, OpenCV 등
* 🔗 [GitHub Repository](https://github.com/uh004/ShowRoom)
</details>

<details>
<summary><b>Eating_shot</b> | 당뇨병 환자용 식단 조절 및 케어 서비스 <i>(2024.07 ~ 2024.11)</i></summary>

<br>

**"당뇨병 환자들의 실질적인 건강 관리를 돕는 식단 조절 및 케어 백엔드 시스템을 구축했습니다."**

* **🎯 Situation & Task:** 환자 맞춤형 식단 데이터 처리 및 안정적인 서비스 제공 필요
* **💡 Action (나의 역할 및 해결 과정):**
  * (FastAPI/Django를 활용한 API 설계 및 구현)
  * (Docker, Redis를 활용한 인프라 세팅 및 성능 최적화 등)
* **📈 Result (성과 및 배운 점):** (안정적인 백엔드 시스템 구축 경험)
* **🛠️ Tech:** Django, FastAPI, Docker, Redis 등
* 🔗 [GitHub Repository](https://github.com/uh004/Eating_shot)
</details>

<details>
<summary><b>2025 GovTech</b> | 공공 기술 혁신 아이디어 기획 <i>(2025.11)</i></summary>

<br>

**"공공 부문의 기술적 문제 해결을 위한 혁신적인 아이디어를 기획하고 구체화했습니다."**

* **🎯 Situation & Task:** (어떤 공공 문제를 타겟팅 했는지 작성)
* **💡 Action (나의 기여):** 아이디어 기획 및 실행 방안 구체화
* **📈 Result:** (경진대회 제출 및 기획안 완성)
</details>

<details>
<summary><b>"미술치료" 논문</b> | 한국실천공학교육학회 발표</summary>

<br>

**"최근 10년간의 관련 논문 2,972편을 크롤링하고 텍스트 마이닝하여 미술치료 연구 동향을 분석했습니다."**

* **🎯 Situation & Task:** 방대한 문헌 데이터 속에서 유의미한 연구 트렌드 도출 필요
* **💡 Action (분석 과정):**
  * Python 기반 웹 크롤링으로 약 3천 편의 논문 데이터 수집
  * TF-IDF, Word2Vec, Keyword Network, WordCloud를 활용한 텍스트 마이닝 및 시각화 수행
* **📈 Result (성과):** 분석 결과를 바탕으로 논문 작성 및 한국실천공학교육학회 발표/게재 완료
* **🛠️ Tech:** TF-IDF, Word2Vec, 텍스트 마이닝 등
</details>

## 🎓 Education & Training

| 교육/훈련명 | 주관/기관 | 기간 |
|---|---|---|
| **인공지능소프트웨어과** (전공심화) | 동양미래대학교 | `2025.03 ~ 2026.02` |
| **인공지능소프트웨어과** (전문학사) | 동양미래대학교 | `2022.03 ~ 2025.02` |
| **KT 에이블스쿨 8기** (AI 개발자 트랙) | KT | `2025.09 ~ 2026.03` |
| **지능정보 SW 아카데미** (AI 실무 역량 강화 및 프로젝트) | 고려대학교 | `2025.02 ~ 2025.06` |

## 🏆 Awards

| 대회명 / 명칭 | 수상내역 | 주관기관 | 일자 |
|---|---|---|---|
| 지능정보 우수프로젝트 경진대회 | **대상** | 정보통신기획평가원 | `25.06.19` |
| 한국경제신문 아이디어 경진대회 | **대상** | 한국경제신문 | `25.04.25` |
| 2024 스마트 DATA/AI 경진대회 | **최우수상** | 동양미래대학교 | `24.11.26` |
| 동양미래EXPO | **장려상** | 동양미래대학교 | `24.11.25` |
| 동양미래EXPO | **우수상** | 동양미래대학교 | `23.11.30` |
| 깃허브 저장소 구축 경진대회 | **최우수상** | 동양미래대학교 | `22.11.30` |
| 데이터분석 경진대회 | **장려상** | 동양미래대학교 | `22.11.30` |

## 📜 Certifications

| 자격증명 | 발급기관 | 취득일자 |
|---|---|---|
| **AICE Associate** | KT, 한국경제신문 | `25.05.19` |
| **정보처리산업기사** | 한국산업인력공단 | `24.09.10` |
| **ADsP** (데이터분석준전문가) | 한국데이터산업진흥원 | `23.09.15` |

<div align="center">
  </div>
