# 🐙 GitHub 저장소 생성 가이드

**목표:** 금융 데이터분석가 포트폴리오 저장소 만들기

---

## 1️⃣ 저장소 생성 정보

### 📌 Owner (소유자)
```
simpson000  (당신의 GitHub 닉네임)
```

### 📌 Repository name (저장소 이름)
```
financial-data-analyst-portfolio
```

**왜 이 이름?**
- ✅ 짧고 명확함
- ✅ "금융 데이터분석가"가 바로 눈에 들어옴
- ✅ 포트폴리오 목적이 명확함
- ✅ 이직 면접관이 GitHub 검색할 때 찾기 쉬움

**대안 이름들:**
- `financial-analyst-projects` (좀 더 간단)
- `loan-data-analytics` (저축은행 특화)
- `data-analyst-finance` (역순)

---

## 2️⃣ Description (설명)

### 📝 짧은 설명 (한 줄)
```
저축은행 경영기획 경험 기반 | 금융 데이터분석가 포트폴리오 (VBA, SQL, Python, Power BI)
```

**복사해서 바로 붙여넣으세요:**
```
저축은행 경영기획 경험 기반 | 금융 데이터분석가 포트폴리오 (VBA, SQL, Python, Power BI)
```

**글자 수:** 약 45글자

---

### 📝 상세한 설명 (선택사항 - README에서 나중에 추가)

저장소 생성 후 README.md에 다음 내용을 추가하세요:

```markdown
# 📊 금융 데이터분석가 포트폴리오

저축은행 경영기획 경험 기반으로 구축한 데이터분석 포트폴리오입니다.

## 📌 About Me
- **경력:** 저축은행 경영기획팀 (6개월)
- **목표:** 금융권 데이터분석가 전환
- **기술 스택:** SQL, Python, VBA, Power BI, 통계분석

## 🚀 Skills
- **데이터베이스:** SQL (SELECT, JOIN, GROUP BY, CTE, 윈도우 함수)
- **자동화:** Excel VBA (루프, 함수, 객체)
- **데이터 분석:** Python (Pandas, NumPy, Scikit-learn)
- **시각화:** Power BI, Matplotlib, Seaborn
- **통계:** 가설검정, 회귀분석, 상관관계

## 📂 Projects

### Phase 1: 기초 다지기
- VBA, SQL, Python 기초 학습
- 첫 자동화 프로젝트 완성

### Phase 2: 현업 자동화 프로젝트
- 여신한도 관리 대시보드
- 월보 자동 생성 시스템
- 마감 모니터링 자동 알림
- 연체 현황 분석 대시보드

### Phase 3: 데이터 분석 심화
- 통계학 기초
- Power BI 고급
- 머신러닝 기초

## 📚 Blog
기술 블로그에서 학습 과정과 프로젝트 후기를 공유합니다.
[블로그 링크 - 나중에 추가]

## 📞 Contact
- Email: [이메일 - 선택]
- LinkedIn: [링크 - 선택]

---

*2025년 12월 시작 | 2027년 6월 목표 이직*
```

---

## 3️⃣ 저장소 설정 옵션

### 📋 Public vs Private
```
✅ Public 선택 (포트폴리오 공개)
```
**이유:** 이직 면접관이 GitHub을 볼 수 있어야 함

### 📋 README 초기화
```
✅ Add a README file 체크
```
**이유:** 저장소 설명을 처음부터 추가할 수 있음

### 📋 .gitignore
```
✅ Python 선택 (권장)
```
**이유:** 
- `__pycache__/` 파일 자동 제외
- `.pyc` 파일 자동 제외
- 불필요한 파일 업로드 방지

### 📋 License
```
✅ MIT License 또는 Apache 2.0 선택
```
**이유:** 
- 포트폴리오 공개용으로 적합
- 다른 사람이 코드를 참고할 수 있도록 허용

### 📋 Private (개인정보 보호)
```
⚠️ 민감한 데이터는 제외할 것
```
**주의사항:**
- 실제 고객 정보 ❌
- 회사 시스템 접근 정보 ❌
- 개인정보 ❌
- 샘플 데이터만 사용 ✅

---

## 4️⃣ 첫 번째 커밋 - README.md 작성

저장소 생성 직후 로컬에 클론한 후:

