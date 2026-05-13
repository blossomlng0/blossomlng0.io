# 🚀 Park Hee-woo | AI Engineer

> **"데이터 기반 도시 문제 해결부터 복잡한 Multi-Agent 아키텍처 설계 및 구현까지, AI의 실전적 가치를 증명합니다."**


---

## 🛠 Technical Skills

### **Agentic AI & Engineering**
* **Frameworks:** `LangChain`, `LangGraph`, `LangSmith` (Monitoring & Tracing)
* **Agent Architecture:** `Planner-Executor-Critic`, `Multi-Agent Workflow`, `Supervisor-based Control`
* **Design Docs:** Workflow/State/Decision Policy/Prompt Specification

### **Machine Learning & Data Science**
* **Languages:** `Python` (Pandas, Numpy), `SQL` (Query & DB Design)
* **Modeling:** `XGBoost`, `LightGBM`, `Random Forest`, `Scikit-learn`, `TensorFlow`
* **Techniques:** `Feature Engineering`, `Hyperparameter Tuning (GridSearchCV)`, `StandardScaler`

---

## 📂 Featured Projects

### **1. LangSmith 기반 실시간 리뷰 분석 Multi-Agent 서비스**
* **개요**: 화장품 속성별(보습/향/가격/포장) 감성 분석 및 근거 추출을 위한 자율형 멀티 에이전트 시스템.
* **핵심 구현**:
    * **Workflow 설계**: `Planner-Analyzer-Evidence Extractor-Critic` 구조의 워크플로우 명세서 및 State 정의.
    * **검증 로직**: `Critic` 에이전트를 통한 분석 결과 자가 검토 및 `Supervisor` 기반 재시도(Retry) 제어.
    * **모니터링**: `LangSmith`를 활용하여 에이전트 실행 Trace 추적 및 실패 케이스 원인 분석.
    * **프롬프트 고도화**: 페르소나 및 제약사항이 반영된 `Prompt 명세서` 기반의 정밀 분석 수행.
* **Tech:** `LangGraph`, `LangSmith`, `GPT-4o-mini`, `SQLite`, `Streamlit`

### **2. 서울시 자치구별 멀티 도메인 데이터 기반 과밀 스코어 예측**
* **개요**: 교통, 경제, 주거, 공간 이종 데이터를 통합하여 도시 혼잡도를 측정하는 '과밀 스코어' 산출 모델.
* **Trouble Shooting**:
    * **문제**: 데이터 출처별 스케일 차이로 인한 모델 편향 발생.
    * **해결**: `StandardScaler` 기반 정규화 및 `Feature Engineering`을 통해 데이터 일관성 확보.
* **Tech:** `Python`, `XGBoost`, `LightGBM`, `Seaborn (Correlation Heatmap)`

### **3. 항공사 고객 만족도 예측 및 머신러닝 파이프라인 최적화**
* **개요**: 항공 서비스 지표를 활용한 고객 만족도 예측 및 서비스 개선 우선순위 도출.
* **Trouble Shooting**:
    * **문제**: 만족 고객 데이터 편중(클래스 불균형)으로 인한 불만족 고객 예측력 저하.
    * **해결**: `GridSearchCV` 최적화 및 전처리 과정을 함수화하여 실험 재현성 및 정답률 향상.
* **Tech:** `Scikit-learn`, `Deep Learning`, `Pipeline Automation`

---

## 📜 Design Documents & Works
* **[설계문서] Workflow & State 정의서**: 에이전트 간 데이터 흐름 및 상태 관리 로직 구조화.
* **[설계문서] Decision Policy & Prompt 명세서**: 의사결정 규칙 및 에이전트 가이드라인 최적화.
* **[구현코드] ML Pipeline (IPYNB)**: 하이퍼파라미터 튜닝 및 모델 비교 분석 과정 포함.

---

## 🎓 Education & Keywords
* **KT AIVLE School:** AI 트랙 이수
* **#설계능력**: 명세서 기반의 투명한 AI 시스템 구축
* **#최적화**: 데이터 전처리부터 모델 튜닝까지의 전 과정 최적화
* **#논리적사고**: 복잡한 비즈니스 로직을 에이전트 협업 구조로 변환

---

## 📫 Contact
* **Email**: hwoo.park@email.com
