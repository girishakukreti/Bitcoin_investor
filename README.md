# Real-Time Anomaly Detection System for Cryptocurrency Investment

## Project Overview

This project involves the development of a real-time anomaly detection system for cryptocurrency investment using Python. The system applies z-score analysis to Bitcoin price data to identify anomalies and trigger SMS alerts for optimal buying or selling opportunities. The project integrates external APIs for live data retrieval, employs data visualization for better insights, and uses Twilio for sending SMS notifications.

## Features

- **Real-Time Anomaly Detection**: Uses z-score analysis to detect price anomalies in Bitcoin data.
- **SMS Alerts**: Sends notifications via SMS using Twilio for immediate actionable insights.
- **Data Retrieval**: Integrates with external APIs to fetch live Bitcoin price data.
- **Data Visualization**: Provides visual insights into price trends and anomalies.

## Components

1. **Data Retrieval**: Utilizes APIs to fetch real-time Bitcoin price data.
2. **Anomaly Detection**: Applies z-score analysis to identify significant deviations from the mean price.
3. **SMS Notifications**: Implements Twilio to send SMS alerts based on detected anomalies.
4. **Data Visualization**: Generates visual representations of price data and detected anomalies.

## Installation and Setup

### Prerequisites

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)
- Twilio account (for SMS notifications)
- API keys for external data sources


