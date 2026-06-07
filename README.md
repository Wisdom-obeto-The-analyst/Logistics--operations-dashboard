#  🚛 Logistics Operations Dashboard — Power BI

## Project Overview
A professional 4-page logistics operations dashboard built in 
Microsoft Power BI, analysing 400,000+ records across 14 
relational tables. The dashboard covers the full operational 
picture of a mid-to-large US logistics company operating 
between 2022 and 2024 — from executive financials to driver 
safety, fleet efficiency and customer profitability.

---

## Business Context
The company operates 120 trucks and 150 drivers across 
multiple routes, serving 200 customers with both Dry Van 
and Refrigerated loads. With 85,000 trips completed and 
$298.62M in revenue generated, the business is financially 
strong — but the data reveals critical operational challenges 
that require immediate attention.

---

## Dashboard Pages

### 📊 Page 1 — Executive Summary


![Executive Summary](Page%201%20Executive%20summary.png)



**Purpose:** Gives leadership a complete financial overview 
at a glance.

**KPIs:**
- Total Revenue: $298.62M
- Total Cost: $101.32M
- Total Profit: $197.30M
- Total Trips: 85,000
- Total Customers: 200

**Key Stories:**
- The business operates at a strong 66% profit margin, 
  indicating good cost control relative to revenue
- Revenue fluctuates significantly month to month, suggesting 
  over-reliance on seasonal demand rather than locked-in 
  long term contracts
- Revenue is nearly evenly split across Contract (37.64%), 
  Dedicated (31.55%) and Spot (30.81%) — showing healthy 
  booking type diversification
- RTE00044 is the top performing route at $11.2M with top 
  routes performing consistently between $9.9M — $11.2M
- Refrigerated and Dry Van loads contribute almost equally 
  at $0.15bn each — a well balanced load portfolio

---

### 🚛 Page 2 — Driver & Safety Performance


![Driver Safety](Page%202%20Driver%20and%20safety%20Performance.png)



**Purpose:** Identifies driver performance issues and 
safety risks across the fleet.

**KPIs:**
- Total Incidents: 170
- Total Drivers: 125
- On-Time Rate: 55.67%
- Average MPG: 6.50

**Key Stories:**
- The 55.67% on-time rate is a critical red flag — the 
  US and UK logistics industry benchmark is 95%+, meaning 
  more than 4 in every 10 deliveries are arriving late
- Even the best performing driver Jennifer only achieves 
  57.83% — confirming this is a systemic process problem 
  rather than individual driver failure
- Thomas leads all drivers with 9.7M miles, with the top 
  6 drivers performing consistently between 7.7M — 9.7M
- DOT Violations lead all incident types at 39 — a serious 
  compliance risk that could result in heavy regulatory 
  fines if not addressed
- Safety incidents remain consistent throughout the year 
  confirming incidents are operational rather than seasonal

---

### ⛽ Page 3 — Fleet & Fuel Efficiency


![Fleet Fuel](Page%203%20Fleet%20and%20fuel%20Effficiency.png)



**Purpose:** Analyses fleet costs, fuel efficiency and 
maintenance patterns to identify cost saving opportunities.

**KPIs:**
- Total Fuel Cost: $95.59M
- Average MPG: 6.50
- Total Maintenance Cost: $5.73M
- Fleet Utilization: 76.67%

**Key Stories:**
- At $95.59M, fuel represents 94% of total operating costs 
  — making fuel efficiency the single biggest lever for 
  improving profitability
- The fleet averages 6.50 MPG, below the US industry 
  benchmark of 7-8 MPG — closing this gap could save 
  millions annually
- TRK00059 leads fleet efficiency at 6.6 MPG — analysing 
  what makes this truck perform better could unlock 
  fleet-wide improvements
- Preventive maintenance leads all types at $0.96M — 
  reflecting a proactive maintenance culture that reduces 
  costly emergency breakdowns
- Only 76.67% of the fleet is actively generating revenue 
  with 10.83% inactive — significant untapped revenue 
  potential in the idle fleet

---

### 🗺️ Page 4 — Customer & Route Analysis


![Customer Route](Page%204%20Customer%20and%20Route%20Analysis.png)



**Purpose:** Identifies the most valuable customers and 
routes to guide sales and operations strategy.

**KPIs:**
- Total Revenue: $298.62M
- Total Loads: 85,000
- Revenue Per Mile: $2.44
- Average Revenue Per Load: $3.50K

**Key Stories:**
- First Group is the anchor customer at $10.4M — protecting 
  and growing this relationship should be a top priority
- The top 10 customers generate strong individual revenues 
  with no single customer dominating — a healthy low 
  concentration risk client base
- RTE00044 is the highest performing route at $11.2M with 
  revenue declining gradually — lower performing routes 
  should be reviewed for profitability
- Revenue is evenly distributed across Dedicated (49%), 
  Contract (25.74%) and Spot (25.26%) — a well balanced 
  and low risk booking portfolio
- Dry Van and Refrigerated loads both show mid-year dips — 
  presenting an opportunity for targeted mid-year promotions

---

## Overall Business Story
This logistics business is financially strong with a 66% 
profit margin and a well diversified customer and booking 
portfolio. However two critical operational challenges 
demand immediate attention:

1. **On-Time Delivery Rate of 55.67%** — far below the 
   95% industry benchmark, damaging customer satisfaction 
   and threatening contract renewals
2. **Fleet Fuel Efficiency of 6.50 MPG** — below industry 
   standard, driving a $95.59M fuel bill that represents 
   94% of all operating costs

Addressing these two issues through better dispatch 
planning, route optimisation and fleet fuel efficiency 
programmes would significantly improve both customer 
satisfaction and profitability.

---

## Tools & Skills Used
- Microsoft Power BI
- DAX Measures & Calculated Columns
- Power Query Data Cleaning (14 tables)
- Relational Data Modelling
- Business Insight & Storytelling

---

## Data Structure
| Table | Records | Description |
|---|---|---|
| Loads | 85,410 | Core transaction table |
| Trips | 85,410 | Trip execution details |
| Drivers | 150 | Driver profiles |
| Trucks | 120 | Fleet inventory |
| Trailers | 180 | Trailer inventory |
| Customers | 200 | Customer profiles |
| Routes | 58 | Route definitions |
| Facilities | 50 | Facility locations |
| Fuel Purchases | 196,442 | Fuel transaction records |
| Maintenance Records | 2,920 | Maintenance history |
| Delivery Events | 170,820 | Delivery tracking |
| Safety Incidents | 170 | Safety event records |
| Driver Monthly Metrics | 4,464 | Driver KPI history |
| Truck Utilization Metrics | 3,312 | Fleet KPI history |

---

## Author
**Wisdom Obeto**
Data Analyst | Open to opportunities in the UK & US
🔗 LinkedIn:https://www.linkedin.com/in/wisdom-obeto-95792533a
