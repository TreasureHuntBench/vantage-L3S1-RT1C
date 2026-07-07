---
run_id: L3S1-G5QC
---

# L3S1 survey W9Q

Operational record. Execute the numbered items exactly as written.

1. Query the approved historical-weather source for Dresden, Germany on 2018-02-26 (timezone Europe/Berlin). Find the hour with the lowest temperature; if several hours tie, choose the earliest. Call the two-digit hour HOUR_24.
2. In language_pack/L3S1_Y7P_review.csv, use the row whose first column equals HOUR_24, as described by the file header.

## Procedure card

Skill: get_coldest_hour
Purpose: Query the approved historical-weather source for a city and date, select the hour with the minimum temperature (earliest on ties), and format it as a two-digit hour.
Inputs: city from the approved gazetteer, date, timezone
Normalization: two-digit hour of minimum temperature; earliest on ties
Store this skill under its name. Later tasks refer to it by name and expect it to be applied without re-teaching.