```bash
# 1. 저장소 클론
git clone https://github.com/simpson000/financial-data-analyst-portfolio.git
cd financial-data-analyst-portfolio

# 2. README.md 열기 (처음에는 비어있거나 자동 생성됨)

# 3. 아래 내용으로 작성
```

### 📝 README.md 초안

```markdown
# 📊 금융 데이터분석가 포트폴리오

저축은행 경영기획 경험 기반으로 데이터분석 포트폴리오를 구축하고 있습니다.

## 👨‍💼 About
- **현재 직책:** 저축은행 경영기획팀
- **경험:** 6개월 (금융 도메인 지식)
- **목표:** 금융권 데이터분석가로 커리어 전환
- **예상 이직:** 2027년 6월

## 🛠️ Tech Stack
| 분야 | 기술 |
|------|------|
| Database | SQL (DML, DDL, 윈도우함수) |
| Automation | Excel VBA |
| Programming | Python 3.x |
| Data Analysis | Pandas, NumPy, Scikit-learn |
| Visualization | Power BI, Matplotlib, Seaborn |
| Statistics | 가설검정, 회귀분석, 상관관계 |

## 📂 Folder Structure

```
financial-data-analyst-portfolio/
│
├── README.md (이 파일)
│
├── Phase1_Basics/
│   ├── 01_first_automation/
│   │   ├── project_description.md
│   │   ├── queries.sql
│   │   ├── automation.vba
│   │   ├── script.py
│   │   └── README.md
│   │
│   └── learning_notes/
│       ├── SQL_기초.md
│       ├── VBA_기초.md
│       └── Python_기초.md
│
├── Phase2_Projects/
│   ├── 01_loan_limit_dashboard/
│   ├── 02_monthly_report_generator/
│   ├── 03_daily_monitoring_alert/
│   └── 04_delinquency_analysis_dashboard/
│
├── Phase3_Advanced/
│   ├── statistics_analysis/
│   ├── power_bi_dashboards/
│   └── machine_learning_models/
│
└── .gitignore

```

## 📚 Learning Path

### Phase 1: 기초 다지기 (0~3개월)
- [x] GitHub 저장소 개설
- [ ] SQL 기초 학습
- [ ] VBA 기초 학습
- [ ] Python 기초 복습
- [ ] 첫 자동화 프로젝트 완성

### Phase 2: 현업 자동화 프로젝트 (3~9개월)
- [ ] 4개 자동화 프로젝트 완성
- [ ] Power BI 기초 습득
- [ ] 기술 블로그 10개 포스팅

### Phase 3: 데이터 분석 심화 (9~15개월)
- [ ] 통계학 기초
- [ ] Power BI 심화
- [ ] 머신러닝 기초
- [ ] 고급 분석 프로젝트

### Phase 4: 이직 준비 (15개월+)
- [ ] 포트폴리오 최종 완성
- [ ] 기술 면접 준비
- [ ] 이직 지원

## 🎯 Key Projects

### 📊 Project 1: 여신한도 관리 대시보드
**기간:** 1개월 | **난이도:** ⭐⭐⭐

저축은행의 여신 현황을 실시간으로 모니터링하는 자동화 시스템

**기술:** SQL + VBA + Pivot Table
**효과:** 월 2시간 → 0시간

[자세히 보기 - 나중에 링크 추가]

### 📈 Project 2: 월보 자동 생성 시스템
**기간:** 2개월 | **난이도:** ⭐⭐⭐⭐

매월 반복되는 월보 생성 업무 완전 자동화

**기술:** SQL + Python (Pandas) + Power BI
**효과:** 월 4시간 → 30분

[자세히 보기 - 나중에 링크 추가]

### 🔔 Project 3: 마감 모니터링 자동 알림
**기간:** 1.5개월 | **난이도:** ⭐⭐⭐⭐⭐

매일 마감 현황을 자동으로 추출 및 알림

**기술:** SQL + Python + Slack API
**효과:** 일 15분 → 0분 (완전 자동화)

[자세히 보기 - 나중에 링크 추가]

### 📉 Project 4: 연체 현황 분석 대시보드
**기간:** 2개월 | **난이도:** ⭐⭐⭐⭐

연체 고객 패턴 분석 및 예측 모델

**기술:** SQL + Python (분석) + Power BI
**효과:** 월 2시간 정리 시간 절감 + 인사이트 제공

[자세히 보기 - 나전에 링크 추가]

## 📖 Blog & Articles

기술 블로그에서 각 프로젝트의 개발 과정, 배운 점, 문제 해결 방법을 상세히 기록합니다.

[블로그 링크 - 나중에 추가]

### 최근 포스팅
- [VBA 기초: 변수와 함수 이해하기] - 나중에
- [SQL JOIN 완벽 정복] - 나중에
- [Python Pandas로 엑셀 자동화하기] - 나중에

## 🎓 Learning Resources

### 학습 자료 (무료)
- **SQL:** 프로그래머스 SQL 입문
- **VBA:** YouTube "엑셀 VBA 완전정복"
- **Python:** 코드잇, Kaggle Learn
- **Power BI:** Microsoft 공식 문서

### 도움이 된 사이트
- Stack Overflow (문제 해결)
- GitHub (코드 참고)
- Medium (기술 블로그)

## 📞 Contact & Links

- **Email:** [이메일 - 선택]
- **LinkedIn:** [프로필 - 선택]
- **Blog:** [블로그 - 나중에 추가]

## 📅 Timeline

```
2025년 12월    ▶ Phase 1 시작 (기초 학습)
2026년 3월     ▶ Phase 2 시작 (프로젝트)
2026년 9월     ▶ Phase 3 시작 (심화)
2027년 3월     ▶ Phase 4 시작 (이직 준비)
2027년 6월     ▶ 목표 이직 완료 🎉
```

## 📊 Stats

![Commits](https://img.shields.io/badge/Commits-0+-blue)
![Projects](https://img.shields.io/badge/Projects-0+-green)
![Blog Posts](https://img.shields.io/badge/Blog%20Posts-0+-yellow)

---

## 📝 Notes

이 저장소는 **금융 데이터분석가 커리어 전환**의 모든 과정을 기록합니다.

- 매주 커밋하며 꾸준함을 보여줍니다
- 실무 기반 프로젝트로 포트폴리오를 구축합니다
- 기술 블로그로 학습 과정을 공유합니다

**목표:** 포트폴리오 완성 후 금융권 데이터분석가로 이직

---

**마지막 업데이트:** 2025년 12월 7일
```

