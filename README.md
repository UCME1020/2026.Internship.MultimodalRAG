# 🚀 2026.Internship.MultimodalRAG

6개월 인턴십 기간 동안 진행하는 **멀티모달 RAG 프로젝트** 레포지토리입니다.  
초기 1–3주차는 강의/학습 기반으로 기술적 토대를 마련하고, 이후 본격적인 기능 개발과 고도화를 진행합니다.

---

## 🎯 프로젝트 목표

- 멀티모달 입력(텍스트/이미지/비디오 등)을 대상으로 **검색 증강 생성(RAG)** 파이프라인을 설계하고 구현
- AI 보조 개발 워크플로우(**Plan → Generate → Modify → Repeat**)를 적용해 개발 생산성과 품질을 함께 확보
- 평가/관측(정량+정성)을 통해 RAG 품질을 지속적으로 개선

---

## 📅 Project Roadmap (First Month)

프로젝트 초기 4주간의 온보딩 및 기술 학습 계획입니다.

| 기간 | 주제 | 주요 내용 |
| :--- | :--- | :--- |
| **Week 1-2** | **Modern Software Dev** | CS146S 실습 & AI 기반 개발 워크플로우 체득 |
| **Week 3** | **RAG Deep Dive** | LangChain, LangGraph, RAG 핵심 기술 선별 수강 |
| **Week 4** | **Development Kickoff** | 주제 선정, 아키텍처 설계 및 개발 진헹 |

---

### 📚 1–2주차: CS146S — The Modern Software Developer 실습

**Stanford CS146S** 강의를 통해 LLM이 가져온 소프트웨어 개발의 패러다임 전환을 이해하고 실습합니다.

