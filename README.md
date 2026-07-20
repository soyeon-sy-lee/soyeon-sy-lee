<div align="center">

# Audit & AX

[Financial Risk Screener](https://soyeon-sy-lee.github.io/financial-risk-screener/)
·
[Revenue Audit Mapper](https://soyeon-sy-lee.github.io/revenue-audit-risk-response-mapper/index.html)

</div>


## Featured Projects

### 01. Financial Ratio-Based Corporate Risk Screener

> 공개 재무비율 데이터를 이용해 추가 검토가 필요한 기업의 우선순위를
> 제시하고, 위험점수의 주요 상승·완화 요인을 설명하는 분석 도구입니다.
> 현재 버전은 재무비율 기반 검토 우선순위 흐름을 보여주는 프로토타입이며,
> DART 재무제표 연동 기능은 포함되어 있으나 실제 운영 환경에서의
> 안정적 데이터 수집·연동을 보장하지는 않습니다.

- 6,819개 관측치와 95개 재무 특성을 분석
- 회계적으로 해석 가능한 핵심 재무비율 14개를 사용한 Logistic Regression
- Dummy, 전체 변수 Logistic, 핵심 변수 Logistic, Random Forest 비교
- 임계값별 검토량·Recall·Precision 비교
- 과거 대만 기업 데이터라는 외부 일반화 한계 명시

**What this demonstrates**

재무비율 분석 · 불균형 데이터 평가 · 설명 가능한 모델
· 검토 우선순위 설계 · 모델 한계 문서화

[Live Demo](https://soyeon-sy-lee.github.io/financial-risk-screener/)
·
[Repository](https://github.com/soyeon-sy-lee/financial-risk-screener)
·
[Model Card](https://github.com/soyeon-sy-lee/financial-risk-screener/blob/main/docs/MODEL_CARD.md)

---

### 02. Revenue Audit Risk-Response Mapper

> 매출·매출채권 위험징후를 가능한 왜곡 양상, 경영진 주장,
> 추가 확인 질문 및 감사절차 후보로 연결하는 교육용 검토 도구입니다.

- 위험 → 왜곡 가설 → 주장 → 추가 질문 → 감사절차의 검토 흐름 설계
- 통제된 seed 지식베이스와 재현 가능한 합성 시나리오 생성기 구현
- 필수 컬럼, 외래키, 중복, split 누수 등을 점검하는 검증 스크립트 작성
- 주장 커버리지와 위험·절차 경고를 분리하여 표시
- 전문가 검토 전 데이터의 상태와 적용 한계를 명시
- 감사의견, 중요성, 표본크기 등 전문적 판단을 자동화하지 않도록 범위 제한

**What this demonstrates**

감사위험 평가 · 경영진 주장 · 감사절차 설계
· 설명 가능한 규칙 · 데이터 검증 · 책임 있는 AI 활용

[Live Demo](https://soyeon-sy-lee.github.io/revenue-audit-risk-response-mapper/index.html)
·
[Repository](https://github.com/soyeon-sy-lee/revenue-audit-risk-response-mapper)

---

### 03. Movie Recommender

> 공개 영화 데이터와 태그 기반 유사도를 이용한 정적 추천 웹앱입니다.

이 프로젝트에서 실험한 태그 기반 구조화, 추천 근거 제시,
로컬 피드백 아이디어를 이후 감사위험 대응 프로젝트의
검토 흐름 설계에 발전시켰습니다.

[Live Demo](https://soyeon-sy-lee.github.io/movie-recommender/)
·
[Repository](https://github.com/soyeon-sy-lee/movie-recommender)

