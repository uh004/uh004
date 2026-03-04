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

**"사용자의 이력서 데이터를 분석해 맞춤형 질문을 생성하고, 답변을 정량 평가하는 AI 면접관 서비스 개발"**

* **🎯 Situation & Task (배경 및 목표)**
  * 이력서 기반 모의면접 시 질문 생성, 면접 진행, 답변 평가, 피드백 작성이 분리되어 발생하는 비효율성 문제 정의
  * PDF/DOCX 1회 입력만으로 질문 생성부터 최종 피드백 리포트까지 자동 수행되는 End-to-End 면접 파이프라인 구축 목표 설정
* **💡 Action (나의 역할 및 해결 과정)**
  * **면접 오케스트레이션 설계:** LangGraph 기반 5노드(evaluate → decide → generate/change_strategy/summarize) 상태 그래프 구성 및 제어
  * **이력서 전처리 자동화:** PyMuPDF/python-docx 활용 텍스트 추출 및 LLM Structured Output 기반 핵심 요약(3~5문장)·키워드 생성
  * **질문 전략 생성 로직:** 3명의 면접관 페르소나(잠재력/조직적합/직무역량) 및 3개 축(경험/동기/논리) 기반 맞춤형 질문 풀 생성
  * **답변 평가 체계 구축:** 구체성·일관성·적합성·논리성 4개 지표에 대한 0/1 독립 채점 및 분야별 누적 평균 점수화 적용
  * **동적 면접 라우팅:** 분야별 평균 0.75 이상 시 다음 주제 전환, 미달 시 최대 2회 심화(꼬리) 질문 생성 로직 구현
  * **피드백 자동화:** 분야별 평균, 강점, 개선점, 10점 환산 점수 및 LLM 3문장 총평 리포트 자동 생성
  * **사용자 인터페이스:** Gradio 기반 파일 업로드 및 실시간 인터랙티브 채팅 UI 연동
* **📈 Result (성과 및 배운 점)**
  * 이력서 1회 입력으로 면접 전 과정을 자동화하고, 5개 노드 LangGraph 파이프라인으로 면접 운영 흐름 단일화
  * 3개 영역 × 3개 관점(총 9개 질문 풀) 매트릭스를 통해 개인화 질문 생성 체계 정형화
  * 동적 라우팅 규칙(0.75 기준점, 최대 2회 심화)을 적용하여 인터뷰 길이를 최소 3문항에서 최대 9문항으로 유연하게 제어
  * 4개 지표 이진 평가(0/1) 기반 답변 정량화 및 10점 만점 환산 스코어링 시스템 구축
  * 정량적 점수(수치)와 정성적 코멘트(해석)가 결합된 종합 피드백 보고 체계 완성
