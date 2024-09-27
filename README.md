# Assignment_3_Get-your-Time-Series-Data

## 2. Data Dictionary

## 변수 설명

| Variable                             | Variable Name | Measurement Unit | Allowed Values     | Description |
|--------------------------------------|---------------|------------------|--------------------|-------------|
| Year                                 | Year          | Year             | 2000-2023          | NA          | 
| Month                                | Month         | Month            | 1-12               | °C          | 
| Domestic Air Travel Passengers       | Dom_Pax       | Numeric          | 2877290-75378157   | 개수         |
| International Air Travel Passengers  | Int_Pax       | Numeric          | 136609-12432615    | NA          |
| Total Air Travel Passengers          | Pax           | Numeric          | 3013899-87810772   | 점수 |
| Domestic Number of Flights           | Dom_Flt       | Numeric          | 217262-890938      | 점수 |
| International Number of Flights      | Int_Flt       | Numeric          | 4996-82681         | 점수 |
| Total Number of Flights              | Flt           | Numeric          | 222280-964102      | 점수 |
| Domestic Revenue Passenger-Miles     | Dom_RPM       | Numeric          | 2551127-72267904   | 점수 |
| International Revenue Passenger-Miles| Int_RPM       | Numeric          | 356762-31376000    | 점수 |
| Total Revenue Passenger-Miles        | RPM           | Numeric          | 2907889-103643904  | 점수 |
| Domestic Available Seat-miles        | Dom_ASM       | Numeric          | 19489079-81997399  | 점수 |
| International Available Seat-miles   | Int_ASM       | Numeric          | 1541419-35326191   | 점수 |
| Total Available Seat-miles           | ASM           | Numeric          | 21030499-117312202 | 점수 |
| Domestic Load Factor                 | Dom_LF        | Numeric          |  | 점수 |
| International Load Factor            | Int_LF        | Numeric          | 고객의 서비스 만족도 (1-5 점수) | 점수 |
| Total Load Factor                    | LF            | Numeric          | 고객의 서비스 만족도 (1-5 점수) | 점수 |

## 데이터 수집 방법

- **날짜 및 기온 데이터**: 매일 자동으로 기상청에서 수집합니다.
- **판매량 데이터**: 매일 매장 폐점 후 집계하여 기록합니다.
- **고객 유형 및 만족도**: 고객이 제공한 정보 및 설문 조사를 통해 수집합니다.

## 데이터의 중요성

이 데이터 세트는 기업의 일일 운영에 대한 통찰을 제공하고, 기후 변화가 판매량에 미치는 영향을 분석하기 위해 사용됩니다. 또한 고객 만족도 점수를 통해 서비스 개선에 필요한 중요 정보를 제공합니다.

