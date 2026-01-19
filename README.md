# FahrbahnTyp-Erkennung
Tiny ML für Fahrbahntyp-Erkennung


## 🇩🇪 Deutsch
### Projektbeschreibung

Dieses Projekt implementiert ein eingebettetes System zur automatischen Klassifikation von Fahrbahntypen mithilfe von Inertialsensordaten.
Das System ist an einem Fahrrad montiert und führt die Inferenz lokal auf einem ATOM S3 (ESP32-S3) ohne Cloud-Anbindung aus.

### Hardware

ATOM S3 (ESP32-S3)

6-Achsen-IMU (Beschleunigung und Gyroskop)

3D-gedruckte Halterung am Fahrrad

### Funktion

Erfassung von IMU-Zeitreihen

Fensterbasierte Vorverarbeitung und Normalisierung

Klassifikation mit Embedded Machine Learning

Echtzeit-Inferenz auf dem Mikrocontroller

### Darstellung

Integrierter Webserver

Anzeige des aktuellen Fahrbahntyps und der Klassifikationswahrscheinlichkeit

Live-Visualisierung der IMU-Signale

# 🇬🇧 English
## Project Description

This project implements an embedded system for automatic road surface classification using inertial sensor data.
The system is mounted on a bicycle and performs local inference on an ATOM S3 (ESP32-S3) without cloud connectivity.

### Hardware

ATOM S3 (ESP32-S3)

6-axis IMU (accelerometer and gyroscope)

Custom 3D-printed bicycle mount

### Functionality

IMU time series acquisition

Window-based preprocessing and normalization

Embedded machine learning classification

Real-time on-device inference

### Visualization

Integrated web server

Display of current road surface type and confidence

Live IMU signal visualization
