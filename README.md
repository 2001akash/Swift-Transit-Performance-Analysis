````markdown
# 🚚 Transit Performance Analysis

This project analyzes shipment tracking data to evaluate **transit performance** and **delivery efficiency** using the provided JSON dataset.

---

## 📁 Files

| File | Description |
|------|--------------|
| `transit_performance_analysis.py` | Main Python script |
| `Swift Assignment 4 - Dataset (1).json` | Input dataset (place in same folder as script) |
| `transit_performance_detailed.csv` | Shipment-level detailed output |
| `transit_performance_summary.csv` | Overall performance summary |
| `transit_service_comparison.csv` | Optional summary grouped by service type |

---

## ⚙️ How to Run

1. Place the JSON file (`Swift Assignment 4 - Dataset (1).json`) in the same folder as the script.  
2. Install dependencies:
   ```bash
   pip install pandas numpy
````

3. Run the analysis:

   ```bash
   python transit_performance_analysis.py
   ```

After execution, three CSV files will be created automatically in the same folder.

---

## 📊 Output Files

| File                                 | Description                                                         |
| ------------------------------------ | ------------------------------------------------------------------- |
| **transit_performance_detailed.csv** | Contains shipment-level detailed transit metrics                    |
| **transit_performance_summary.csv**  | Provides overall statistics like average, median, and total metrics |
| **transit_service_comparison.csv**   | Summarizes average transit hours and facilities by service type     |

---

## 🧮 Metrics Calculated

* Total transit time (in hours)
* Number of facilities visited
* In-transit event count
* Average hours per facility
* Out-for-delivery attempts
* First-attempt delivery status
* Service classification (Express / Standard)

---

## ✅ Features

* Handles missing and null values gracefully
* Supports multiple timestamp formats (`$numberLong`, ISO)
* Removes duplicate or invalid events
* Automatically generates clean, analysis-ready CSV outputs
* Works directly with raw FedEx-style tracking data

---
