# High-Volume Recruitment Loop Tracker & Operational Pipeline Engine

##  Project Architecture & Operational Overview
This repository contains an enterprise-simulated candidate infrastructure tracker engineered to manage high-volume recruitment loops at scale (aligned with Amazon operations metrics). Moving away from unformatted manual data input, this project introduces a fully relational operational design featuring data hygiene boundaries, real-time query mechanics, and data aggregation dashboards.

##  Automated Implementations & Core Functions
* **Relational Search Mechanics (`XLOOKUP`):** Programmed a dynamic user-facing search query tool that instantly tracks, parses, and extracts real-time candidate properties across multi-stage loop records based on unique candidate tokens.
* **Structural Data Hygiene (Data Validation):** Configured drop-down parameter isolation layers across core stage boundaries (`Sourced`, `Initial Screening`, `Assessment Loop`, `Offer Extended`) to block erratic manual errors and keep system data pristine.
* **Analytical Aggregations (Pivot Reporting):** Deployed live pivot data tracking blocks on the `Metrics Dashboard` tab to monitor live volume splits across active interview loops, identifying capacity constraints immediately.
* **Error-Handling Architecture:** Formulated fallback parameters (`ID Not Found` string arguments) into formulas to handle data mismatches gracefully without system display breakdowns.

##  File Structure
* `AMZN_Recruitment_Pipeline_Tracker.xlsx` - Master Automated Candidate Log Data Engine Workbook.
* `README.md` - Technical Infrastructure Workflows and Systems Documentation.
