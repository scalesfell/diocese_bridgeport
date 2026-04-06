# Diocese of Bridgeport: Growing Flock, Shrinking Clergy

Data analysis and visualization of Catholic population, priest, 
and parish trends in the Diocese of Bridgeport, CT (1959–2024).

Author: Frankie Noguera
Tools: Python, Jupyter Lab, Pandas, Matplotlib

## Files
- `diocese_bridgeport.ipynb` — Jupyter notebook with full analysis and visualizations

## Data Sources
- [Catholic-Hierarchy.org](https://www.catholic-hierarchy.org/diocese/dbrid.html) — Official statistics (1959–2023)
- Diocese of Bridgeport State of the Diocese Address, October 2024
- Bishop Caggiano Easter Message, April 2026 — bridgeportdiocese.org

## Methodology
- All data from 1959–2023 is sourced directly from Catholic-Hierarchy.org,
  which compiles figures from the Vatican's official Annuario Pontificio
- 2024 data points are sourced from diocesan statements rather than the 
  official Annuario Pontificio, which runs on a one-year publication lag
- The ~3,667 Catholics per active priest figure is calculated by the author 
  based on diocesan statements (440,000 Catholics ÷ 120 active priests)
- 120 active priests figure sourced from Bishop Caggiano's October 2024 
  State of the Diocese address

## Caveats
- 2024 Catholic population (440,000) is an estimate consistent with diocesan statements
- 2024 total priests (200) is carried over from 2023 pending official publication
- The ~3,667 ratio uses active priests only — not total priests
