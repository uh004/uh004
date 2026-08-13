## 🙋‍♂️ 안녕하세요 문제 해결의 본질에 집중하는 AI Engineer 배수한입니다

- 기업의 업무 문제를 이해하고, 복잡한 과정을 해결 가능한 단계로 나누어 AI를 적용하는 방법을 설계합니다.
- 필요한 기술과 도구를 유연하게 활용해 핵심 기능을 실제로 작동하는 흐름으로 구현하고, 문제가 발생했을 때 원인을 확인하고 개선할 수 있는 구조를 만드는 것을 중요하게 생각합니다.
- AI가 생성한 결과를 그대로 전달하기보다, 사용자가 결과를 확인할 수 있도록 판단 기준과 근거를 함께 제공하는 서비스를 만들고자 합니다.

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
<summary><b>SmartChain-HD</b> | AI 기반 협력사 리스크 관리 플랫폼 <i>(2025.12.29 ~ 26.02.20)</i></summary>

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
<summary><b>ai_lecture-generator</b> | AI 강사 ppt 기반 강의 영상 생성 <i>(2025.11.10 ~ 2025.11.13)</i></summary>

<br>

**"PPT 자료만 입력하면 AI 강사가 자동으로 설명하는 강의 영상·퀴즈 생성 서비스 개발"**

* **🎯 Situation & Task (배경 및 목표)**
  * 기존 PPT 기반 강의 제작의 반복 수작업(요약 작성, 대본 작성, TTS 녹음, 영상 편집, 퀴즈 제작) 비효율 문제 정의
  * PPT 1개 입력만으로 강의 콘텐츠를 End-to-End로 생성하는 자동화 파이프라인 구축 목표 설정
* **💡 Action (나의 역할 및 해결 과정)**
  * **파이프라인 오케스트레이션:** LangGraph 기반 파싱 → 검색 보강 → 페이지 요약 → 스크립트 생성 → TTS → 슬라이드 영상 생성 → 병합 → 퀴즈 생성의 8단계 워크플로우 구현
  * **PPT 분석 파트:** 슬라이드별 텍스트/표/이미지 추출 및 PPT→PNG 변환(LibreOffice+Poppler) 자동화
  * **RAG 보강 파트:** 슬라이드당 최대 4개 질의 생성, 검색 결과 가중치(유사도 0.5/신뢰도 0.3/충실도 0.2) 재정렬 및 중복 제거 로직 구현
  * **강의 생성 파트:** 대본 맥락을 반영한 스크립트 생성, OpenAI TTS 연동 및 음성 속도 제어(0.8x~2.0x UI) 구현
  * **영상 생성 파트:** 이미지와 음성을 결합해 1920x1080 MP4 생성 후 전체 강의 영상 자동 병합
  * **학습 보조 파트:** 대본 기반 4지선다형 퀴즈(10문항) 자동 생성 프롬프트 설계 및 Gradio 인터랙티브 풀이 UI 구현
  * **안정성 강화:** 검색 및 TTS 보이스 fallback, FFmpeg 재시도(1회), 실패 슬라이드 추적 로직 적용
* **📈 Result (성과 및 배운 점)**
  * PPT 1개 입력으로 요약/대본/TTS/영상/퀴즈까지 한 번에 생성되는 파이프라인을 완성해, 강의 제작의 분절된 수작업 단계를 단일 플로우로 통합
  * 샘플 3장 기준 영상 생성 성공률 100%(3/3) 달성 (FFmpeg 재시도, TTS 보이스 fallback, 실패 슬라이드 추적을 통해 실패를 전체 중단이 아닌 부분 복구로 전환)
  * 169.2초 강의 영상 및 10문항 퀴즈를 자동 생성하며, **슬라이드 위치 기반 스크립트 규칙(첫 장/중간/마지막)**과 이전 대본 맥락 반영으로 설명 흐름의 일관성 개선
  * RAG 단계에서 검색 결과를 그대로 쓰지 않고 유사도·도메인 신뢰도·콘텐츠 충실도 재점수화 및 중복 제거를 적용해, 노이즈를 줄이고 출처 기반 요약 품질을 높이는 설계 경험 확보
  * LLM·검색·미디어(음성/영상) 파트를 각각 구현하는 수준을 넘어, 장애 대응까지 고려한 운영형 End-to-End AI 서비스 아키텍처 설계 및 구현 역량 강화
