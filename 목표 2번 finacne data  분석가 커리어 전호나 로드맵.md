# 🎯 목표 2번: Finance Data 분석가 커리어 전환 로드맵

**시작일:** 2025년 12월 7일  
**상태:** 🟢 진행 중  
**목표 직책:** Data Planning & Analytics Specialist (Finance Data 팀)  
**필수 스킬:** SQL, Python, SAS/R, 통계 분석, 모델링  
**목표 기간:** 18개월 (2025년 12월 ~ 2027년 6월)

---

## 🎯 목표 2번 정의

### 최종 목표

```
Finance Data 팀 - Data Planning & Analytics Specialist

"통계 모델링과 데이터 아키텍처를 통해
금융 리스크를 관리하고 비즈니스 인사이트를 제공하는 분석가

- 신용평가 모델 개발 & 운영
- 데이터 기반 리스크 분석
- 데이터 아키텍처 설계
- 통계 분석 & 예측 모델링"

기간: 18개월 (2025년 12월 ~ 2027년 6월)
목표 회사: 금융권 (은행, 저축은행, 핀테크)
```

---

## 📊 18개월 전체 계획

| 단계 | 기간 | 초점 | 핵심 산출물 | 프로젝트 |
|------|------|------|----------|--------|
| **Phase 1** | 0~3개월 | 기초 다지기 | SQL, Python, 통계 기초 | - |
| **Phase 2** | 3~9개월 | 모델링 | 4개 분석/모델링 프로젝트 | 4개 |
| **Phase 3** | 9~15개월 | 고급 기술 | 2개 고급 프로젝트 | 2개 |
| **Phase 4** | 15~18개월 | 포트폴리오 완성 | 포트폴리오 + 이직 준비 | - |
| **합계** | 18개월 | 전문 분석가 | **7개 프로젝트** | **7개** |

---

## Phase 1: 기초 다지기 (0~3개월)

**기간:** 2025년 12월 ~ 2026년 3월  
**목표:** SQL, Python, 통계 기초 완성

### 월 1 (12월) - SQL & Python 기초

**Week 1-4:**

```
주 1-2: SQL 심화
- INNER/LEFT/FULL JOIN
- 서브쿼리, CTE (WITH)
- 윈도우 함수 (ROW_NUMBER, RANK, LAG, LEAD)
- 집계함수 (COUNT, SUM, AVG, GROUP_CONCAT)
- 성능 최적화 기초

산출물: advanced_sql_queries.sql
- 20+ 복잡한 쿼리 작성
- 각 쿼리 해석 및 최적화

주 3-4: Python 기초 복습
- Pandas (DataFrame, Series 조작)
- NumPy (수치 계산)
- Matplotlib (기본 시각화)
- 데이터 정제 파이프라인 구축

산출물: data_analysis_basics.py
- Pandas로 데이터 읽기/정제/저장
- 기본 통계 계산
- 간단한 시각화
```

**GitHub 커밋: 3개**

---

### 월 2 (1월) - 통계 기초 & SAS/R 선택

**학습 주제:**

```
통계 기초 (1주-2주):
- 기술 통계 (평균, 분산, 표준편차, 분포)
- 확률과 확률분포 (정규분포, 포아송 등)
- 가설 검정 (t-test, chi-square test)
- 신뢰도와 신뢰구간

SAS 또는 R 선택 (3주-4주):
- SAS: PROC SQL, PROC MEANS, PROC REG
  또는
- R: dplyr, ggplot2, base R 통계

산출물:
- Statistics_Fundamentals.md
- SAS_or_R_Tutorial.md (선택한 것)
```

**GitHub 커밋: 2개**

---

### 월 3 (2월) - 첫 번째 분석 프로젝트

**프로젝트 1: 고객 포트폴리오 분석**

```
목표: "통계 방법론으로 고객 포트폴리오 분석"

기술 스택:
- SQL: 고객 데이터 추출
- Python: 통계 분석
- SAS/R: 결과 검증

산출물:
01_Customer_Portfolio_Analysis/
├── data_extraction.sql
├── statistical_analysis.py
├── portfolio_analysis_report.md ⭐
├── visualization.py
└── README.md

분석 내용:
1. 고객 세분화 (통계 기반)
2. 포트폴리오 특성 분석
3. 위험 요인 분석
4. 통계적 의미성 검증

기대 성과:
- 첫 번째 완성된 분석 프로젝트
- 통계 방법론 이해
- 기초 보고서 작성 능력

GitHub 커밋: 3개
```

