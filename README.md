# Smart City Dashboard with Accessibility Features

## Overview

The **Smart City Dashboard** is an interactive web application that visualizes key city data in real-time. It provides insights into **traffic conditions**, **air quality**, and **public transit efficiency**. Additionally, it features **accessibility information** such as elevator availability and wheelchair access at public places. This project leverages **machine learning**, **real-time data integration**, and **data visualization** techniques to provide a comprehensive view of a city's operational efficiency and inclusivity.

## Key Features

- **Traffic Data**: Real-time traffic status and forecasting using historical data.
- **Air Quality**: Displays current air quality levels based on the OpenWeatherMap API.
- **Public Transit**: Live public transportation data from city transit APIs.
- **Accessibility**: Real-time information on accessible locations such as elevators and wheelchair access in public buildings.
- **Machine Learning Models**: Traffic forecasting using regression models or time-series forecasting techniques.
- **Real-Time Updates**: The dashboard automatically updates key metrics to reflect real-time data.

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: Dash, Plotly, HTML, CSS, JavaScript
- **Data Sources**:
  - OpenWeatherMap API for air quality
  - Google Maps API for traffic data
  - City transit APIs for public transport data
  - Custom or open data for accessibility information
- **Machine Learning**: Scikit-learn for traffic prediction

## Getting Started

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/smart-city-dashboard.git
   cd smart-city-dashboard



# Datasets for Smart City Dashboard

This folder contains the datasets used for the Smart City Dashboard project.

## Contents

### 1. Raw Data
- **traffic_data.csv**:
  - **Description**: Historical traffic data for real-time forecasting.
  - **Columns**:
    - `timestamp`: Time of data collection.
    - `location_id`: Unique ID for traffic location.
    - `traffic_density`: Traffic density score (1–10).
  - **Source**: Simulated data or city traffic API.

- **air_quality.csv**:
  - **Description**: Air quality levels by city or region.
  - **Columns**:
    - `timestamp`: Time of data collection.
    - `region`: Region or location name.
    - `aqi`: Air Quality Index.
  - **Source**: OpenWeatherMap API.

- **public_transit.csv**:
  - **Description**: Real-time public transit updates.
  - **Columns**:
    - `timestamp`: Time of data collection.
    - `route_id`: Public transit route ID.
    - `status`: Current status (on-time, delayed, etc.).
  - **Source**: Local transit APIs.

- **accessibility.json**:
  - **Description**: Real-time data on accessibility features.
  - **Fields**:
    - `location`: Name of the building or station.
    - `elevator_status`: Current status (working, under maintenance).
    - `wheelchair_access`: Availability (yes/no).
  - **Source**: Simulated data or APIs.

### 2. Processed Data
- **Description**: Cleaned and transformed datasets for analysis and machine learning.

### 3. Machine Learning Models
- **Description**: Trained models for traffic forecasting.
- **Files**:
  - `traffic_forecast_model.pkl`: Pickle file of the regression model.
  - `time_series_model.pkl`: Pickle file of the time-series model.

## Data Setup

### 1. Fetch the Data
- **Traffic Data**: Download from [City Traffic API](#) or use the provided `traffic_data.csv`.
- **Air Quality Data**: Obtain via the [OpenWeatherMap API](https://openweathermap.org/).
- **Public Transit Data**: Access through your local transit API.

### 2. Generate Data
For simulated datasets:
```bash
python src/data_processing.py


