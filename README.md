# Power BI – Airline CSV Data

Clean CSV files for **Power BI modeling and visualization practice**.

Perfect for students who want to:
- Practice table relationships
- Write DAX measures
- Build airline performance dashboards

---

## Files

| File | Description |
|------|-------------|
| `airlines.csv` | Airline code & name |
| `airports.csv` | IATA code, name, city, country |
| `cancellation_codes.csv` | Cancellation code & reason |
| `flights.csv` | Flight records (origin, dest, delay, date, etc.) |

---

## How to use in Power BI

1. Download the 4 CSV files  
2. Open **Power BI Desktop**  
3. **Get Data → Text/CSV** → load each file  
4. Model the relationships:  
   - `flights.origin` → `airports.iata_code`  
   - `flights.dest` → `airports.iata_code`  
   - `flights.airline` → `airlines.code`  
   - `flights.cancellation_code` → `cancellation_codes.code`

---

## Note for students
- **No .pbix file included** – build your own dashboard!  
- Data are samples (you can source real data from OpenFlights or BTS).  

*Instructor: Erica Melchor 
*Course: Flight Data Insights with Power BI
