# 신용카드 고객 세그먼트 분류 (DACON)

본 프로젝트는 데이콘 대회의 카드 고객 데이터를 기반으로 고객 세분화 모델을 구축한 기록입니다.  
데이터는 아래 네 가지 영역으로 나뉘며, 주요 변수들을 다음과 같이 분류하였습니다:

====================================================================================

## 1. 기본정보 & 고객속성
- 성별, 연령, 지역, 입회/탈회 이력
- 소지 카드 수, 이용 가능 여부
- 마케팅 수신 동의, Life Stage 등
- `Segment`, `Segment.1`, `이용금액대` 등 포함

 <고객 특성/이력 중심>

---

## 2. 카드 이용 실적 & 소비 패턴
- 이용건수/이용금액 (B0M, R3M, R6M, R12M 등)
- 일시불, 할부, CA, 카드론, 체크 등 유형별
- 쇼핑/교통/여유/납부 카테고리
- 1~3순위 업종 및 금액

 <소비 성향 + 기간별 트렌드 분석>

---

## 3. 금융 정보 & 연체/잔액 관련
- 이용 한도, 이자율, 리볼빙 비율 등
- 잔액 정보 (일시불, 할부, 카드론 등 평잔/변동률)
- 연체일수/금액, 연체원금, 회차
- 선결제/정기결제(RP) 정보 포함

 <신용 위험 & 금융 습관 분석>

---

## 4. 고객 행동 & 접점 분석
- 앱/PC/IB 접속 정보
- ARS 인입/상담/문의 내역
- TM/LMS/EM 등 컨택 히스토리
- 캠페인 접촉 수/일수

 <디지털 채널 활용도 + 고객 접촉 반응 분석>

---

## 🔗 데이터 출처

> 본 데이터는 [데이콘 - 신용카드 고객 세그먼트 분류 AI 경진대회](https://dacon.io/competitions/official/236460/data)에서 제공되며, 데이터는 공식 사이트를 통해 직접 다운로드 가능합니다.