**Phase 1 완료 시 상태:**
- ✅ SQL & Python 심화 숙련
- ✅ 통계 기초 탄탄
- ✅ SAS 또는 R 선택 & 기초 학습
- ✅ 6+ GitHub 커밋
- ✅ 분석 프로젝트 1개 완성

---

## Phase 2: 모델링 프로젝트 (3~9개월)

**기간:** 2026년 4월 ~ 9월  
**목표:** 4개 모델링 프로젝트 완성 + 데이터 파이프라인 구축

### 프로젝트 2: 신용 위험 모델 (4~5월)

```
목표: "로지스틱 회귀로 신용 위험 예측 모델 개발"

기술 스택:
- SQL: 위험 데이터 특성 추출
- Python: 모델 개발 (Scikit-learn)
- SAS/R: 통계 검증

산출물:
02_Credit_Risk_Model/
├── feature_engineering.sql
├── credit_risk_model.py
├── model_evaluation_report.md ⭐
├── model_validation.md
├── model_deployment_guide.md
└── README.md

모델 개발:
1. 데이터 준비 (특성 엔지니어링)
2. 로지스틱 회귀 모델 구축
3. 모델 평가 (AUC, KS, Gini)
4. 비즈니스 해석
5. 배포 가이드

기대 성과:
- 신용 위험 예측 모델 완성
- 모델 정확도: 80% 이상
- 실무 적용 가능한 수준

기대 비즈니스 효과:
- 신용 심사 자동화 가능
- 리스크 관리 개선
- 대출 손실 20~30% 감소

GitHub 커밋: 5개
```

---

### 프로젝트 3: 고객 세분화 & 클러스터링 (5~7월)

```
목표: "머신러닝 클러스터링으로 고객 위험도 세분화"

기술 스택:
- SQL: 고객 특성 데이터 추출
- Python: K-means, 계층적 클러스터링
- SAS/R: 세그먼트 특성 분석

산출물:
03_Customer_Segmentation/
├── customer_features.sql
├── clustering_analysis.py
├── segmentation_report.md ⭐
├── segment_profiles.md
├── risk_dashboard.pbix
└── README.md

세분화 과정:
1. 특성 선택 & 정규화
2. 최적 클러스터 수 결정
3. K-means 클러스터링
4. 각 세그먼트 특성 분석
5. 비즈니스 해석

세그먼트:
- Segment 1: 저위험 고객 (특성 분석)
- Segment 2: 중간위험 고객 (특성 분석)
- Segment 3: 고위험 고객 (특성 분석)

기대 비즈니스 효과:
- 세그먼트별 맞춤 전략 수립
- 위험 관리 효율화
- 마케팅 타겟팅 개선

GitHub 커밋: 4개
```

---

### 프로젝트 4: 데이터 파이프라인 & ETL (7~8월)

```
목표: "자동화된 데이터 파이프라인 구축"

기술 스택:
- SQL: 복잡한 데이터 변환
- Python: 자동화 스크립트
- Power BI: 자동 갱신 대시보드

산출물:
04_Data_Infrastructure/
├── etl_pipeline.py
├── scheduled_jobs.sql
├── data_quality_checks.py
├── monitoring_dashboard.pbix
├── infrastructure_guide.md ⭐
└── README.md

파이프라인 구성:
1. 데이터 추출 (여러 소스)
2. 데이터 변환 (정제, 계산)
3. 데이터 로드 (데이터마트)
4. 품질 검증
5. 에러 처리 & 알림

자동화:
- Task Scheduler로 자동 실행
- 일 1회 또는 주 1회 스케줄
- 실패 시 자동 알림

기대 비즈니스 효과:
- 수작업 시간 20시간/주 절감
- 데이터 최신성 보장
- 분석 효율 50% 증가

GitHub 커밋: 4개
```

---

### 프로젝트 5: 고급 통계 분석 (8~9월)

```
목표: "회귀분석과 가설검정으로 비즈니스 인사이트 도출"

기술 스택:
- SQL: 데이터 추출
- Python: 회귀분석 (Statsmodels)
- SAS/R: 통계 검증

산출물:
05_Advanced_Analytics/
├── regression_analysis.py
├── hypothesis_testing.md
├── business_insights.md ⭐
├── statistical_validation.md
└── README.md

분석 내용:
1. 선형회귀 분석 (연체율 예측)
2. 로지스틱 회귀 (기본/고급)
3. 가설 검정 (통계적 의미성)
4. 상관관계 분석
5. 비즈니스 의사결정에 활용

기대 인사이트:
- "특정 고객 특성이 연체와 유의한 관계"
- "마케팅 채널이 고객 만족도에 미치는 영향"
- "포트폴리오 구성의 최적화 방안"

GitHub 커밋: 4개
```

