# Assignment_3_Get-your-Time-Series-Data

## 2. Data Dictionary

## 변수 설명

| Variable | Variable Name | Measurement Unit | Allowed Values  | Description |
|----------------|------------|----------------|-------------------------------------------------|------|
| Year           | Year       | Year           | 2000-2023   | NA   | 
| Month           | Month      | Month           | 1-12                            | °C   | 
| Domestic Air Travel Passengers          | Dom_Pax    | Numeric         | 0-75,378,157                                   | 개수 |
| International Air Travel Passengers   | Int_Pax| Numeric       | 고객의 유형을 나타냄 (개인, 기업)                  | NA   |
| Total Air Travel Passengers    | Pax    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |
| Domestic Number of Flights  | Dom_Flt    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |
| International Number of Flights    | Int_Flt    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |
| Total Number of Flights   | Flt    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |
| Domestic Revenue Passenger Miles   | Dom_RPM    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |
| International Revenue Passenger Miles   | Int_RPM    | Numeric     | 고객의 서비스 만족도 (1-5 점수)                   | 점수 |


## 데이터 수집 방법

- **날짜 및 기온 데이터**: 매일 자동으로 기상청에서 수집합니다.
- **판매량 데이터**: 매일 매장 폐점 후 집계하여 기록합니다.
- **고객 유형 및 만족도**: 고객이 제공한 정보 및 설문 조사를 통해 수집합니다.

## 데이터의 중요성

이 데이터 세트는 기업의 일일 운영에 대한 통찰을 제공하고, 기후 변화가 판매량에 미치는 영향을 분석하기 위해 사용됩니다. 또한 고객 만족도 점수를 통해 서비스 개선에 필요한 중요 정보를 제공합니다.

