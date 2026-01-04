# STATRACK Python 부트캠프 커리큘럼

[원본](https://classroom.dante-labs.com/classes/487c5921-76ef-4e7f-9c4d-db36cc0b3187)

## 핵심 목표

Week 1

Python 기초
Python 프로그래밍 완전 정복

Week 2

데이터 처리
pandas + Plotly + 데이터 수집

Week 3

데이터 분석
시계열 + 통계 + 텍스트 분석

Week 4

머신러닝
전통적 ML (scikit-learn)

Week 5

딥러닝
PyTorch로 현대 딥러닝

------------------

📅 Week 1: Python Fundamentals (32h)
목표: Python 기초 문법부터 OOP, 예외 처리, 표준 라이브러리까지 완전 정복

## Day 1: 데이터 구조와 제어 흐름 (8h)

### Day 1-1: 데이터 구조 심화 (Collection) (4h)

학습 목표:

Python의 핵심 데이터 구조 완전 정복

리스트, 튜플, 딕셔너리, 집합의 특성과 활용

Comprehension 문법으로 코드 간결화

실무 패턴 (VLOOKUP, 데이터 집계 등)

주요 내용:

Part 1: 기초

Numbers, Strings 완전 정복

List, Tuple 마스터하기

Dictionary의 모든 것

Set과 집합 연산

Part 2: 심화

List/Dict/Set Comprehension

Tuple Unpacking 고급 활용

실무 패턴: VLOOKUP, 집계, 변환

실습 데이터셋:

학생 성적 데이터

매출 거래 데이터

### Day 1-2: 제어 흐름의 진화 (Advanced Control) (4h)

학습 목표:

조건문과 반복문 완전 정복

Python 특화 제어 구조 마스터

효율적인 루프 작성법

주요 내용:

Part 1: 기초

if/elif/else 조건문

for/while 반복문

break, continue, pass

Part 2: 심화

match-case (구조적 패턴 매칭)

enumerate, zip, reversed

for-else, while-else 패턴

중첩 루프 최적화

실습:

FizzBuzz 변형 문제

데이터 그룹핑 및 집계

### Day 2: 함수와 모듈 (8h)

### Day 2-0: 함수와 스코프 (Function & Scope) (3h)

학습 목표:

함수 정의와 활용 완전 정복

고급 함수 기법 (*args, **kwargs, lambda)

스코프와 클로저 이해

주요 내용:

Part 1: 기초

함수 정의 및 호출

매개변수와 반환값

기본값, 키워드 인자

Part 2: 심화

args, **kwargs 완전 정복

lambda 함수

데코레이터 기초

LEGB 스코프 규칙

### Day 2-1: 모듈과 패키지 (Module & Package) (2h)

학습 목표:

모듈 import 시스템 이해

패키지 구조 설계

가상환경 관리

주요 내용:

Part 1: 기초

import 기본 문법

from import 활용

name == “main”

Part 2: 심화

패키지 구조 (init.py)

상대/절대 경로 import

pip와 requirements.txt

가상환경 (venv, conda)

### Day 2-2: 파일 다루기와 직렬화 (File I/O & Serialization) (3h)

학습 목표:

파일 읽기/쓰기 완전 정복

CSV, JSON, Pickle 다루기

안전한 파일 처리 (with 문)

주요 내용:

Part 1: 기초

파일 열기/닫기

텍스트 파일 읽기/쓰기

CSV 파일 다루기

with 문으로 안전하게

Part 2: 심화

JSON 직렬화/역직렬화

Pickle로 객체 저장

대용량 파일 처리 (청킹)

파일 경로 관리 (pathlib)

실습:

로그 파일 분석

CSV 데이터 변환

JSON API 응답 처리

### Day 3: OOP와 고급 주제 (8h)

### Day 3-0: 객체지향 프로그래밍 (OOP) (3h)

학습 목표:

클래스와 객체 개념 이해

상속과 다형성 활용

실무 OOP 패턴

주요 내용:

Part 1: 기초

클래스 정의 및 인스턴스 생성

init, str, repr

인스턴스 변수 vs 클래스 변수

메서드 정의

Part 2: 심화

상속 (Inheritance)

다중 상속과 MRO

프로퍼티와 데코레이터

dataclass 활용

추상 클래스 (ABC)

실습:

BankAccount 클래스

데이터 파이프라인 클래스 설계

### Day 3-1: 예외 처리와 디버깅 (Exceptions) (2h)

학습 목표:

Syntax Errors vs Exceptions 구분

try-except 완전 정복

사용자 정의 예외

로깅으로 디버깅

주요 내용:

Part 1: 기초

try-except 기본 구조

여러 예외 타입 처리

try-except-else-finally

with 문으로 리소스 관리

Part 2: 심화

예외 계층 구조

사용자 정의 예외

예외 체이닝 (raise from)

logging 모듈

재시도 로직

실습:

API 호출 에러 처리

파일 처리 안전화

로그 기반 디버깅

### Day 3-2: 분석가를 위한 표준 라이브러리 II (2h)

학습 목표:

실무 필수 표준 라이브러리

파일/경로 조작

날짜/시간 처리

정규표현식

주요 내용:

Part 1: 기초

os, pathlib (파일/디렉토리)

glob (파일 패턴 매칭)

shutil (파일 복사/이동)

datetime (날짜/시간)

Part 2: 심화

re (정규표현식)

collections (고급 자료구조)

itertools (반복자 도구)

functools (함수 도구)

실습:

파일 일괄 처리

로그 파일 정규표현식 파싱

날짜 기반 데이터 집계

### Day 3-3: 종합 실습 - 로그 분석 자동화 봇 (1h)

프로젝트 목표:

Week 1에서 배운 모든 내용 통합

실제 업무 시나리오 해결

프로젝트 내용:

여러 서버 로그 파일 수집

에러 패턴 추출 (정규표현식)

통계 집계 및 리포트 생성

예외 처리 및 로깅

OOP로 구조화

📊 Week 2: Data Processing & Collection (32h)
목표: pandas로 데이터 처리 + Plotly로 시각화 + 웹 데이터 수집
중요: matplotlib/seaborn 사용 없이 Plotly Express & Graph Objects만 사용

### Day 4: NumPy 핵심 + pandas 기초 + Plotly 입문 (8h)

### Day 4-0: NumPy 핵심만 (1h)

학습 목표:

NumPy 배열 개념 이해

pandas가 빠른 이유 이해

기본 배열 연산

주요 내용:

배열 생성 및 인덱싱

브로드캐스팅 개념

벡터화 연산의 이점

왜 NumPy를 알아야 하나: pandas 내부 이해용

실습:

배열 연산 vs 반복문 속도 비교

### Day 4-1: pandas 기초 (5h)

학습 목표:

Series, DataFrame 완전 정복

파일 읽기/쓰기 마스터

기본 데이터 조작

주요 내용:

Part 1: 기초

Series, DataFrame 개념

CSV, Excel 파일 읽기/쓰기

기본 탐색 (head, tail, info, describe)

인덱싱과 슬라이싱 (loc, iloc)

필터링과 조건 선택

Part 2: 심화

컬럼 추가/삭제/이름 변경

정렬 (sort_values, sort_index)

중복 제거 (drop_duplicates)

apply, map, applymap 함수형 처리

실습 데이터셋: Titanic

### Day 4-2: Plotly Express 기초 (2h)

학습 목표:

Plotly Express로 빠른 시각화

인터랙티브 차트의 힘

pandas 데이터를 바로 그래프로

주요 내용:

Part 1: 기초

px.scatter() - 산점도

px.line() - 선 그래프

px.bar() - 막대 그래프

px.histogram() - 히스토그램

px.box() - 박스플롯

Part 2: 인터랙티브 기능

hover_data, color, size 매핑

facet_row, facet_col (서브플롯)

animation_frame (애니메이션)

테마와 템플릿

실습:

Titanic 데이터 기본 시각화

생존율 분석 그래프

인터랙티브 대시보드 맛보기

중요: matplotlib은 사용하지 않음!

### Day 5: 데이터 전처리 + Plotly 검증 (8h)

### Day 5-0: 결측치 처리 (2.5h)

학습 목표:

결측치 패턴 이해

적절한 처리 방법 선택

시각화로 검증

주요 내용:

Part 1: 기초

isna(), notna() 확인

fillna() - 값 채우기

dropna() - 제거하기

interpolate() - 보간

Part 2: 심화 + 시각화

결측치 패턴 분석

px.imshow() - 히트맵으로 결측치 시각화

다양한 채우기 전략 (평균, 중앙값, ffill, bfill)

결측치 처리 before/after 비교 시각화

실습:

더러운 데이터셋 결측치 처리

Plotly로 패턴 확인

### Day 5-1: 이상치 및 데이터 정제 (2.5h)

학습 목표:

이상치 탐지 방법

데이터 타입 변환

정규화/스케일링

주요 내용:

Part 1: 이상치

IQR 방법으로 이상치 탐지

Z-score 방법

px.box() - 박스플롯으로 이상치 시각화

px.scatter() - 산점도로 이상치 확인

Part 2: 데이터 정제

astype() - 타입 변환

pd.to_datetime() - 날짜 변환

replace() - 값 대체

정규화 (Min-Max, Z-score)

Part 3: 시각화로 검증

px.histogram() - 분포 확인

전처리 전후 비교 대시보드

실습:

Titanic 데이터 완전 정제

before/after 시각화 비교

### Day 5-2: 실습 프로젝트 (3h)

프로젝트: 더러운 전자상거래 데이터 정제

작업 내용:

결측치 처리 전략 수립

이상치 탐지 및 처리

데이터 타입 정제

Plotly 대시보드로 전체 과정 시각화

정제된 데이터 저장

결과물:

정제된 CSV 파일

HTML 대시보드 (Plotly)

### Day 6: pandas 고급 + Plotly Graph Objects + SQL (8h)

### Day 6-0: pandas 고급 조작 (3h)

학습 목표:

groupby로 집계 마스터

pivot_table로 요약

merge로 데이터 통합

주요 내용:

Part 1: groupby

기본 집계 (sum, mean, count)

다중 컬럼 groupby

agg() 함수로 복합 집계

transform() vs apply()

px.bar(), px.line()으로 집계 결과 시각화

Part 2: pivot & merge

pivot_table() 완전 정복

merge() - 데이터 조인

concat() - 데이터 결합

px.imshow() - 피벗 테이블 히트맵

실습:

매출 데이터 일/월별 집계

다중 소스 데이터 통합

Plotly로 트렌드 분석

### Day 6-1: Plotly Graph Objects (2h)

학습 목표:

Graph Objects로 세밀한 커스터마이징

고급 시각화 기법

대시보드 레이아웃

주요 내용:

Part 1: Graph Objects 기초

go.Figure() 생성

add_trace() 추가

update_layout() 레이아웃

update_xaxes(), update_yaxes() 축 설정

Part 2: 고급 시각화

Subplots (make_subplots)

이중 Y축

Annotations (주석)

Shapes (도형 그리기)

색상 팔레트 커스터마이징

Part 3: 인터랙티브 대시보드

버튼과 슬라이더

Dropdown 메뉴

애니메이션 컨트롤

실습:

복합 차트 만들기

인터랙티브 대시보드 구축

### Day 6-2: SQL 연동 간단히 (1h)

학습 목표:

pandas에서 SQL 데이터 가져오기

기본 쿼리 실행

주요 내용:

pd.read_sql() 데모

SQLAlchemy 기초 연결

to_sql()로 데이터 저장

pandas-gbq (BigQuery) 소개

“필요할 때 찾아보세요” 수준

실습:

SQLite 데이터베이스 읽기

쿼리 결과 시각화

### Day 6-3: 통합 실습 (2h)

프로젝트: 다중 소스 데이터 분석

작업 내용:

CSV + DB에서 데이터 로드

merge로 통합

groupby로 집계

Plotly Graph Objects로 대시보드

HTML 리포트 생성

### Day 7: 웹 스크레이핑 (정적/동적) (8h)

### Day 7-0: 정적 스크레이핑 (4h)

학습 목표:

HTML 구조 이해

BeautifulSoup으로 파싱

실전 크롤링

주요 내용:

Part 1: 기초

HTML/CSS 선택자 기초

requests로 웹페이지 가져오기

BeautifulSoup 파싱

find(), find_all() 사용법

Part 2: 실전 크롤링

CSS Selector 활용

테이블 데이터 추출

페이지네이션 처리

에러 처리 및 재시도

pandas DataFrame으로 저장

Plotly로 수집 데이터 시각화

실습:

뉴스 사이트 헤드라인 수집

쇼핑몰 상품 정보 크롤링

수집 데이터 분석 및 시각화

### Day 7-1: 동적 스크레이핑 (4h)

학습 목표:

JavaScript 렌더링 페이지 처리

Selenium으로 브라우저 자동화

실전 동적 크롤링

주요 내용:

Part 1: Selenium 기초

WebDriver 설정

요소 찾기 (By.ID, By.CLASS_NAME, By.XPATH)

클릭, 입력 자동화

대기 전략 (implicit_wait, explicit_wait)

Part 2: 고급 기법

스크롤 처리

iframe 전환

팝업 처리

로그인 자동화

headless 모드

Part 3: 실전 프로젝트

SNS 데이터 수집

동적 테이블 크롤링

pandas로 정제 및 분석

Plotly 대시보드 생성

실습:

인스타그램 해시태그 수집 (데모)

동적 차트 데이터 추출

수집 → 분석 → 시각화 파이프라인

### Day 7-2: 종합 프로젝트

프로젝트: 실시간 뉴스 크롤러 + 분석 대시보드

작업 내용:

여러 뉴스 사이트에서 헤드라인 수집

pandas로 데이터 정제

키워드 빈도 분석

Plotly로 인터랙티브 대시보드

자동화 스크립트 작성

📈 Week 3: Data Analysis Methods (32h)
목표: 시계열 분석 + 통계 + A/B Testing + 텍스트 마이닝

### Day 8: 시계열 데이터 분석 (8h)

### Day 8-0: 시계열 기초 (3h)

학습 목표:

시계열 데이터 개념

datetime 처리 완전 정복

시계열 인덱싱

주요 내용:

Part 1: 기초

시계열 데이터란?

pd.to_datetime() 변환

DatetimeIndex 설정

시간대 (timezone) 처리

Part 2: 시계열 조작

날짜 범위 생성 (date_range)

시계열 인덱싱 및 슬라이싱

shift(), diff() 활용

px.line()으로 시계열 시각화

실습:

주식 데이터 날짜 처리

시계열 기본 시각화

### Day 8-1: 시계열 분석 기법 (3h)

학습 목표:

resample로 리샘플링

rolling로 이동 평균

추세와 계절성 분해

주요 내용:

Part 1: 리샘플링

resample() - 주기 변환

업샘플링 vs 다운샘플링

다양한 집계 함수

Part 2: 이동 통계

rolling() - 이동 평균

expanding() - 누적 통계

ewm() - 지수 가중 이동 평균

Part 3: 시계열 분해

추세 (Trend)

계절성 (Seasonality)

잔차 (Residual)

Plotly로 분해 결과 시각화

실습:

주식 데이터 이동 평균

계절성 분석

트렌드 예측

### Day 8-2: 시계열 시각화 + 프로젝트 (2h)

학습 목표:

Plotly로 고급 시계열 차트

인터랙티브 시계열 대시보드

주요 내용:

px.line() 고급 활용

Range Slider 추가

Multiple Y-axes

Candlestick 차트 (주가)

Time Series Annotations

프로젝트: 암호화폐 가격 분석

yfinance로 데이터 수집

이동 평균 계산

인터랙티브 차트 생성

추세 분석 리포트

### Day 9: 기초 통계 (8h)

### Day 9-0: 확률 분포 (2.5h)

학습 목표:

확률 분포 개념 이해

scipy.stats 활용

통계량 계산

주요 내용:

Part 1: 통계 기초 복습 (30분)

평균, 중앙값, 최빈값

분산, 표준편차

사분위수, IQR

Part 2: 확률 분포

정규분포 (norm)

이항분포 (binom)

포아송분포 (poisson)

t-분포, 카이제곱분포

Plotly로 분포 시각화

실습:

scipy.stats로 분포 다루기

실제 데이터 분포 확인

Q-Q plot으로 정규성 검정

### Day 9-1: 가설 검정 (3h)

학습 목표:

가설 검정 프로세스 이해

t-test, chi-square 실습

p-value 해석

주요 내용:

Part 1: 가설 검정 개념

귀무가설 vs 대립가설

유의수준 (α)

p-value 해석

Type I, Type II 오류

Part 2: 검정 방법

t-test (단일, 독립, 대응)

chi-square (카이제곱 검정)

ANOVA (분산분석)

비모수 검정 (Mann-Whitney, Wilcoxon)

Part 3: 상관관계

상관계수 (Pearson, Spearman)

상관관계 vs 인과관계

px.scatter()로 상관관계 시각화

실습:

키-몸무게 상관관계

A/B 그룹 평균 비교

설문조사 데이터 카이제곱 검정

### Day 9-2: 회귀분석 기초 (1.5h)

학습 목표:

선형 회귀 개념

statsmodels 활용

회귀 결과 해석

주요 내용:

Part 1: 단순 선형 회귀

최소제곱법

회귀계수 해석

R-squared

px.scatter() + trendline

Part 2: 다중 선형 회귀

statsmodels.formula.api

summary() 해석

잔차 분석

Plotly로 잔차 플롯

실습:

광고비 vs 매출 회귀

다중 변수 회귀 모델

예측 및 시각화

### Day 9-3: 통계 종합 실습 (1h)

프로젝트: 실제 데이터로 가설 검증

예시: “키가 큰 사람이 몸무게가 더 많이 나갈까?”

데이터 탐색 (EDA)

정규성 검정

상관분석

회귀모델 구축

결과 시각화 및 해석

### Day 10: A/B Testing (8h)

### Day 10-0: A/B 테스트 이론 (2h)

학습 목표:

실험 설계 원리

A/B 테스트 프로세스

통계적 유의성

주요 내용:

Part 1: 실험 설계

대조군 vs 실험군

무작위 배정

표본 크기 계산

실험 기간 설정

Part 2: 평가 지표

전환율 (Conversion Rate)

클릭률 (CTR)

평균 주문 금액 (AOV)

지표 선정 기준

실습:

표본 크기 계산 (power analysis)

실험 설계서 작성

### Day 10-1: A/B 테스트 분석 (3h)

학습 목표:

A/B 테스트 데이터 분석

통계적 검정 수행

결과 해석 및 의사결정

주요 내용:

Part 1: 데이터 분석

A/B 그룹 기초 통계량

전환율 계산

Plotly로 그룹 비교 시각화

Part 2: 통계적 검정

비율 검정 (z-test)

t-test (평균 비교)

chi-square (범주형)

p-value 해석

Part 3: 심화 주제

다변량 테스트 (A/B/C)

시퀀셜 테스팅

Bayesian A/B Testing 소개

실습:

웹사이트 버튼 색상 A/B 테스트

이메일 제목 A/B 테스트

결과 시각화 및 리포트

### Day 10-2: A/B 테스트 실전 프로젝트 (3h)

프로젝트: 전자상거래 웹사이트 개선

시나리오:

목표: 결제 페이지 전환율 향상

실험: 새로운 UI 디자인 테스트

데이터: 2주간 A/B 테스트 결과

작업 내용:

데이터 탐색 및 전처리

A/B 그룹 비교 (기초 통계)

통계적 검정 수행

Plotly 대시보드 생성

전환율 비교 차트

일별 트렌드

세그먼트별 분석 (모바일 vs PC)

의사결정 제안

실험 리포트 작성

결과물:

HTML 대시보드

의사결정 리포트

후속 실험 제안

### Day 11: 텍스트 마이닝 (8h)

### Day 11-0: 텍스트 전처리 (3h)

학습 목표:

텍스트 정제 기법

토큰화 및 정규화

한글 텍스트 처리

주요 내용:

Part 1: 기초 전처리

소문자 변환, 공백 제거

특수문자 제거 (정규표현식)

불용어 (stopwords) 제거

어간 추출 (stemming), 표제어 추출 (lemmatization)

Part 2: 한글 처리

KoNLPy 설치 및 설정

형태소 분석 (Okt, Mecab)

품사 태깅

명사 추출

Part 3: 토큰화

단어 토큰화

문장 토큰화

n-gram 생성

실습:

뉴스 기사 전처리

한글 형태소 분석

토큰화 파이프라인 구축

### Day 11-1: 텍스트 분석 기법 (3h)

학습 목표:

단어 빈도 분석

TF-IDF

워드 클라우드

주요 내용:

Part 1: 빈도 분석

Counter로 단어 빈도

Plotly 막대 그래프로 Top-N 단어

워드 클라우드 (WordCloud 라이브러리)

Part 2: TF-IDF

TF-IDF 개념

scikit-learn TfidfVectorizer

중요 단어 추출

Part 3: 문서 유사도

코사인 유사도

문서 클러스터링 소개

실습:

뉴스 기사 키워드 추출

TF-IDF로 중요 문서 찾기

워드 클라우드 생성

### Day 11-2: 감성 분석 (1h)

학습 목표:

감성 분석 개념

사전 기반 감성 분석

머신러닝 기반 감성 분석 소개

주요 내용:

Part 1: 사전 기반

VADER (영어)

KNU 감성 사전 (한글)

긍정/부정/중립 분류

Part 2: 시각화

px.pie() - 감성 분포

px.bar() - 감성 점수 비교

실습:

영화 리뷰 감성 분석

트위터 감성 분석

### Day 11-3: 텍스트 마이닝 종합 프로젝트 (1h)

프로젝트: 뉴스 헤드라인 분석

작업 내용:

크롤링한 뉴스 데이터 (### Day 7에서 수집)

텍스트 전처리

키워드 빈도 분석

TF-IDF로 중요 키워드

감성 분석

Plotly 대시보드

워드 클라우드

Top 키워드 차트

감성 분포

시간대별 트렌드

결과물:

텍스트 분석 리포트

인터랙티브 대시보드

🤖 Week 4: Machine Learning with scikit-learn (32h)
목표: 전통적인 머신러닝 완전 정복 (scikit-learn, XGBoost, LightGBM)

### Day 12: 머신러닝 기초 + scikit-learn (8h)

### Day 12-0: 머신러닝 개론 (2h)

학습 목표:

머신러닝 개념 이해

지도학습 vs 비지도학습

ML 워크플로우

주요 내용:

Part 1: ML 기초 개념

머신러닝이란?

지도학습 (Supervised Learning)

비지도학습 (Unsupervised Learning)

강화학습 (Reinforcement Learning) 소개

Part 2: ML 프로세스

문제 정의

데이터 수집 및 전처리

모델 선택 및 훈련

평가 및 튜닝

배포

Part 3: scikit-learn 소개

설치 및 기본 구조

estimator 인터페이스

fit(), predict(), transform()

### Day 12-1: 데이터 전처리 for ML (3h)

학습 목표:

ML을 위한 데이터 준비

특성 엔지니어링

훈련/테스트 분할

주요 내용:

Part 1: 데이터 분할

train_test_split()

계층적 샘플링 (stratify)

교차 검증 (Cross-Validation)

Part 2: 특성 스케일링

StandardScaler (표준화)

MinMaxScaler (정규화)

RobustScaler (이상치 강건)

Part 3: 범주형 변수 처리

LabelEncoder

OneHotEncoder

get_dummies()

Part 4: 특성 엔지니어링

다항 특성 (PolynomialFeatures)

로그 변환

상호작용 특성

실습:

Titanic 데이터 ML용 전처리

파이프라인 구축

### Day 12-2: 모델 평가 (2h)

학습 목표:

모델 성능 지표 이해

과적합 vs 과소적합

모델 비교 및 선택

주요 내용:

Part 1: 분류 평가 지표

Accuracy (정확도)

Precision (정밀도)

Recall (재현율)

F1-score

Confusion Matrix

Plotly로 Confusion Matrix 시각화

Part 2: 회귀 평가 지표

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE

R² (R-squared)

Part 3: 과적합 방지

교차 검증

Learning Curve

Validation Curve

Plotly로 학습 곡선 시각화

실습:

다양한 지표 계산

모델 성능 비교 대시보드

### Day 12-3: 첫 ML 모델 (1h)

실습: Titanic 생존 예측

작업 내용:

데이터 로드 및 EDA

특성 엔지니어링

로지스틱 회귀 모델 훈련

성능 평가

Plotly로 결과 시각화

### Day 13: 지도학습 - 회귀와 분류 (8h)

### Day 13-0: 회귀 모델 (4h)

학습 목표:

다양한 회귀 알고리즘 이해

모델 비교 및 선택

하이퍼파라미터 튜닝

주요 내용:

Part 1: 선형 모델

Linear Regression

Ridge Regression (L2 정규화)

Lasso Regression (L1 정규화)

ElasticNet

Part 2: 비선형 모델

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting (XGBoost, LightGBM)

Part 3: 하이퍼파라미터 튜닝

GridSearchCV

RandomizedSearchCV

Plotly로 파라미터 영향 시각화

실습:

주택 가격 예측 (Boston Housing)

여러 모델 비교

최적 모델 선택

### Day 13-1: 분류 모델 (4h)

학습 목표:

다양한 분류 알고리즘

멀티클래스 분류

앙상블 기법

주요 내용:

Part 1: 기본 분류기

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Support Vector Machine (SVM)

Part 2: 트리 기반 모델

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Part 3: 앙상블 기법

Voting Classifier

Bagging

Boosting

Stacking

Part 4: 불균형 데이터 처리

class_weight 조정

SMOTE (오버샘플링)

언더샘플링

실습:

신용카드 사기 탐지

여러 모델 비교

Plotly로 ROC 곡선, PR 곡선

### Day 14: 비지도학습 (8h)

### Day 14-0: 군집화 (Clustering) (4h)

학습 목표:

군집화 개념 이해

다양한 군집화 알고리즘

최적 군집 수 찾기

주요 내용:

Part 1: K-Means

K-Means 알고리즘

Elbow Method

Silhouette Score

px.scatter()로 군집 시각화

Part 2: 계층적 군집화

Hierarchical Clustering

Dendrogram

Linkage 방법

Part 3: 밀도 기반 군집화

DBSCAN

노이즈 탐지

임의 모양 군집

Part 4: 가우시안 혼합 모델

GMM (Gaussian Mixture Model)

확률적 군집화

실습:

고객 세분화 (Customer Segmentation)

여러 알고리즘 비교

인터랙티브 군집 대시보드

### Day 14-1: 차원 축소 (4h)

학습 목표:

차원의 저주 이해

PCA와 t-SNE

특성 선택

주요 내용:

Part 1: PCA (주성분 분석)

PCA 개념

설명된 분산

차원 축소 및 시각화

px.scatter()로 2D/3D 시각화

Part 2: t-SNE

t-SNE 개념

고차원 데이터 시각화

perplexity 파라미터

Part 3: 특성 선택

SelectKBest

RFE (Recursive Feature Elimination)

Feature Importance

실습:

MNIST 손글씨 차원 축소

Iris 데이터 시각화

Plotly로 고차원 데이터 탐색

### Day 15: ML 종합 프로젝트 (8h)

### Day 15-0: 앙상블 & AutoML (3h)

학습 목표:

앙상블 고급 기법

AutoML 도구 활용

모델 해석

주요 내용:

Part 1: 고급 앙상블

Voting (Hard/Soft)

Stacking 심화

Blending

Plotly로 모델 비교

Part 2: AutoML 소개

TPOT (Tree-based Pipeline Optimization)

Auto-sklearn 소개

하이퍼파라미터 최적화 (Optuna)

Part 3: 모델 해석

Feature Importance

SHAP Values

Partial Dependence Plot

Plotly로 해석 시각화

실습:

여러 모델 스태킹

AutoML로 최적 모델 찾기

SHAP로 모델 설명

### Day 15-1: 종합 프로젝트 (5h)

최종 프로젝트: End-to-End ML 파이프라인

선택 가능한 프로젝트:

전자상거래 고객 이탈 예측

고객 데이터 EDA

특성 엔지니어링

여러 분류 모델 비교

최적 모델 선택 및 튜닝

비즈니스 인사이트 도출

Plotly 대시보드

부동산 가격 예측

부동산 데이터 수집 (크롤링)

데이터 전처리

회귀 모델 구축

가격 예측 및 시각화

인터랙티브 예측 도구

SNS 감성 분석 + 분류

텍스트 데이터 수집

텍스트 전처리

TF-IDF 벡터화

감성 분류 모델

실시간 감성 분석 대시보드

작업 프로세스:

문제 정의 및 데이터 수집

EDA 및 시각화

데이터 전처리

특성 엔지니어링

모델 훈련 및 평가

하이퍼파라미터 튜닝

최종 모델 선택

Plotly 대시보드 구축

리포트 작성 및 발표

결과물:

Jupyter Notebook (전체 프로세스)

HTML 대시보드

프로젝트 리포트 (PDF)

발표 자료

🧠 Week 5: Deep Learning with PyTorch (32h)
목표: PyTorch로 현대 딥러닝 아키텍처 완전 정복

### Day 16: PyTorch 기초 + MLP/DNN (8h)

### Day 16-0: PyTorch 기초 (3h)

학습 목표:

PyTorch 텐서 연산

Autograd 이해

기본 신경망 구축

주요 내용:

Part 1: PyTorch 기초

Tensor 생성 및 연산

GPU 가속 (CUDA)

Autograd (자동 미분)

torch.nn 모듈

Part 2: 신경망 기초 이론

퍼셉트론 (Perceptron)

활성화 함수 (ReLU, Sigmoid, Tanh)

손실 함수 (MSE, Cross-Entropy)

옵티마이저 (SGD, Adam)

역전파 알고리즘

Part 3: 첫 PyTorch 모델

nn.Module 클래스

forward() 정의

모델 훈련 루프

Plotly로 손실 곡선

실습:

간단한 회귀 문제

이진 분류 문제

학습 과정 시각화

### Day 16-1: MLP (Multi-Layer Perceptron) (2h)

학습 목표:

다층 퍼셉트론 이해

은닉층의 역할

과적합 방지 기법

주요 내용:

Part 1: MLP 아키텍처

입력층, 은닉층, 출력층

Layer Normalization

Dropout

Batch Normalization

Part 2: 하이퍼파라미터

학습률 (Learning Rate)

배치 크기 (Batch Size)

에포크 (Epochs)

Early Stopping

실습:

MNIST 손글씨 분류

Fashion MNIST 분류

Plotly 대시보드 (정확도, 손실)

### Day 16-2: DNN (Deep Neural Network) (3h)

학습 목표:

깊은 신경망 구축

가중치 초기화

학습률 스케줄링

주요 내용:

Part 1: 깊은 네트워크

여러 은닉층 쌓기

Residual Connection 소개

Gradient Vanishing/Exploding 문제

Part 2: 학습 기법

Xavier/He 초기화

Learning Rate Scheduler

Gradient Clipping

Weight Decay (L2 정규화)

Part 3: 모델 저장 및 로드

torch.save() / torch.load()

Checkpoint 관리

모델 배포 준비

실습:

Tabular 데이터 분류 (고객 이탈 예측)

깊은 네트워크 실험

학습 과정 모니터링 대시보드

### Day 17: CNN (이미지) + RNN (시퀀스) (8h)

### Day 17-0: CNN (Convolutional Neural Network) (4h)

학습 목표:

합성곱 신경망 이해

이미지 데이터 처리

전이 학습 (Transfer Learning)

주요 내용:

Part 1: CNN 기초

Convolutional Layer (Conv2d)

Pooling Layer (MaxPool, AvgPool)

Flatten

CNN 아키텍처 설계

Part 2: 고급 CNN 기법

Data Augmentation (변환, 회전, 플립)

Padding, Stride

Batch Normalization

Global Average Pooling

Part 3: 유명 아키텍처

LeNet-5

AlexNet 소개

VGG16 소개

ResNet 소개

Part 4: Transfer Learning

Pre-trained 모델 활용

Fine-tuning

Feature Extraction

실습:

CIFAR-10 이미지 분류

사용자 정의 데이터셋 분류

ResNet Pre-trained 모델로 전이 학습

Plotly로 Confusion Matrix, 샘플 예측

### Day 17-1: RNN (Recurrent Neural Network) (4h)

학습 목표:

순환 신경망 이해

시계열/텍스트 데이터 처리

LSTM과 GRU

주요 내용:

Part 1: RNN 기초

RNN 개념 및 아키텍처

시퀀스 데이터 표현

Hidden State

Vanishing Gradient 문제

Part 2: LSTM (Long Short-Term Memory)

LSTM 셀 구조

Forget Gate, Input Gate, Output Gate

Cell State

nn.LSTM 사용법

Part 3: GRU (Gated Recurrent Unit)

GRU vs LSTM

더 간단한 구조

nn.GRU 사용법

Part 4: 시퀀스 모델링

Many-to-One (감성 분석)

Many-to-Many (시계열 예측)

Bidirectional RNN

실습:

주가 예측 (시계열)

영화 리뷰 감성 분석 (텍스트)

Plotly로 예측 vs 실제 비교

### Day 18: Seq2Seq + Attention + Transformer (8h)

### Day 18-0: Seq2Seq (Sequence-to-Sequence) (2.5h)

학습 목표:

Encoder-Decoder 아키텍처

번역 모델 이해

Teacher Forcing

주요 내용:

Part 1: Seq2Seq 기초

Encoder-Decoder 구조

Context Vector

Teacher Forcing

Inference (Greedy, Beam Search)

Part 2: 구현

Encoder (LSTM/GRU)

Decoder (LSTM/GRU)

입력/출력 임베딩

훈련 루프

실습:

간단한 기계 번역 (영어 → 한글)

날짜 형식 변환

번역 결과 시각화

### Day 18-1: Attention Mechanism (2.5h)

학습 목표:

Attention 메커니즘 이해

Seq2Seq에 Attention 적용

Attention 가중치 시각화

주요 내용:

Part 1: Attention 기초

Attention의 필요성

Query, Key, Value

Attention Score 계산

Softmax로 가중치

Part 2: Attention 종류

Additive Attention (Bahdanau)

Multiplicative Attention (Luong)

Self-Attention

Part 3: Attention with Seq2Seq

Encoder에서 모든 Hidden States 사용

Decoder에서 Attention 적용

Context Vector 동적 계산

실습:

Attention 기반 번역 모델

Plotly로 Attention Heatmap 시각화

### Day 18-2: Transformer (3h)

학습 목표:

Transformer 아키텍처 완전 이해

Multi-Head Attention

Positional Encoding

주요 내용:

Part 1: Transformer 기초

“Attention is All You Need”

RNN 없이 순수 Attention

Encoder-Decoder Stack

Positional Encoding

Part 2: Multi-Head Attention

여러 Attention Head

Parallel 처리

Concatenation

Part 3: Feed-Forward Network

Position-wise FFN

Layer Normalization

Residual Connection

Part 4: 구현

nn.TransformerEncoderLayer

nn.TransformerDecoderLayer

Masking (Padding, Future)

실습:

간단한 Transformer 모델

텍스트 분류

Attention 가중치 시각화

## Day 19: BERT + GAN + 최종 프로젝트 (8h)

### Day 19-0: BERT (Bidirectional Encoder Representations from Transformers) (2h)

학습 목표:

BERT 개념 이해

Pre-trained BERT 활용

Fine-tuning

주요 내용:

Part 1: BERT 기초

Masked Language Model (MLM)

Next Sentence Prediction (NSP)

Bidirectional Context

Tokenization (WordPiece)

Part 2: Hugging Face Transformers

transformers 라이브러리

AutoModel, AutoTokenizer

Pre-trained 모델 로드

Fine-tuning 전략

Part 3: 응용

텍스트 분류

개체명 인식 (NER)

질의응답 (QA)

실습:

한국어 BERT (KoBERT)로 감성 분석

Fine-tuning

분류 결과 대시보드

### Day 19-1: GAN (Generative Adversarial Network) (2h)

학습 목표:

GAN 개념 이해

Generator와 Discriminator

이미지 생성

주요 내용:

Part 1: GAN 기초

Generator (생성자)

Discriminator (판별자)

Adversarial Loss

MinMax Game

Part 2: GAN 훈련

교대 훈련 (Alternating)

Mode Collapse 문제

Wasserstein GAN 소개

Part 3: GAN 변형

DCGAN (Deep Convolutional GAN)

Conditional GAN

StyleGAN 소개

실습:

MNIST 손글씨 생성

DCGAN으로 얼굴 생성

생성 이미지 갤러리

### Day 19-2: 최종 딥러닝 프로젝트 (4h)

프로젝트 선택:

이미지 분류 + 객체 탐지

사용자 정의 데이터셋

CNN + Transfer Learning

실시간 예측 데모

Plotly 대시보드

챗봇 구축

Seq2Seq + Attention

또는 BERT 기반

간단한 대화 시스템

웹 인터페이스

시계열 예측 + 이상 탐지

LSTM/GRU

Autoencoder

실시간 모니터링

인터랙티브 대시보드

이미지 생성 (GAN)

특정 도메인 (얼굴, 패션 등)

DCGAN 또는 StyleGAN

생성 이미지 갤러리

웹 데모

작업 프로세스:

문제 정의 및 데이터 준비

모델 아키텍처 설계

데이터 전처리 파이프라인

모델 훈련 및 튜닝

성능 평가

모델 저장 및 배포 준비

대시보드/데모 구축

리포트 및 발표

결과물:

PyTorch 모델 (.pth)

Jupyter Notebook

웹 데모 (Streamlit/Gradio)

발표 자료

## 📝 평가 방법

일일 평가
퀴즈 (⭐~⭐⭐⭐⭐⭐ 난이도): 각 Day 종료 시

주간 평가
Week 1: Day 3 종합 실습 (Python 기초 점검)

Week 2-3: 통합 프로젝트 (데이터 수집 + DB + 텍스트 분석) - Week 3 금요일 발표

Week 4: Kaggle 미니 대회 (전통적 ML 경쟁) - Day 14 오후 리더보드 공개

Week 4-5: 최종 통합 프로젝트 (ML + DL) - Week 5 금요일 발표

## 📝 평가 기준

- 코드 품질 (30%)
  - 가독성, 효율성, 에러 처리
- 분석의 깊이 (40%)
  - 질문의 질
  - 인사이트 도출
  - 시각화 선택
- 커뮤니케이션 (30%)
  - 리포트 작성
  - 발표 능력
  - 팀워크 (해당 시)

## 추천도서

- “파이썬 데이터 분석” (웨스 맥키니)
- “핸즈온 머신러닝” (오렐리앙 제롱)
- “밑바닥부터 시작하는 데이터 과학” (조엘 그루스)
- “PyTorch로 시작하는 딥러닝” (엘리 스티븐스)
- “밑바닥부터 시작하는 딥러닝” (사이토 고키)

## 학습자료

- Kaggle Learn
- DataCamp
- Real Python
- PyTorch Tutorials
