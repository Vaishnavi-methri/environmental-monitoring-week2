# Environmental Monitoring & Pollution Control — Week 2

Simulated environmental monitoring system for **Week 2 milestone**.

## ✅ Week 2 Improvisations (What changed from Week 1)
- Added **multiple sensors** (simulated): Temperature (°C), Humidity (%), AQI.
- Implemented **CSV logging** (`environment_data.csv`) for persistent storage.
- Introduced **robust error handling** to skip faulty readings.
- Added **visualization** using matplotlib and **saved plot** as `aqi_trend.png`.
- Provided **CLI arguments** (`--samples`, `--interval`, `--csv`) for flexible runs.
- Organized code into **clean, reusable functions**.

## Project Structure
```
├── week2_environment_monitoring.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the script (default 10 samples, 1s interval):
   ```bash
   python week2_environment_monitoring.py
   ```
3. Optional: custom run
   ```bash
   python week2_environment_monitoring.py --samples 30 --interval 0.5 --csv my_data.csv
   ```
4. Output:
   - `environment_data.csv` — logged readings
   - `aqi_trend.png` — saved AQI line chart

## Example Submission Notes
**Briefly mention the improvisations done by you:**  
- Integrated temperature, humidity, and AQI simulations.  
- Logged readings to CSV with timestamp.  
- Skipped faulty readings using exception handling.  
- Visualized AQI trend and saved the plot.  
- Added CLI flags for flexible sampling.

## GitHub Repo Link (replace with your repo)
https://github.com/your-username/environmental-monitoring-week2

---
© 2025 Methri Vaishnavi. Licensed under the MIT License (see `LICENSE`).