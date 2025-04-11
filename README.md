# Project_Omega2k25
Real-time Crowd Density &amp; Movement Monitoring System using ESP32-CAM, YOLOv5/v8, FastAPI, WebSockets, and LED alert indicators. Built to enhance safety in public spaces through AI-based analytics and anomaly detection.
# Crowd Density & Movement Monitoring System

This is a real-time AI-powered system to monitor and analyze crowd density and movement patterns using ESP32 cameras and YOLO models. It triggers visual alerts via LED indicators to prevent dangerous overcrowding.

## Features
- YOLOv5/v8-based person detection
- Crowd density estimation and anomaly detection
- Real-time alerting using LEDs
- Web dashboard with heatmaps and predictions
- Device management for ESP32-CAM and system monitoring

## Hardware
- 3 Laptops (1 with RTX3050)
- 4 ESP32-CAMs
- 5 LED indicators

## Tech Stack
- Python 3.10
- YOLOv5/YOLOv8
- FastAPI
- WebSockets
- MongoDB or InfluxDB
- OpenCV

## Getting Started

```bash
python3.10 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
