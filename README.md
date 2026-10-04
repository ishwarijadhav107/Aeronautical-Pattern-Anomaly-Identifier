# ✈️ AERONAUTICAL PATTERN ANOMALY IDENTIFIER

### Flight Telemetry Analysis & Dynamic Pattern Monitoring

> A data-structure-based flight telemetry analysis system that detects abnormal aircraft patterns through sequential data processing and real-time-style monitoring.

---

## 📌 Overview

**AERONAUTICAL PATTERN ANOMALY IDENTIFIER** is a flight telemetry monitoring and anomaly detection system developed as a **Fundamentals of Data Structures (FDS)** project.

The system analyzes aircraft telemetry data including **GPS coordinates, altitude, heading, and speed**. Flight points are processed sequentially and compared with consecutive points to identify unusual changes in aircraft behavior.

The project combines a **C++ data-processing and anomaly detection engine** with an interactive **HTML, CSS, and JavaScript dashboard** for entering flight data, running analysis, visualizing the flight path, and reviewing detected anomalies.

The main focus is on applying **arrays, structures/classes, traversal, sequential scanning, comparisons, and rule-based detection** to a practical aviation problem.

---

## 🎯 Objectives

- Analyze aircraft flight telemetry data.
- Store and process sequential flight points.
- Detect abnormal changes in flight parameters.
- Identify altitude drops and heading changes.
- Detect unusual holding patterns.
- Flag suspicious telemetry points and segments.
- Provide an interactive visualization of the flight path.
- Demonstrate practical applications of **Data Structures and Algorithms**.

---

## ⚙️ How the System Works

```text
        Flight Telemetry Input
                 ↓
        Store Flight Points
                 ↓
        Sequential Traversal
                 ↓
       Compare Consecutive Points
                 ↓
      ┌──────────┼──────────┐
      ↓          ↓          ↓
   Altitude    Heading     Speed
    Check       Check      Check
      ↓          ↓          ↓
      └──────────┼──────────┘
                 ↓
        Pattern Detection
                 ↓
        Anomaly Identification
                 ↓
       Flight Path Visualization
                 ↓
        Anomaly Details & Report

✈️ Flight Telemetry

Each flight point contains important aircraft parameters:

Parameter	                Description
Point ID	                Unique identifier of the telemetry point
Latitude	                Aircraft latitude
Longitude	                Aircraft longitude
Altitude	                Aircraft altitude in feet
Heading	                  Direction of aircraft movement
Speed	                    Aircraft speed in knots

🧠 Data Structures & Algorithms

The project is primarily designed around Fundamentals of Data Structures concepts.

Core Concepts Used
Arrays
Structures / Classes
Sequential Traversal
Array Scanning
Data Comparison
Searching
Sorting
Loops
Conditional Statements
Functions
Threshold-Based Processing
Time & Space Complexity

🏗️ Project Architecture

AERONAUTICAL-PATTERN-ANOMALY-IDENTIFIER/
│
├── cpp/
│   ├── Anomaly.h
│   ├── AnomalyDetector.cpp
│   ├── AnomalyDetector.h
│   ├── DSA_Utils.cpp
│   ├── DSA_Utils.h
│   ├── FlightData.cpp
│   ├── FlightData.h
│   ├── FlightPoint.h
│   └── main.cpp
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   └── dataset.js
│
├── build.bat
├── flight_analyzer.exe
├── flight_data.json
├── index.html
└── README.md

🛠️ Technology Stack
Backend / Analysis Engine
C++
Structures and Classes
Data Structures
Algorithmic Processing
Frontend / Dashboard
HTML5
CSS3
JavaScript
Data
JSON
Build
Windows Batch Script
C++ Executable
