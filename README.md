# Call Centre Support Analytics — Performance, Traffic & Satisfaction Dashboard
A dynamic and interactive Excel dashboard to explore customer support data — built around agent performance, call traffic patterns, and priority-based handling.

This dashboard analyzes 46,380 support calls from a mid-sized call centre, surfacing patterns that directly affect customer satisfaction — from agent-level performance gaps to peak traffic days and a completely underutilized IVR system. It's built for operations managers, team leads, or anyone trying to figure out where their support pipeline is breaking down.

## Tech Stack

The dashboard was built using the following tools and skills:

•	📊Excel - Main data visualization platform used for report creation.

•	🔄Pivot Tables - Data summarization for analyzing on category basis.

•	🧮Dynamic formulas (AVERAGEIFS, COUNTIFS) and structured table references for clean, linked visuals. 

## Data source

Excel skills for business course

A Dummy data ~46,400 calls across 6 months in 2017. The data covers things like call timings, query types, agent details, and customer satisfaction scores.

## Feature / Highlights

•	Business Problem: 

The call centre deal with thousands of interactions daily but often struggle to pinpoint why satisfaction stays low. So I tried to answer questions like: which hours see the most drop-offs, which agents are actually resolving issues efficiently, and where the IVR is completely failing customers.
The dashboard is built entirely in Excel using Pivot Tables, slicers, and aggregation formulas — no external tools.

•	Goal of the Dashboard:

To deliver an interactive visual tool that enable the company for better understanding in distributions of customers with staff. Supports decisions such as agents allocating or more training, improving ivr on the basis of different queries for solving customers problems as fast as possible.

•	Walkthrough of key visuals:

1.	Top KPIs (gives easy understanding of key metrics) like Total Calls - 46380, Avg time of answer of call - 55, Resolving Rate - 78.3%, Calls cut (before going to a agent) - 9%, Avg satisfaction - 3.01 out of 5, No calls solved only in IVR.
2.	Peak hours for long waiting - displays around 4, customers are waiting longest.
3.	Satisfaction score by agents – Ellis got very good rating whereas adams got 1.3 less rating which can’t be ignored.  
4.	Handling time to resolution by agents – Reveals that shorter handling time doesn't always mean lower resolution — some agents resolve efficiently without long calls.
5.	Response time by priority types – tells answering high & medium priority queries taking long than low level.
6.	Resolution against total calls by query – showing more than 70% queries of first, second and third types are solved.
7.	Call traffic by days – telling Thursday getting largest calls in a week needs to allocate some more staffs. Although Sunday and Mondays are contrasting.
8.	Month, query and priority filter panel - interactive slicers lets users filter all visuals by selected months, query or priority types.

•	Business Impact & Insights:

1. The 9% Abandon Rate is a hidden cost

Nearly 1 in 10 callers hung up before reaching an agent. That's roughly 4,174 calls where the company got zero resolution and likely a frustrated customer. This ties directly back to the IVR and peak hour problems — if wait times were shorter, abandonment would drop.

2. 3.01 out of 5 satisfaction is barely passing

The average sits just above the midpoint. For a company handling 46,380 calls, that's not a small problem — it means the majority of customers are leaving the interaction feeling neutral at best. Worth framing as a baseline that the dashboard helps explain, not just report.

3. Query types 4 and 5 are struggling

It points to either complexity in those query types or agents not being trained specifically for them.

4. Short handling time ≠ low resolution — the efficiency insight

Some agents are resolving calls quickly without dragging out handle time. That's a coaching model — those agents' approaches should be studied and replicated, not just noted.

5. Sunday vs Thursday — the scheduling contrast

Thursday is peak, Sunday is the opposite. If staffing is uniform across the week, the company is simultaneously overstaffed on Sundays and overwhelmed on Thursdays. That's a scheduling fix, not a hiring problem.

## Screenshots / Demos

Show what the dashboard looks like. Example: 

https://github.com/Biswas014/Customer-Support-Analytics-Dashboard/blob/main/Customer_Support_Report_Snapshot.PNG






   


