# Data-Analyst-skryu

데이터분석가 류승권의 개인 프로젝트 저장소입니다.

## 📁 Structure

```
.
├── data/
│   ├── raw/          # 원본 데이터 (git 제외)
│   ├── processed/    # 가공 데이터 (git 제외)
│   └── external/     # 외부 데이터 (git 제외)
├── notebooks/        # 탐색/분석 노트북 (예: 01_eda.ipynb)
├── src/              # 재사용 Python 코드
├── sql/              # 분석 쿼리
└── reports/
    └── figures/      # 결과 차트/이미지
```

## 🚀 Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # 필요 시 값 채우기
```

## 🌿 Branch Strategy

| Branch | 용도 |
|---|---|
| `main` | 완성된 결과물 (직접 push 지양) |
| `analysis-skryu` | 개인 작업 브랜치 |

작업 흐름: `analysis-skryu`에서 작업 → `main`으로 PR 후 병합

### Commit Convention

- `feat:` 새 분석/기능
- `fix:` 수정
- `docs:` 문서
- `refactor:` 코드 정리
- `chore:` 설정/기타

## 📊 Projects

| 프로젝트 | 설명 | 링크 |
|---|---|---|
| _TBD_ | | |
