# portfolio
real-time-iot-dashboard-influxdb-grafana
# 🛰️ Real-Time IoT Dashboard with Node-RED, InfluxDB & Grafana

## 🔧 Tools Used:
- Node-RED (for MQTT integration)
- InfluxDB (time-series database)
- Grafana (dashboard visualization)
- MQTT (sensor data protocol)

## 📌 Project Description:
This project captures real-time sensor data (e.g., OEE(Overal Equipment Effectiveness) metrics, temperature, vibration) using MQTT, processes it through Node-RED, stores it in InfluxDB, and visualizes the live data using Grafana dashboards.

## ⚙️ Workflow:
1. **MQTT** receives sensor data in JSON format.
2. **Node-RED** parses and routes data to InfluxDB.
3. **InfluxDB** stores time-series metrics.
4. **Grafana** visualizes KPIs like temperature trends, machine health, energy usage.

## 🖥️ Sample Grafana Dashboards:
![Grafana Dashboard](images/grafana-dashboard.png)

## 🧠 What I Learned:
- Handling real-time data pipelines
- Time-series storage using InfluxDB
- Building live dashboards in Grafana
- Structuring flows in Node-RED