* **🛠️ Tech:** Python, LangGraph, LangChain, OpenAI API(Chat/TTS), Tavily API, python-pptx, FFmpeg/ffprobe, LibreOffice, Poppler(pdftoppm), Gradio, Pillow, dotenv
* 🔗 [GitHub Repository](https://github.com/uh004/ai_lecture-generator)
</details>

<details>
<summary><b>ai_interview_agent</b> | 이력서 기반 AI 면접관 <i>(2025.10.30 ~ 2025.11.03)</i></summary>

<br>

<details>
<summary><b>ShowRoom</b> | 3D 공간 재구성 서비스 기획 <i>(2025.04.18 ~ 2025.06.13)</i></summary>

<br>

**"2D 이미지만으로 3D 공간을 재구성하는 혁신적인 서비스 아이디어를 기획하고 시스템 구조 설계"**

* **🎯 Situation & Task (배경 및 목표)**
  * 실내 3D 재구성 시 전문 장비 및 고비용 파이프라인 의존에 따른 일반 사용자 접근성 한계 문제 정의
  * 웹 환경(Airbnb 등)에서 선택한 최소 3장의 2D 이미지만으로 3D 재구성 및 보강 이미지 생성을 연계하는 End-to-End 시스템 아키텍처 설계 목표 수립
* **💡 Action (나의 역할 및 해결 과정)**
  * **기하 변환 모듈 구현:** MiDaS 기반 깊이 추정 및 3D Unproject/Project를 활용하여 입력 이미지를 Y축 기준 ±30° 회전 처리
  * **마스크 추출 및 노이즈 제거:** 기하 변환 후 발생한 빈 영역(Out-of-Bounds)을 Grid 기반 마스크로 추출하고, Morphology Open(5x5 커널) 연산 적용
  * **인페인팅 파이프라인 구축:** Stable Diffusion 2 Inpainting 파이프라인 구축 (Steps=50, Guidance=8.5, 출력 해상도 512x384 표준화)
  * **생성 제어 및 분기 처리:** 판별부 결과 키(0: Left, 1: Right, 2: None) 기반 생성 여부 및 방향 분기 로직 적용으로 예외 케이스 제어
  * **API 연동 및 데이터 확장:** 생성 이미지를 BytesIO(JPEG) 및 Base64로 직렬화하여 API 응답으로 전달하고, 메인 서버 연동을 통해 3D 재구성 입력을 3장에서 4장으로 동적 확장
* **📈 Result (성과 및 배운 점)**
  * 기하 변환 → 마스크 생성 → 인페인팅 → API 직렬화로 이어지는 4단계 이미지 생성 파이프라인 코드 제품화
  * 핵심 하이퍼파라미터(회전각, Steps, Guidance 등) 최적화 및 고정을 통해 실험 재현성 및 시스템 운영 일관성 확보
  * 판별 키 기반 분기 로직을 통해 '생성 불필요' 케이스를 포함한 안정적인 예외 처리 및 운영 플로우 완성
  * 2D 생성 결과를 3D 재구성 파이프라인으로 즉각 연계하는 구조를 구현하여, 생성 모델 품질 최적화 및 모델 서빙/API 연동 설계 역량 강화
* **🛠️ Tech:** Python, PyTorch, TensorFlow, Fast3R, OpenCV, Stable Diffusion Inpainting, Flask, Chrome Extension, BERTopic, Sentence-Transformers, PyMeshLab, Viser, Ngrok
* 🔗 [GitHub Repository](https://github.com/uh004/ShowRoom)
</details>

<details>
<summary><b>Eating_shot</b> | 당뇨병 환자용 식단 조절 및 케어 서비스 <i>(2024.07.01 ~ 2024.11.18)</i></summary>

<br>

## 💡 Planning & Research (기획 및 연구)

<details>
<summary><b>2025 GovTech</b> | 공공 기술 혁신 아이디어 기획 (아열대 작물 AI 플랫폼) <i>(2025.11) - 예선 진출 X</i></summary>

<br>

<details>
<summary>텍스트 마이닝 기법을 활용한 미술치료 현황 분석 | 실천공학교육논문지 게재 <i>(2024.12)</i></summary>

<br>

**"최근 10년간의 관련 논문 2,972편을 크롤링하고 텍스트 마이닝하여 미술치료 연구 동향을 객관적으로 분석 및 시각화했습니다."**

* **🎯 Background & Purpose (연구 배경 및 목적)**
  * 코로나19 팬데믹 이후 심리적 문제 해결을 위한 미술치료의 중요성이 대두됨에 따라, 전체적인 연구 동향 파악의 필요성 제기
  * 2014년부터 2023년까지 10년간 발행된 국내 미술치료 관련 논문을 수집하여 거시적인 연구 트렌드와 주요 키워드 간 연관성 도출 목표 수립
* **💡 Methodology (연구 및 분석 방법)**
  * **데이터 파이프라인 구축:** Python(Selenium, BeautifulSoup)을 활용하여 DBpia 및 RISS에서 2,972편의 논문 제목 및 초록(Abstract) 크롤링 및 중복 데이터 정제
  * **형태소 분석 및 전처리:** KiwiPiePy 라이브러리를 활용한 텍스트 토큰화 및 2글자 이상의 명사 추출 수행
  * **핵심어 추출 및 시각화:** scikit-learn을 활용한 TF(단어 빈도) 및 TF-IDF 분석으로 핵심 단어 추출 후 WordCloud 시각화
  * **의미망 분석:** Word2Vec(Skip-gram) 모델을 통해 단어 간 의미적 유사성을 벡터화하고, Gephi를 활용해 키워드 네트워크 동시 출현 빈도 및 연결 중심성(Yifan Hu Proportional) 시각화
* **📈 Result & Implication (연구 결과 및 의의)**
  * '아동', '청소년', '노인' 등 사회 취약 계층 및 '교육(특수학교 등)'과 미술치료의 강한 연관성 등 주요 연구 트렌드 객관적 도출
  * 방대한 비정형 텍스트 데이터를 계량적으로 분석하여 수작업으로 파악하기 힘든 거시적 동향을 증명하고, 한국실천공학교육학회(KCI 등재지) 정규 논문 게재 완료
* **🛠️ Tech:** Python, Selenium, BeautifulSoup, KiwiPiePy, scikit-learn (TF-IDF), Word2Vec, Gephi
* 🔗 [논문 링크 (Korea Science)](https://koreascience.or.kr/article/JAKO202406657604346.page)
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
