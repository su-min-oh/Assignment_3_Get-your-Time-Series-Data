# Assignment_3_Get-your-Time-Series-Data

## 1. CSV file uploaded to repository
## 2. Data Dictionary

| Variable                             | Variable Name | Measurement Unit | Allowed Values     | Description |
|--------------------------------------|---------------|------------------|--------------------|-------------|
| Year                                 | Year          | Year             | 2000-2023          | The year in which the data was recorded          | 
| Month                                | Month         | Month            | 1-12               | The month in which the data was recorded          | 
| Domestic Air Travel Passengers       | Dom_Pax       | Numeric          | 2877290-75378157   | Number of domestic travel passengers for the month        |
| International Air Travel Passengers  | Int_Pax       | Numeric          | 136609-12432615    | Number of international travel passengers for the month          |
| Total Air Travel Passengers          | Pax           | Numeric          | 3013899-87810772   | Number of total travel passengers for the month |
| Domestic Number of Flights           | Dom_Flt       | Numeric          | 217262-890938      | Number of domestic flights for the month |
| International Number of Flights      | Int_Flt       | Numeric          | 4996-82681         | Number of international flights for the month |
| Total Number of Flights              | Flt           | Numeric          | 222280-964102      | Number of total flights for the month |
| Domestic Revenue Passenger-Miles     | Dom_RPM       | Numeric          | 2551127-72267904   | Total miles traveled by domestic travel passengers, reported in thousands |
| International Revenue Passenger-Miles| Int_RPM       | Numeric          | 356762-31376000    | Total miles traveled by international travel passengers, reported in thousands |
| Total Revenue Passenger-Miles        | RPM           | Numeric          | 2907889-103643904  | Total miles traveled by all travel passengers, reported in thousands |
| Domestic Available Seat-miles        | Dom_ASM       | Numeric          | 19489079-81997399  | the product of the number of seats available and the distance flown, reported in thousands(domestic) |
| International Available Seat-miles   | Int_ASM       | Numeric          | 1541419-35326191   | the product of the number of seats available and the distance flown, reported in thousands(international) |
| Total Available Seat-miles           | ASM           | Numeric          | 21030499-117312202 | the product of the number of seats available and the distance flown, reported in thousands(total) |
| Domestic Load Factor                 | Dom_LF        | Numeric          | 13.09-89.96        | percentage of RPM/ASM, indicating the efficiency of utilization(domestic) |
| International Load Factor            | Int_LF        | Numeric          | 23.15-89.44        | percentage of RPM/ASM, indicating the efficiency of utilization(international) |
| Total Load Factor                    | LF            | Numeric          | 13.83-89.14        | percentage of RPM/ASM, indicating the efficiency of utilization(total) |

## 데이터 수집 방법

- **날짜 및 기온 데이터**: 매일 자동으로 기상청에서 수집합니다.
- **판매량 데이터**: 매일 매장 폐점 후 집계하여 기록합니다.
- **고객 유형 및 만족도**: 고객이 제공한 정보 및 설문 조사를 통해 수집합니다.

## 데이터의 중요성

이 데이터 세트는 기업의 일일 운영에 대한 통찰을 제공하고, 기후 변화가 판매량에 미치는 영향을 분석하기 위해 사용됩니다. 또한 고객 만족도 점수를 통해 서비스 개선에 필요한 중요 정보를 제공합니다.