* **🛠️ Tech:** Python, LangGraph, LangChain, OpenAI API(Chat), Gradio, PyMuPDF, python-docx, python-dotenv
* 🔗 [GitHub Repository](https://github.com/uh004/ai_interviewer)
</details>

<details>
<summary><b>MINIMAX</b> | 질환별 신약 후보 분자 생성·예측 백엔드 구축 <i>(2025.09.05 ~ 2025.11.28)</i></summary>

<br>

**"사용자 입력 분자/질환 카테고리를 기반으로 신규 분자를 생성하고, 결합친화도 및 독성을 예측하는 AI 서비스 개발"**

* **🎯 Situation & Task (배경 및 목표)**
  * 비전문 사용자도 활용 가능한 신약 후보 탐색 서비스를 위해, 분자 생성부터 예측 및 저장까지 이어지는 API 단일 흐름 설계 필요성 정의
  * 분자 생성(Transformer) + 다중 예측(pKi/pKd/독성) + DB 적재를 통합한 End-to-End 백엔드 구축 목표 수립
* **💡 Action (나의 역할 및 해결 과정)**
  * **효능 예측 모델 연동:** 약물 효능 예측을 중심으로, 물성 5개(MW, logP, QED, HBD, HBA) 및 예측 5개(pKi 타깃/점수, pKd 타깃/점수, 독성) 등 총 10개 지표 산출 파이프라인 구성
  * **FastAPI 엔드포인트 설계:** 사용자 직접 입력 및 질환 카테고리 선택 기반으로 API 입력 흐름 분리 구현
  * **분자 생성 로직 제어:** 요청당 신규 분자 생성량 고정 제어 (사용자 입력: 5개, 질환 기반: 최대 10개)
  * **DB 연동 구조 설계:** Oracle DB 연동, 테이블 4개 + 시퀀스 2개 스키마를 통해 입력 및 생성 데이터 관리 체계 구축
* **📈 Result (성과 및 배운 점)**
  * 분자 생성 → 다중 예측 → DB 저장으로 이어지는 전체 운영 코드 경로 완성 및 API 중심 서빙 구조 구현
  * 정적 검증 통과 후, 런타임 검증 과정에서 핵심 의존성 패키지 5종(oracledb, deepchem, tensorflow, rdkit, chembl_webresource_client)의 충돌 리스크 정량 식별
  * 모델의 단순 성능 지표(정확도/추론 시간) 최적화에 앞서, '재현 가능한 실행 환경 고정(패키지 버전, 클라이언트 경로 등)'이 AI 서비스 안정성의 최우선 선결 조건임을 도출 및 학습
* **🛠️ Tech:** Python, FastAPI, PyTorch, TensorFlow, Transformers, RDKit, DeepChem, OracleDB, Pandas, Scikit-learn
* 🔗 [GitHub Repository](https://github.com/uh004/minimax)

</details>

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

**"당뇨병 환자의 식단·운동·혈당 데이터를 통합 관리하고, 음식 이미지 AI 분석까지 연결한 비동기 헬스케어 서비스 개발"**

* **🎯 Situation & Task (배경 및 목표)**
  * 분산된 당뇨 환자 일상 관리 기능(식단, 혈당, 복약 등)의 단일 서비스 통합 필요성 정의
  * 음식 이미지 업로드부터 AI 추론, 결과 저장, 사용자 피드백 및 추천 연계로 이어지는 End-to-End 백엔드 파이프라인 설계 목표 수립
* **💡 Action (나의 역할 및 해결 과정)**
  * **AI 데이터 정제 및 운동 추천 (담당 역할):** 추론 품질 개선을 위한 데이터 전처리 및 피처 엔지니어링 수행, 사용자 상태 기반 맞춤형 운동 추천 로직 구현
  * **비동기 AI 추론 파이프라인:** 이미지 저장 시 `InferenceTask(PENDING)` 생성 및 Celery 큐(`ai_queue`) 연동으로 고비용 추론 작업을 웹 요청과 분리하여 비동기 처리
  * **AI 서버 연동 및 데이터 매핑:** Django(`httpx`) ↔ FastAPI(`/predict`) 연동을 통해 추론 결과(JSON) 수집 및 식단(`Diet`) 데이터와 자동 매핑
  * **동적 영양 정보 관리:** 사용자 피드백(음식 추가/교체/삭제) API 제공 및 총 영양소(TOTAL) 자동 재계산 로직으로 데이터 일관성 유지
  * **맞춤형 식단 추천 연동:** 잔여 영양소(칼로리/탄단지) 및 식품군 섭취 편향 기반 추천 API(`/recommendation_score_foods`) 연동을 통한 개인화 식단 제공
  * **건강관리 백엔드 확장:** 혈당·혈압 기록, 운동 칼로리 자동 계산, 복약 알림 스케줄링(Celery+Signal) 및 SSE 기반 실시간 알림 채널 구축
  * **MSA 인프라 설계:** Docker Compose 기반 멀티서비스(Django, FastAPI, PostgreSQL, Redis, Celery, ELK 등) 컨테이너 오케스트레이션 통합 환경 구축
* **📈 Result (성과 및 배운 점)**
  * 업로드 → 추론 → 영양 분석 → 사용자 피드백 → 추천 및 리포트 생성까지 이어지는 헬스케어 파이프라인 코드 제품화
  * 비동기 아키텍처 도입으로 동기 요청 병목을 해소하고, 추론 실패 시 예외 처리(상태 전이/데이터 정리)를 포함한 안정적인 운영 플로우 정착
  * 복합 데이터 모델링, 비동기 큐 서빙, 프레임워크 간 API 통합 경험을 통한 실서비스형 백엔드/인프라 설계 역량 증명
* **🛠️ Tech:** Python, Django, DRF, FastAPI, Celery, Redis, PostgreSQL, SQLite, Docker Compose, YOLOv8(Ultralytics), OpenCV, scikit-learn, pandas, django-eventstream(SSE), Flower, Caddy, ELK
* 🔗 [GitHub Repository](https://github.com/uh004/Eating_shot)

</details>

## 💡 Planning & Research (기획 및 연구)

<details>
<summary><b>2025 GovTech</b> | 공공 기술 혁신 아이디어 기획 (아열대 작물 AI 플랫폼) <i>(2025.11) - 예선 진출 X</i></summary>

<br>

**"내 땅 아열대 작물 시뮬레이터: 기후변화 대응을 위한 맞춤형 재배·수익 예측 AI 플랫폼 기획"**

* **❓ Problem (문제 정의)**
  * 기후변화로 기존 농작물 재배의 불확실성이 증가하나, 기존 아열대 작물 매뉴얼은 파편화되고 일반화되어 있어 농가 적용에 한계
  * 농민이 작물 전환 시 가장 필요로 하는 '내 지역에서의 재배 가능성'과 '실질적인 경제성(수익)'을 사전에 파악하기 어려움
* **💡 Solution (해결 방안)**
  * 일반적인 사후 매뉴얼 제공을 넘어, '내 땅 + 내 조건'을 기준으로 실시간 의사결정을 지원하는 데이터 기반 AI 시뮬레이터 플랫폼 제안
* **⚙️ Service Flow & Tech (서비스 흐름 및 구현 전략)**
  * **환경 적합성 예측:** 기상청 데이터와 작물별 생육 조건 데이터를 융합하고, 환경 유사도 매칭 알고리즘(KNN 등)을 적용해 지역별 재배 적합성(%) 도출
  * **경제성 자동 계산기:** 농촌진흥청/통계청 소득 데이터 및 도매시장 시세 학습 데이터를 기반으로 초기 투자비, 연간 순이익, 손익분기점 자동 산출
  * **사용자 경험(UX) 최적화:** '지역 선택 → 보유 면적/투자금 입력 → 적합성 예측 → 경제성 비교'의 4단계 직관적인 MVP 프로세스 설계
* **📈 Expected Impact (기대 효과)**
  * 농가의 작물 전환 실패 리스크를 최소화하고 안정적인 소득 확보 및 수익 다각화 지원
  * 기후변화 대응 및 식량안보 강화라는 공공의 과제를 데이터 기반의 GovTech 비즈니스 모델로 풀어내는 서비스 기획력 증명
</details>

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
