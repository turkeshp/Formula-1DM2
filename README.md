# Formula-1DM2

Formula-1DM2 is an advanced data analytics and visualization project focused on the world of Formula 1 racing. The project provides comprehensive historical analysis, deep dives into driver and constructor dominance, and a unique real-time data streaming dashboard built using Apache Kafka and Tableau.

## 📖 Project Overview

This repository began with the goal to answer one of the most exciting questions in modern motorsport:  
**How did Max Verstappen manage to beat Lewis Hamilton, who stood on the brink of a record 8th world title, in the controversial 2021 F1 season?**  
But we didn't stop there. Formula-1DM2 explores:

- The rise and rivalry of F1's greatest drivers and constructors.
- The evolution of dominance in Formula 1 across decades.
- The power of real-time analytics, demonstrated by streaming F1 data pipelines to Tableau dashboards.

### Key Features

- **Historical Data Analysis**: Compare the most dominant drivers and constructors since the inception of Formula 1.
- **2021 Title Showdown**: Special focus on the dramatic final race between Lewis Hamilton and Max Verstappen.
- **Streaming Data Pipeline**: Real-time data flow from Kafka to Tableau, enabling up-to-the-minute race analytics and dashboards.
- **Rich Visualizations**: Interactive Tableau dashboards, insightful plots, and storytelling with data.
- **Reproducible Analysis**: All code is provided in Jupyter notebooks for transparency and learning.

---

## 🗂️ Repository Structure

```
Formula-1DM2/
│
├── README.md                # This file: project overview, instructions, credits
├── LICENSE                  # Open source license (MIT)
├── .gitignore               # Files and folders to ignore in version control
├── requirements.txt         # Python dependencies
│
├── notebooks/               # Jupyter notebooks for analysis & EDA
│   └── Exam.ipynb
│
├── data/                    # Datasets (raw and processed)
│   ├── Node-Link Tree Data_Main Dataset.csv
│   ├── Node-Link Tree Data_Main Dataset111.csv
│   ├── Node-Link.csv
│   ├── results (F1 Results 2021)_results.csv
│   ├── results (F1 Results 2021)_results.xlsx
│   └── results (Onyx Data - DataDNA Dataset Challenge - April 2022 - F1 Results Data)_results.csv
│
├── images/                  # All visual assets and images used in analysis
│   ├── F1new_logo.jpeg
│   ├── LewisvsMax1.png
│   ├── Screenshot 2023-11-14 at 11.45.10.png
│   └── ... (more)
│
├── visualizations/          # Tableau workbooks and dashboards
│   ├── Basic.twb
│   ├── Formula1_StaticDashboard.twb
│   ├── Formula1_StreamingDashboard.twbx
│   └── Superstore.twbx
│
├── presentations/           # Presentation slides for sharing findings
│   └── Dataviz 2 Day 1.pptx
│
└── scripts/                 # Utility scripts (e.g., Kafka command scripts)
    └── KafkaCommands
```

---

## 🚀 How to Use This Repository

### 1. Clone the Repository

```bash
git clone https://github.com/turkeshp/Formula-1DM2.git
cd Formula-1DM2
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Explore the Analysis

- Open and run the notebooks in the `notebooks/` directory for detailed data exploration and visualizations.
- Find Tableau dashboards and workbooks in `visualizations/` for interactive data stories.
- Investigate the data streaming and Kafka pipeline in the `scripts/` folder.

### 4. (Optional) Run the Streaming Dashboard

1. Set up Apache Kafka on your machine or cloud.
2. Use scripts from the `scripts/` folder to push live or simulated F1 data streams.
3. Connect Tableau to your Kafka data source and open dashboards in the `visualizations/` folder for real-time analytics.

---

## 📊 Datasets Used

- Official Formula 1 race results (CSV & Excel)
- Onyx Data - DataDNA Dataset Challenge: F1 Results
- Custom, hand-assembled datasets for driver and constructor comparisons

**Note:** Some datasets are large. For privacy or licensing, you may need to download them from official sources.

---

## 📈 Visualizations

- Driver vs. Driver showdowns (e.g., Lewis Hamilton vs. Max Verstappen)
- Constructor dominance over time
- Real-time race dashboards (using Tableau + Kafka)
- Annotated screenshots and images in `images/`

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, etc.)
- **Jupyter Notebook** for analysis & rapid prototyping
- **Apache Kafka** for real-time/streaming data
- **Tableau** for professional dashboards
- **PowerPoint** for presentations

---

## 🤝 Contributing

Pull requests, suggestions, and collaborations are welcome. Please open an issue if you have ideas or want to report bugs.

---

## 📜 License

This repo is licensed under the MIT License (see `LICENSE` for full text).

---

## 👤 Author

Created by [turkeshp](https://github.com/turkeshp)  
Feel free to connect for F1 data discussions or analytics collaborations!
