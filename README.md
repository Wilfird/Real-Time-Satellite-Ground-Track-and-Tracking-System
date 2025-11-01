# Real-Time-Satellite-Ground-Track-and-Tracking-System
Real-Time Satellite Ground Track and Tracking System

This project visualizes the real-time orbital position and ground track of satellites using their TLE (Two-Line Element) data. It provides a GUI-based interface to track satellites such as the ISS, display latitude & longitude in real-time, and show orbit paths using map visualizations.

1. Features

Real-time satellite tracking using latest TLE data
Ground track plotted live using Matplotlib & Cartopy
GUI interface to start/stop tracking easily
Displays live latitude, longitude, and position markers
Modular code — can be extended to multiple satellites

| Component   | Purpose                        |
| ----------- | ------------------------------ |
| Python 3.11 | Core language                  |
| Skyfield    | Orbit propagation from TLE     |
| SGP4        | Satellite trajectory model     |
| Cartopy     | Global map & ground track plot |
| Tkinter     | Graphical user interface       |
| Matplotlib  | Visual rendering               |


Install required libraries: pip install skyfield sgp4 cartopy matplotlib numpy

2. How to Use

Add a satellite’s latest TLE data in the script
Run the script:

python satellite_tracker.py

The GUI will open → click Start Tracking
Watch the real-time ground track update


3. Future Improvements

Multi-satellite tracking
Ground station coverage & pass prediction
Zoomable and interactive map
Flask/Django-based web dashboard

4. Applications

Space operations learning & demonstration
Amateur satellite tracking
Ground station support systems
Aerospace and defense academic projects
