# Interactive Weather Data Visualization

Welcome to the **Interactive Weather Data Visualization** project! This tool lets you visualize weather trends based on data captured by RTL-SDR devices using the [RTL433](https://github.com/merbanan/rtl_433) software.

The data captured can include temperature, humidity, battery status, and button presses from various weather sensors, and is displayed through interactive charts.

---

## Features

- **Interactive Visualizations**: Upload your weather data in JSON format and get interactive charts displaying:
  - Temperature (°C or °F)
  - Humidity (%)
  - Battery Status
  - Button Pressed
  
- **Device Selector**: If you have data from multiple devices, you can select which device's data to visualize.

- **Sleek and Responsive Design**: Works across multiple devices with a smooth, user-friendly interface.

---

## Project by

**Tim Digga**  
A passionate enthusiast of **RTL-SDR**, **Flipper Zero**, and electronics. I enjoy experimenting with wireless signals and creating cool, useful tools.

---

## How to Use

### Step 1: Capture Data with RTL433

You need to have an RTL-SDR device and the [RTL433 software](https://github.com/merbanan/rtl_433) installed on your system. This tool will allow you to capture data from various weather stations and devices.

**1. Install RTL433:**

Follow the installation instructions for your operating system on the [RTL433 GitHub page](https://github.com/merbanan/rtl_433).

**2. Capture Weather Data:**

Run RTL433 to start receiving data. If your weather station transmits data, RTL433 will pick it up and display it in the terminal.
To save your captured data into a json file, you need to run this command!
Example command:
```bash
rtl_433 -F json > weatherdata.json
```











## Project Overview

The **Interactive Weather Data Visualization** tool is a web-based application that allows users to upload JSON files containing weather data captured from RTL433 devices. Once the data is uploaded, the tool visualizes it through interactive charts, displaying trends such as temperature, humidity, battery status, and button presses over time.

### Features:
- Upload a JSON file containing weather data.
- Select devices from the uploaded data to visualize.
- Interactive charts showing:
  - Temperature (°C or °F)
  - Humidity (%)
  - Battery status
  - Button press events
- Sleek and responsive design.

### Technology:
- **HTML5** for structuring the page.
- **CSS** for styling the page with custom animations and a modern look.
- **Chart.js** for generating interactive charts.
- **JavaScript** for handling file uploads, data processing, and rendering charts.

### Credits:
- **Tim Digga** – Developer of this project.
- **Chart.js** – For providing the charting library used for visualizations. [Chart.js GitHub](https://github.com/chartjs/Chart.js).
- **RTL433** – For enabling weather data collection through RTL-SDR. [RTL433 GitHub](https://github.com/merbanan/rtl_433).

