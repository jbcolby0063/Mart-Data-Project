# 대형 마트 고객 데이터 분석 프로젝트

## 프로젝트 소개

* 2년 치 고객 데이터를 활용해 매출에 크게 기여하는 핵심 고객 그룹을 찾고 그들의 특성과 소비 성향을 분석하는 프로젝트입니다.

* 고객을 여러 그룹으로 분류하기 위해 RFM (Recency, Frequencey, Monetary) 분석 방법을 사용했습니다.

## 프로젝트 링크

* [Project.ipynb](https://github.com/jbcolby0063/Mart-Data-Project/blob/main/Project.ipynb)

## 사용 언어와 라이브러리

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Seaborn](https://seaborn.pydata.org/)

## 데이터

1. 사용 데이터
    * [customer_data.csv](https://github.com/jbcolby0063/Mart-Data-Project/blob/main/data/customer_data.csv)

2. 데이터 설명
    * `ID`: 임의의 값으로 부여된 고객 아이디
    * `signup_ym`: 고객 가입 연월
    * `birth_year`: 출생 연도
    * `annual_income`: 연 소득
    * `marital_status`: 혼인 상태
    * `children`: 부양 자녀 수
    * `recency`: 마지막 구매일로부터 기준 시점까지 경과된 날
    * `amount_alcohol`: 주류 구매 금액
    * `amount_fruit`: 과일 구매 금액
    * `amount_meat`: 육류 구매 금액
    * `amount_fish`: 수산물 구매 금액
    * `amount_snack`: 과자 구매 금액
    * `amount_general`: 잡화 구매 금액
    * `num_purchase_web`: 웹 페이지를 통한 구매 횟수
    * `num_purchase_store`: 매장 방문을 통한 구매 횟수
    * `num_purchase_discount`: 할인을 통한 구매 횟수
    * `promotion_{숫자}`: 프로모션 1부터 프로모션 6까지 각각 참여했는지 여부를 나타내며 참여 시 1, 아닐 시 0으로 표시
    * `revenue`: 수익