**Phase 2 완료 시 상태:**
- ✅ 4개 모델링 프로젝트 완성
- ✅ 신용 위험 모델 개발 능력
- ✅ 데이터 파이프라인 구축 능력
- ✅ 18 GitHub 커밋
- ✅ 포트폴리오 완성도 70%

---

## Phase 3: 고급 기술 프로젝트 (9~15개월)

**기간:** 2026년 10월 ~ 2027년 1월  
**목표:** 2개 고급 프로젝트 완성

### 프로젝트 6: 데이터 웨어하우스 설계 (10~11월) ⭐⭐⭐

```
목표: "엔터프라이즈 데이터 웨어하우스 아키텍처 설계"

기술 스택:
- SQL: 차원 모델링, 스타 스키마
- Python: ETL 설계
- Data Modeling: 종합 설계

산출물:
06_Data_Warehouse_Design/
├── dimensional_modeling.md ⭐
├── star_schema_design.sql
├── etl_architecture.md
├── data_dictionary.md
├── performance_optimization.sql
└── README.md

데이터 웨어하우스 설계:
1. 비즈니스 요구사항 분석
2. 차원 모델링 (사실 테이블, 차원 테이블)
3. 천천히 변하는 차원 (SCD) 설계
4. 데이터 구조 최적화
5. 성능 튜닝 전략

기대 성과:
- 엔터프라이즈 수준 DW 설계
- 스케일 가능한 아키텍처
- 분석 속도 70% 향상

GitHub 커밋: 6개
```

---

### 프로젝트 7: 시계열 예측 & 포캐스팅 (11~1월) ⭐⭐⭐

```
목표: "시계열 분석으로 비즈니스 메트릭 예측"

기술 스택:
- SQL: 시계열 데이터 추출
- Python: ARIMA, Prophet, LSTM
- SAS/R: 시계열 검증

산출물:
07_Time_Series_Forecasting/
├── time_series_analysis.py
├── arima_models.md ⭐
├── prophet_models.md
├── lstm_models.py
├── forecast_accuracy.md
├── business_forecast_dashboard.pbix
└── README.md

예측 모델:
1. ARIMA 모델 (정통 시계열)
2. Prophet (페이스북 오픈소스)
3. LSTM 신경망 (딥러닝)
4. 앙상블 모델 (결합)
5. 신뢰도 구간 추정

예측 대상:
- 대출 금액 예측
- 연체율 추이 예측
- 고객 이탈 예측
- 수익 포캐스팅

기대 비즈니스 효과:
- 정확한 자금 계획
- 리스크 사전 예방
- 경영진 의사결정 개선
- 전략 수립 강화

GitHub 커밋: 6개
```

**Phase 3 완료 시 상태:**
- ✅ 2개 고급 프로젝트 완성
- ✅ 데이터 웨어하우스 설계 능력
- ✅ 시계열 예측 모델 개발 능력
- ✅ 12 GitHub 커밋
- ✅ 포트폴리오 완성도 90%

---

## Phase 4: 포트폴리오 완성 & 이직 준비 (15~18개월)

**기간:** 2027년 2월 ~ 6월  
**목표:** 포트폴리오 완성 & 이직 성공

### 포트폴리오 최종 점검 (2월~3월)

```
GitHub 정리:
✅ 7개 프로젝트 완전한 문서화
✅ 각 프로젝트 상세 README
✅ 모델 개발 과정 상세 기록
✅ 코드 품질 높은 수준 (주석, 구조화)

기술 블로그:
✅ 15개 이상 포스팅 완료
✅ SQL 최적화 (3개)
✅ Python 데이터 분석 (3개)
✅ 통계 분석 방법론 (3개)
✅ 머신러닝 모델링 (3개)
✅ 시계열 분석 (3개)

포트폴리오 사이트:
✅ Notion 또는 개인 웹사이트
✅ 자기소개 & 경력 요약
✅ 주요 프로젝트 소개
✅ 기술 스킬 (SQL, Python, SAS/R, 통계)
✅ GitHub & 블로그 링크
```

### 면접 준비 (4월~5월)

