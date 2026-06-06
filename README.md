# ⚽ FIFA World Cup 2026 Winner Prediction

## 프로젝트 개요
Kaggle 데이터를 활용해 FIFA 월드컵 2026 우승국을 예측하는 머신러닝 모델입니다.
데이터 분석 입문자로서 전체 데이터 사이언스 파이프라인을 직접 구현했습니다.

## 주요 결과
- 🥇 **아르헨티나** — 우승 후보 1위
- 🥈 **잉글랜드** — 우승 후보 2위  
- 🥉 **스페인** — 우승 후보 3위
- 최종 모델 AUC: **0.7138**

## 진행 과정

### 1. EDA (탐색적 데이터 분석)
- 타겟 분포 시각화
- 상관관계 히트맵 및 TOP 10 피처 분석
- 박스플롯, 히스토그램, 산점도
- 다중공선성 탐지

### 2. 피처 엔지니어링
- 원본 22개 피처 → 파생 피처 9개 추가 생성

### 3. 모델 학습 및 비교
| 모델 | 설명 |
|------|------|
| Logistic Regression | 기본 분류 모델 |
| Random Forest | 앙상블 모델 |
| Gradient Boosting | 최종 채택 모델 |

### 4. 모델 개선
- 피처 선택 + GridSearchCV 하이퍼파라미터 튜닝
- AUC **0.6763 → 0.7138** 향상 (C=0.1)

## 사용 기술
- Python, JupyterLab
- pandas, scikit-learn

## 데이터
Kaggle FIFA World Cup 2026 Dataset
