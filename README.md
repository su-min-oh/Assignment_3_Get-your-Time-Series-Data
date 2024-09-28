# Assignment_3_Get-your-Time-Series-Data

## 1. The Data File in Excel or CSV format
"U.S. Airline Traffic Data (2003-2023)" - uploaded to repository in CSV format

<br> <br>

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

<br> <br>

## 3. Data Collection Methodology. State how the data is collected, by whom, how often, etc. 

| About     | Description   |
|-----------|---------------|
| Source    | The data was retrieved from the Bureau of Transportation Statistics (BTS), specifically from the T-100 Segment dataset.      |
| Who       | The Bureau of Transportation Statistics collects and manages this dataset.                                                   |
| How       | The data is collected from airlines operating in the United States. Airlines are required to report monthly on their operations, including the number of passengers, flights, and miles traveled. This data is aggregated and verified by the Bureau of Transportation Statistics.                  |
| Frequency | Data is collected and reported on a monthly basis.                                                                           |
| Notes     | The dataset spans from 2003 to 2023 and includes detailed information about both domestic and international flight segments. |

<br> <br>

## 4. Why does this data intrigue you?

In my opinion, airlines usage is one of the most seasonal data that we can observe in business. This dataset clearly shows a strong seasonal pattern within each year, with similar trends repeating year after year. <br>
What intrigued me is that during the COVID era, a new cyclical pattern emerged, creating a "new normal" in airline usage. <br>
I believe forecasting the expected monthly number of passengers in this new normal will be both challenging and fascinating.  <br>