```
기술 면접 대비:

Q1: "가장 복잡했던 모델은?"
A: 신용 위험 모델
   - 특성 엔지니어링 어려움
   - 클래스 불균형 처리 (20% vs 80%)
   - 모델 해석 가능성 확보
   - 최종 AUC: 0.82

Q2: "SQL 성능 최적화 사례는?"
A: ETL 파이프라인 최적화
   - 조인 순서 조정으로 50% 빠름
   - 인덱싱 전략 적용
   - 서브쿼리 → CTE 변경

Q3: "통계 검증 방법은?"
A: 모델 평가 프로세스
   - Hold-out 방식 검증 (70:30)
   - K-fold 교차 검증
   - Gini, KS, AUC 지표 활용

Q4: "데이터 품질 문제를 어떻게 처리했나?"
A: 결측치 & 이상치 처리
   - 결측치: 평균값, 중앙값, 모델 기반 보정
   - 이상치: 통계적 방법 (IQR, Z-score)
   - 검증: 전/후 분포 비교

이직 준비물:
☑️ 포트폴리오 사이트
☑️ 이력서 (모델링 경험 강조)
☑️ 자소서 (3개 프로젝트 심화)
☑️ SQL 최적화 예제 코드
☑️ 모델 개발 프로세스 설명
☑️ 실제 모델 코드 (Jupyter)
```

### 이직 지원 (6월)

```
목표 포지션:
- Data Analyst (금융권)
- Credit Risk Analyst
- Data Scientist (Financial Services)
- Analytics Engineer

목표 회사:
- 더 큰 규모 저축은행
- 지역 은행
- 핀테크 회사
- 신용평가기관
- 금융 컨설팅사

```

---

## 📊 기술 스킬 진화 경로

### SQL 진화
```
Month 1: JOIN, 서브쿼리, CTE 심화
Month 3: 윈도우 함수, 고급 집계
Month 6: 복잡한 데이터 변환 쿼리
Month 12: 성능 최적화, 인덱싱 전략
Month 18: 프로덕션 수준 데이터 파이프라인
```

### Python 진화
```
Month 1: Pandas, NumPy 심화
Month 3: Scikit-learn 머신러닝 기초
Month 6: 고급 모델링, 특성 엔지니어링
Month 12: 시계열, 신경망 기초
Month 18: 프로덕션 코드 품질 (테스트, 배포)
```

### 통계 진화
```
Month 1: 기술 통계, 확률
Month 3: 가설 검정, 회귀분석
Month 6: 머신러닝 이론
Month 12: 고급 모델 검증
Month 18: 통계적 리더십 (논문 수준)
```

### SAS/R 진화
```
Month 2: 기본 문법, 함수
Month 4: 통계 프로시저
Month 8: 고급 모델링
Month 12: 프로덕션 코드
Month 18: 효율적인 스크립트 작성
```

---

## 🎓 최종 체크리스트

### Phase 1 완료 (3개월)
- [ ] SQL 심화 학습 완료
- [ ] Python & 통계 기초 완성
- [ ] SAS 또는 R 선택 & 기초 학습
- [ ] 첫 번째 분석 프로젝트 완료
- [ ] 6+ GitHub 커밋

### Phase 2 완료 (9개월)
- [ ] 4개 모델링 프로젝트 완성
- [ ] 신용 위험 모델 개발
- [ ] 데이터 파이프라인 구축
- [ ] 18+ GitHub 커밋
- [ ] 기술 블로그 10개 이상 포스팅

### Phase 3 완료 (15개월)
- [ ] 데이터 웨어하우스 설계 완성
- [ ] 시계열 예측 모델 개발
- [ ] 12+ GitHub 커밋
- [ ] 기술 블로그 총 15개 이상
- [ ] 포트폴리오 90% 완성

### Phase 4 완료 (18개월)
- [ ] 7개 프로젝트 완전 문서화
- [ ] 포트폴리오 사이트 완성
- [ ] 기술 면접 준비 완료
- [ ] 이직 지원 시작
- [ ] 최종 목표 달성! 🎉

---

## 💡 성공의 핵심

```
1. "정확성" > 속도
   - 모델 정확도가 모든 것
   - 철저한 검증 과정

2. "포트폴리오" 프로젝트가 핵심
   - 실제 작동하는 모델
   - 설명 가능한 결과

3. "데이터 이해"가 기초
   - 데이터 특성 파악
   - 결측치, 이상치 처리

4. "통계 이론" 필수
   - 모델이 왜 작동하는가?
   - 통계적 근거는?

5. "문서화" 중요
   - 코드 주석
   - 모델 설명 보고서
   - 결과 해석
```

---

**문서 상태:** 활성 로드맵  
**목표 직책:** Data Planning & Analytics Specialist  
**기간:** 18개월  
**난이도:** 상 ⭐⭐⭐⭐  
**마지막 업데이트:** 2025년 12월 7일

---

**화이팅!** 🎯📊✨
