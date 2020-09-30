# Design and deliver an end-to-end Business Intelligence (BI) solution

## Client Brief
1. Track KPIs (sales, revenue, profit, returns)
2. Compare regional performance, analyze product-level trends and forecasts
3. Identify high-value customers

### Objectives
- ** Filler ** Utilise BI software to achieve above requirements for ease of consumption by end user
- Ingest raw data
- Clean and prepare data
- Build data analytical model
- Build sheets
- Build complete dashboard

### Data model
#### Data cleaning
 - Imported raw csvs
    - Client data
 - Check overall quality of data:
 ..1. nulls
 ..2. type casting
 ..3. new columns/split text
 ..4. remove trailing spaces

#### Data manipulation
 - Extract year, month, day, start of week, etc from single time string

#### Date Modelling
 - Analyse available keys, there data formats
 - Create normalised database through relationships, blends and joins
 - Create snowflake schema based on relationships