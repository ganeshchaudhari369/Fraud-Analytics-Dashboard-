# Fraud Detection Dashboard

An interactive Python dashboard built with **Dash**, **Plotly**, and **Bootstrap** to analyze fraud detection data from a managerial perspective.

## Features
- **Interactive KPIs**: Real-time tracking of transaction volume, fraud cases, and financial risk.
- **Hourly Analysis**: Line charts visualizing peak fraud hours.
- **Store Type Risk Profiling**: Comparative analysis of fraud incidence across different store types.
- **Behavioral Analytics**: Distribution of transaction amounts and geographical distance risks.
- **Dynamic Filtering**: Filter data by Store Type and Hour of Day.

## Preview
The dashboard provides a clean, professional interface using the `LUX` theme.

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd "Python Dashboard"
   ```

2. Install dependencies:
   ```bash
   pip install dash dash-bootstrap-components pandas plotly
   ```

3. Run the application:
   ```bash
   python app.py
   ```
   Open [http://localhost:8080](http://localhost:8080) in your browser.

## Public Access (via ngrok)

To make your dashboard accessible over the internet:

1. Install `pyngrok`:
   ```bash
   pip install pyngrok
   ```

2. Get a free authtoken from [ngrok.com](https://dashboard.ngrok.com/get-started/your-authtoken).

3. Set your authtoken in your environment or edit `launch_public.py`.

4. Run the public launcher:
   ```bash
   python launch_public.py
   ```
   A public URL (e.g., `https://xxxx.ngrok-free.app`) will be displayed in the terminal.

## Data
The project uses `fraud.csv`. Ensure this file is present in the root directory.