* **Course Link:** [https://themodernsoftware.dev/](https://themodernsoftware.dev/)
* **Assignments:** [https://github.com/mihail911/modern-software-dev-assignments/tree/master](https://github.com/mihail911/modern-software-dev-assignments/tree/master)
  
### 💡 Course Highlights
> *"Software development has evolved from 0-1 code creation to an iterative workflow of plan, generate with AI, modify, and repeat."*

* **Paradigm Shift:** 기존 코딩 방식에서 'Plan → Generate(AI) → Modify → Repeat'의 반복적 워크플로우로 전환
* **10x Productivity:** 개발 전 과정(Lifecycle)에 AI 자동화를 도입하여 생산성 극대화
* **Core Skills:**
    * AI-assisted Development (AI 보조 개발)
    * Automated Testing (자동화된 테스트)
    * Intelligent Documentation (지능형 문서화)
    * Security Vulnerability Detection (보안 취약점 탐지)
      
### ⚡ Action Plan: 2-Week Intensive Sprint
**8주 분량의 커리큘럼을 2주 안에 완주하는 단기 집중 과정으로 진행합니다.**
* **Goal:** 1일 1과제 수행 (Daily Assignment Completion)
* **Schedule:** 2주 동안 8개 주차의 핵심 과제를 모두 소화하고, 매일 학습 내용을 기록합니다.
---
### 🎓 3주차: RAG 강의 수강
- 강의: [테디노트의 RAG 비법노트 : GPT·로컬 모델부터 LangGraph·Agent까지](https://fastcampus.co.kr/data_online_teddy)
- 커리큘럼(총 45h) 중 필요한 파트 선별 수강
<details>
<summary><b>📚 선별 강의 커리큘럼 </b></summary>

---

<details>
<summary><b>🧩 Part 1. LangChain 입문</b></summary>

### ▸ Ch 1. LangChain 시작하기
- 강의를 보는 방법 (00:11:40)
- RAG 기술이 주목받는 이유 (00:27:21)
- 위키독스 전자책 활용 방법 (00:02:24)
- 실습 코드 (GitHub) (00:02:22)

### ▸ Ch 2. 환경 설정
- 환경설치 (Windows) (00:16:51)
- 환경설치 (MacOS) (00:15:08)
- OpenAI API 키 설정 (00:09:17)
- LangSmith 키 설정 (00:07:29)
- VS Code User Settings(JSON) (00:04:16)

### ▸ Ch 3. LangChain 시작하기
- LangChain 개요 (00:06:29)
- Jupyter Notebook 사용법 (00:19:36)
- OpenAI 모델 이해 (00:11:05)
- Token 개념 및 비용 계산 (00:14:42)
- Context Window 이해 (00:09:58)

### ▸ Ch 4. LangChain 문법 맛보기
- ChatOpenAI 파라미터 / invoke / stream (00:14:37)
- LangSmith 추론 추적 (00:05:20)
- PromptTemplate (00:06:06)
- StrOutputParser 연결 (00:11:31)
- Chain 추론 과정 확인 (00:01:51)
- 비동기 호출 (00:05:15)
- 병렬 체인 (RunnableParallel) (00:08:00)

</details>

---

<details>
<summary><b>🧱 Part 2. 체인 파이프라인의 기본 요소</b></summary>

### ▸ Ch 1. 프롬프트
- PromptTemplate & partial variables (00:11:00)
- YAML 기반 프롬프트 로드 (00:07:22)

### ▸ Ch 2. 미니 프로젝트
- Streamlit 기반 ChatGPT 웹앱 (00:26:18)

### ▸ Ch 3. RAG 시작하기
- RAG 프로세스 (사전 단계) (00:26:13)
- RAG 프로세스 (실행 단계) (00:13:21)
- PDF 문서 QA RAG (00:25:00)
- 프롬프트 메이커 프로젝트 (00:16:00)
- PDF 기반 QA 챗봇 (00:11:58)
- LangSmith + 다양한 LLM 적용 (00:10:48)

### ▸ Ch 4. Output Parser
- Output Parser 개요 (00:09:56)
- PydanticOutputParser (00:23:53)
- with_structured_output() (00:03:28)
- LangSmith 흐름 확인 (00:05:18)

### ▸ Ch 5. Output Parser 활용 프로젝트
- 이메일 정보 구조화 (00:15:03)
- 구조화 결과를 다음 체인에 활용 (00:12:15)

### ▸ Ch 6. 모델 (Model)
- RAG에서의 LLM 역할 (00:06:57)
- 다양한 LLM 활용 (00:17:06)
- 응답 캐싱 (Cache) (00:08:41)
- 모델 저장 및 로드 (00:09:54)

### ▸ Ch 7. 모델 활용 프로젝트
- 기능 분리 (py 파일 구조화) (00:07:52)
- Ollama 기반 RAG (00:14:24)
- 멀티모달 이미지 인식 챗봇 (00:19:24)

</details>

---

<details>
<summary><b>🧠 Part 3. 체인의 기능 확장 (Memory)</b></summary>

### ▸ Ch 1. 메모리
- 메모리 개념 (00:02:02)
- ConversationBufferMemory (00:10:33)
- ConversationBufferWindowMemory (00:02:54)
- SQLite 기반 대화 저장 (00:11:10)
- 멀티턴 챗봇 프로젝트 (00:13:34)

</details>

---

<details>
<summary><b>📂 Part 4. 데이터 로드</b></summary>

### ▸ Ch 1. Document Loader
- 도큐먼트 로더 구조 (00:14:59)
- Document 구조 이해 (00:14:09)
- PDF Loader (00:16:05)

</details>

---

<details>
<summary><b>🔎 Part 5. Retrieval-Augmented Generation (RAG)</b></summary>

### ▸ Ch 1. 텍스트 분할
- 텍스트 분할 전략 (00:07:53)
- Character / Recursive / Token Splitter

### ▸ Ch 2. 임베딩
- Embeddings 개요 (00:09:16)
- OpenAIEmbeddings (00:10:09)
- CacheBackedEmbeddings (00:08:05)

### ▸ Ch 3. 벡터 저장소
- VectorStore 개요 (00:07:32)
- Chroma (00:25:47)

### ▸ Ch 4. Retriever
- Retriever 개요 (00:09:01)
- VectorStore 기반 Retriever (00:13:43)
- ContextualCompressionRetriever (00:15:26)
- Ensemble Retriever (00:11:56)

### ▸ Ch 5. Reranker
- Reranker 개요 (00:12:27)
- CrossEncoderReranker (00:06:20)

### ▸ Ch 6. RAG 파이프라인
- 뉴스 기사 QA (00:14:10)
- RAPTOR 논문 리뷰 (00:20:47)
- RAPTOR 코드 구현 (00:14:42)
- 오픈모델 기반 RAG (00:19:31)

</details>

---

<details>
<summary><b>⚙️ Part 6. 바로 사용할 수 있는 체인</b></summary>

- Stuff 요약 체인 (00:10:47)
- SQL 쿼리 생성 체인 (00:17:37)

</details>

---

<details>
<summary><b>🔗 Part 7. LCEL 고급 문법</b></summary>

- RunnablePassthrough (00:15:55)
- Runnable 구조 확인 (00:02:56)
- RunnableLambda (00:08:41)

</details>

---

<details>
<summary><b>📊 Part 8. RAG 평가 & 개선</b></summary>

### ▸ Ch 1. RAG 평가
- 평가 방식 및 지표 (00:05:14)
- RAGAS 소개 (00:08:05)
- 합성 데이터셋 생성 (00:10:28)
- RAGAS 실습 (00:22:07)

### ▸ Ch 2. LangSmith 기반 최적화
- Dataset Testing (00:09:43)
- LLM-as-Judge (00:16:55)
- Hallucination 평가 (00:05:32)
- RAGAS 프로젝트 (00:12:38)

</details>

---

<details>
<summary><b>🤖 Part 9. Agent</b></summary>

### ▸ Ch 1. Tools
- LangChain Tools 활용 (00:19:26)
- Custom Tool 제작 (00:07:52)

### ▸ Ch 2. Agent 핵심
- Tool Binding (00:16:49)
- Agent / AgentExecutor (00:15:48)
- Agent 스트리밍 (00:11:30)
- Agent 메모리 (00:05:38)
- 멀티 LLM Agent (00:10:14)

### ▸ Ch 3. Agent 활용
- Agentic RAG (00:14:46)
- 보고서 작성 자동화 Agent (00:14:58)
- CSV 데이터 분석 Agent (00:24:14)

</details>

---

<details>
<summary><b>🕸️ Part 10. LangGraph</b></summary>

### ▸ Ch 1. LangGraph 개요
- LangGraph 개요 (00:21:32)
- State / Node / Edge / Compile (00:25:21)

### ▸ Ch 2. 핵심 기능
- TypedDict / Annotated / Reducer (00:09:58)
- LangGraph 챗봇 (00:09:31)

### ▸ Ch 3. 구조 설계
- Graph Flow 설계 (00:23:33)
- Naive RAG (00:21:12)
- Hallucination 평가 모듈 (00:11:44)
- Agentic RAG (00:23:53)
- Adaptive RAG (00:32:13)

### ▸ Ch 4. 유스케이스
- 에이전트 대화 시뮬레이션 (00:15:55)
- Corrective RAG (CRAG) (00:17:57)
- Self-RAG (00:13:32)
- SQL Agent (Text2SQL) (00:26:17)
- GitHub QA 챗봇 (00:28:23)
- Perplexity 클론 (00:29:28)

</details>

---

<details>
<summary><b>🚀 Part 11. 서비스 배포</b></summary>

### ▸ Ch 1. Streamlit
- 배포 config 설정 (00:03:45)
- 배포 준비 (00:06:46)
- 배포 및 테스트 (00:07:42)
- 수정사항 반영 (00:05:00)

### ▸ Ch 2. LangServe
- LangServe 개요 (00:03:38)
- 모델 서빙 (00:21:18)
- 외부 연동 (00:06:26)

</details>

---

</details>



---
### 🛠️ 4주차: 개발 진행
초기 학습 기간(Week 1-3) 이후, 남은 인턴십 기간 동안 본격적인 팀 프로젝트를 진행합니다.

* **Team Sync:** 팀원 간 아이디어 회의 및 주제 확정
* **Architecture Design:** Multimodal RAG 시스템 아키텍처 설계
* **Development:** 데이터 파이프라인 구축
    * 모델 구현 및 튜닝
    * 서비스 개발 및 배포
---
## 📝 Daily Log Rule 

모든 팀원은 **매일 자정 전**까지 GitHub Issues 탭에 당일 학습 내역을 기록합니다.

### 📌 Writing Guide (작성 방법)
구체적인 작성 방법과 양식은 [인턴 생활간 공지사항 #2](https://github.com/sejong-rcv/2026.Internship.MultimodalRAG/issues/2)를 참고.
### 📌 Weekly Seminar
매주 월요일(3시), 한 주간 학습한 내용을 정리하고 공유하는 세미나를 진행합니다