---

## 5️⃣ 저장소 생성 후 로컬 세팅

```bash
# Step 1: 저장소 클론
git clone https://github.com/simpson000/financial-data-analyst-portfolio.git

# Step 2: 폴더 이동
cd financial-data-analyst-portfolio

# Step 3: 폴더 구조 생성
mkdir -p Phase1_Basics/01_first_automation/data_sample
mkdir -p Phase1_Basics/learning_notes
mkdir -p Phase2_Projects
mkdir -p Phase3_Advanced

# Step 4: .gitignore 확인
# (저장소 생성 시 Python 선택했으면 자동으로 생성됨)

# Step 5: README.md 수정 및 커밋
git add .
git commit -m "Initial commit: 금융 데이터분석가 포트폴리오 저장소 개설"
git push origin main
```

---

## 6️⃣ 추가 설정 (나중에)

### 🔧 Repository Settings (GitHub 웹에서)
1. **Settings** → **General**
   - Description 추가
   - Website 추가 (블로그 링크)

2. **Settings** → **Collaborators** (선택)
   - 멘토 추가 (피드백 받고 싶으면)

3. **Settings** → **Topics** (선택)
   - `data-analysis`, `python`, `sql`, `vba`, `finance` 등 추가

---

## 📋 체크리스트

저장소 생성 전에 다음을 확인하세요:

- [ ] GitHub 계정 가입 완료
- [ ] 닉네임: `simpson000`
- [ ] 저장소 이름: `financial-data-analyst-portfolio`
- [ ] Public 선택
- [ ] README 초기화 체크
- [ ] Python .gitignore 선택
- [ ] License 선택 (MIT 또는 Apache 2.0)

---

## ✅ 저장소 생성 완료 후

다음을 해야 할 일:

1. **로컬 클론** (위 코드 참조)
2. **폴더 구조 생성** (위 코드 참조)
3. **README.md 작성** (위 샘플 참조)
4. **첫 커밋**
   ```bash
   git add .
   git commit -m "Initial commit: 포트폴리오 저장소 개설"
   git push origin main
   ```

5. **다음 채팅에서 공유**
   - 저장소 링크: `https://github.com/simpson000/financial-data-analyst-portfolio`

---

**준비 완료! 이제 저장소를 만들면 됩니다! 🚀**

---

**작성일:** 2025년 12월 7일
