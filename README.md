# Detection of Hardware Trojan in On-Chip Network Using Machine Learning

## Overview
This project focuses on the detection of hardware Trojans in Network-on-Chip (NoC) architectures. These Trojans, introduced maliciously during the design or manufacturing process, pose significant threats to modern integrated circuits by degrading performance and compromising system security. Leveraging machine learning techniques, this project implements a robust framework for identifying and localizing hardware Trojans, enhancing the security of NoC-based systems.

## Features
- **Machine Learning Models**: Implements Random Forest Classifier (RFC) and eXtreme Gradient Boosting (XGB) for Trojan detection.
- **Simulation Environment**: Uses Garnet 2.0 simulator to emulate traffic in an 8×8 mesh-based NoC under normal and attack conditions.
- **Feature Extraction**: Key metrics like packet latency, hop count, buffer utilization, and crossbar activity are extracted and analyzed.
- **Attack Localization**: Identifies specific routers affected by hardware Trojans.

## Technologies Used
- **Programming Languages**: Python, C (converted models for hardware-level integration)
- **Machine Learning**: Random Forest Classifier (RFC), XGBoost (XGB)
- **Simulation**: Garnet 2.0 simulator
- **Libraries**: NumPy, Pandas, scikit-learn, m2cgen, Matplotlib

## Dataset
- **Simulation Data**: Generated using Garnet 2.0 simulator for normal and Trojan-affected traffic scenarios.
- **Key Features**: Metrics include packet latency, flit latency, hop count, injection rates, crossbar activity, etc.
