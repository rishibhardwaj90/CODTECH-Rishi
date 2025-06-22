NYC Taxi Data Analysis – Task 1

This project performs exploratory data analysis on a NYC taxi dataset to extract meaningful insights using Python.

Repository Structure:

```
TASK_1/
├── dataset_task1.csv                # Raw dataset used for analysis
├── Task 1.py                        # Main Python script
├── op_task1.csv                     # Output CSV containing analysis results
└── outputs_task1/                   # Generated plots and visualizations
    ├── plot_avg_tip_amount.png
    ├── plot_avg_total_amount.png
    ├── plot_avg_total_vendor.png
    ├── plot_avg_trip_distance.png
    ├── plot_daily_trip_count.png
    ├── plot_total_fare_pu.png
    └── plot_trip_count.png
```

Features:
* Reads and processes NYC taxi trip data
* Performs aggregations such as:
  * Average tip amount
  * Average total fare
  * Trip counts per day and pickup location
* Visualizes results using bar plots and line graphs
* Saves both CSV outputs and visualizations

Requirements:
* Python 3.x
* pandas
* matplotlib
* seaborn

Install dependencies using:
```bash
pip install pandas matplotlib seaborn
```

How to Run:
1. Clone the repository.
2. Navigate to the `TASK_1/` directory.
3. Run the Python script:

```bash
python "Task 1.py"
```

Output:
All generated plots will be saved in the `outputs_task1/` folder.
A summary CSV (`op_task1.csv`) will also be created.
