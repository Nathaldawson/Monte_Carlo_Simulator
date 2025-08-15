# Browser-Based Monte Carlo Simulator

This is a self-contained HTML file that runs a Monte Carlo simulation for stock prices directly in a web browser. It uses JavaScript for the financial calculations and Chart.js for real-time visualization. No backend server or special setup is required.

## Features

* **Client-Side Only**: Runs entirely in the browser. No server is needed.
* **Live Visualization**: Renders each simulation path on the chart in real-time.
* **Configurable Parameters**: Adjust initial price, drift, volatility, time horizon, and the number of simulations.
* **Stop Functionality**: A running simulation can be stopped at any time.
* **Input Validation**: Ensures that valid numerical inputs are provided before running.
* **Modern UI**: A responsive, dark-themed interface for all controls and the chart.

## How to Use

1.  Save the code as an `index.html` file.
2.  Open the `index.html` file in a modern web browser (e.g., Chrome, Firefox, Edge).
3.  Adjust the parameters in the control panel.
4.  Click "Start Simulation".

## Technology

* HTML
* CSS (Embedded)
* JavaScript (Embedded)
* Chart.js (loaded from a CDN)