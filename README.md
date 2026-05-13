# 🚀 Park Hui-woo | AI Engineer

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
* **결과**: Planner-Executor-Critic 구조의 멀티 에이전트 워크플로우를 설계하여 LLM의 환각(Hallucination) 현상을 억제하고 분석 정답률을 고도화함.
* **배운점**:
   * 순한 API 호출이 아닌 LangGraph 기반의 상태 관리(State) 및 의사결정 정책(Decision Policy) 설계 경험을 통해, 복잡한 비즈니스 로직을 AI 시스템으로 구조화하는 엔지니어링 역량을 확보했습니다.
   * 에이전트별 페르소나와 제약사항을 정의한 명세서를 관리하며, 모델의 출력 품질을 정교하게 제어하고 최적화하는 LLM 전문성을 확보했습니다.
* **Tech:** `LangGraph`, `LangSmith`, `GPT-4o-mini`, `SQLite`, `Streamlit`

### **2. 2026년 서울시 빅데이터 활용 경진대회**
* **개요**: 서울시 과밀 지역 복합 진단 분석. 교통, 경제, 주거, 공간 이종 데이터를 통합하여 도시 혼잡도를 측정하는 '과밀 스코어' 산출 모델.
* **Trouble Shooting**:
    * **문제**: 데이터 출처별 스케일 차이로 인한 모델 편향 발생.
    * **해결**: `StandardScaler` 기반 정규화 및 `Feature Engineering`을 통해 데이터 일관성 확보.
* **결과**: 교통, 경제, 주거, 공간 등 4개 영역의 이종 데이터를 통합하여 자치구별 실질 혼잡도를 정량화한 '과밀 스코어'를 산출하고 시각화함.
* **배운점**:
     * 서로 다른 형식의 공공 데이터를 병합하고 StandardScaler로 정규화하는 과정을 통해, 실무 데이터의 결측치 및 스케일 불일치 문제를 해결하는 데이터 전처리 파이프라인 구축 능력을 길렀습니다.
      * 단순한 모델링을 넘어, 비즈니스 목적에 맞는 독자적인 지표(Feature)를 설계하고 가중치를 부여하는 분석 기획 역량이 AI 모델의 실질적인 활용도를 결정짓는 핵심임을 깨달았습니다.
* **Tech:** `Python`, `XGBoost`, `LightGBM`, `Seaborn (Correlation Heatmap)`

### **3. 항공사 고객 만족도 예측 및 머신러닝 파이프라인 최적화**
* **개요**: 항공 서비스 지표를 활용한 고객 만족도 예측 및 서비스 개선 우선순위 도출.
* **Trouble Shooting**:
    * **문제**: 만족 고객 데이터 편중(클래스 불균형)으로 인한 불만족 고객 예측력 저하.
    * **해결**: `GridSearchCV` 최적화 및 전처리 과정을 함수화하여 실험 재현성 및 정답률 향상.
* **결과**: 5종 이상의 머신러닝 알고리즘 성능 비교 및 GridSearchCV 튜닝을 통해 불만족 고객 예측 성능(Recall)을 최적화함.
* **배운점**:
   * 클래스 불균형 문제를 해결하기 위한 샘플링 전략과 하이퍼파라미터 튜닝을 수행하며, 성능 지표 기반의 객관적인 모델 평가 및 고도화 프로세스를 체득했습니다.
   * 분석 과정을 함수화하여 지속 가능한 파이프라인을 구축하는 소프트웨어 엔지니어링 마인드의 중요성을 이해하고 실천했습니다.
* **Tech:** `Scikit-learn`, `Deep Learning`, `Pipeline Automation`

---

## 🎓 Education & Keywords
* **KT AIVLE School:** AI 트랙 이수
* **#설계능력**: 명세서 기반의 투명한 AI 시스템 구축
* **#최적화**: 데이터 전처리부터 모델 튜닝까지의 전 과정 최적화
* **#논리적사고**: 복잡한 비즈니스 로직을 에이전트 협업 구조로 변환

---

## 📫 Contact
* **Email**: gmldn6@gmail.com
