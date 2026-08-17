# F1 Championship Tracker & Scenario Model

Dynamic Excel and Power BI model tracking F1 Driver and Constructor Championships, with automated points calculation, sprint race integration, and what-if scenario modelling — verified against official standings through Round 10.

**Status:** Excel model complete | Power BI model complete | Python extension planned

## Excel Features
* Self-updating Drivers' and Constructors' standings (leaderboards re-sort automatically as results are added)
* Sprint race and Grand Prix points integrated into a single points system
* Interactive dashboard with dropdown-filtered trend charts and gap-to-leader visualisation
* What-if scenario modelling: simulate alternate finishing positions for past or future races and see recalculated standings

**Excel skills demonstrated:**
IF, SUMIFS, VLOOKUP, XLOOKUP, INDEX/MATCH, LARGE, COUNTIF, RANK

## Power BI Dashboard
* Multi-page interactive report: Drivers, Constructors, Scenario Tool, and Overview/Summary pages
* DAX-driven standings with dynamic ranking (RANKX) and alphabetical tie-breaking logic
* Cumulative points progression charts by round for both Drivers' and Constructors' Championships
* What-if scenario tool built on Power BI's native What-If Parameter — dynamically recalculates season totals based on a hypothetical finishing position for any selected driver and race
* Combined race + sprint points modelled through table relationships and DAX measures (mirrors the Excel SUMIFS logic natively in Power BI)

**Power BI / DAX skills demonstrated:**
Power Query (unpivoting, data cleaning, ETL), data modelling & relationships, DAX measures (SUMX, RANKX, CALCULATE, FILTER, LOOKUPVALUE), What-If Parameters, interactive multi-page report design

*Note: updates via manual refresh rather than scheduled cloud refresh, as the model is built and maintained locally.*

## Roadmap
- [x] Excel model (standings, scenario modelling, dashboard)
- [x] Power BI (Power Query ETL, DAX measures, interactive report)
- [ ] Python (same dataset, extended analysis/automation)
