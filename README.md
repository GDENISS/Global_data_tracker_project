# COVID-19 Global Data Tracker 🌍

The COVID-19 Global Data Tracker is a Python-based data analysis project that dives into global COVID-19 trends using the Our World in Data dataset. It processes and visualizes data on cases, deaths, and vaccinations across countries, delivering insights through charts and maps. Perfect for data enthusiasts, researchers, or anyone curious about pandemic trends, this project showcases data cleaning, exploratory data analysis (EDA), and visualization using Python.

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Data Source](#data-source)
- [Visualizations](#visualizations)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 📊 Project Overview

This project analyzes global COVID-19 data to uncover patterns in cases, deaths, and vaccination rollouts. Using the Our World in Data dataset, it focuses on countries like Kenya, USA, and India (customizable), producing line charts, bar plots, and an interactive choropleth map. The script is designed for clarity and modularity, making it easy to extend or adapt.

### Objectives

- 🧹 Clean and preprocess COVID-19 data.
- 📈 Analyze trends over time for cases, deaths, and vaccinations.
- 🌎 Compare metrics across countries.
- 📊 Visualize trends with charts and maps.
- 📝 Summarize findings in a console-based report.

## ✨ Key Features

- **Robust Data Cleaning**: Handles missing values, converts date formats, and filters relevant data.
- **In-Depth EDA**: Calculates death rates and compares trends across countries.
- **Rich Visualizations**:
  - Line charts for temporal trends.
  - Bar charts for country comparisons.
  - Interactive choropleth map for global case distribution.
- **Customizable**: Easily modify countries or add new metrics.
- **Automated Outputs**: Saves plots as PNGs and maps as HTML.

## 🛠️ Tech Stack

- **Python 3.8+**
- **Libraries**:
  - pandas: Data manipulation
  - matplotlib & seaborn: Static visualizations
  - plotly: Interactive maps
- **Dataset**: Our World in Data COVID-19 CSV
- **Environment**: Terminal, VS Code, or any Python IDE

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip for installing dependencies
- owid-covid-data.csv from Our World in Data
- Optional: Git for cloning the repository

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GDENISS/covid19-global-data-tracker.git
   cd covid19-global-data-tracker
2. **covid19-global-data-tracker/**
├── covid19_data_tracker.py          # Main analysis script
├── owid-covid-data.csv              # Dataset (not in repo, download separately)
├── total_cases_over_time.png        # Output: Cases line chart
├── total_deaths_over_time.png       # Output: Deaths line chart
├── total_cases_bar.png              # Output: Cases bar chart
├── total_vaccinations_over_time.png # Output: Vaccinations line chart
├── choropleth_map.html              # Output: Interactive map
├── README.md                        # Project documentation
├── .gitignore                       # Ignore dataset and outputs


