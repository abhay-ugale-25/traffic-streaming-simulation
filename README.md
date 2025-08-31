# Traffic Streaming Simulation

This project simulates a real-time data streaming pipeline using Python. It demonstrates the concepts of batch streaming, data processing, and dynamic visualization without relying on big data frameworks like Apache Spark or Kafka. Instead, it uses Python generator functions and Matplotlib to mimic a streaming workflow.

## Features

* Simulates streaming with Python generator functions
* Processes traffic data in batches
* Updates plots in real time after each batch
* Provides summary statistics for each batch (average traffic, max temperature, common weather)
* Notebook is configured to stop after processing 10 batches as a sample demonstration

## Dataset

The project uses the [Metro Interstate Traffic Volume dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume), which contains hourly traffic data, weather conditions, and timestamps.

## Requirements

Install the following Python libraries:

```
pandas
matplotlib
ipython
time
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/traffic-streaming-simulation.git
   cd traffic-streaming-simulation
   ```

2. Open the notebook in Jupyter or Colab:

   * Jupyter: `jupyter notebook traffic_streaming.ipynb`
   * Colab: Upload the notebook and dataset to Google Colab.

3. Run all cells sequentially.

4. Observe:

   * Real-time updating line plots of traffic volume and temperature
   * Bar chart of weather frequency
   * Final summary DataFrame of all processed batches
