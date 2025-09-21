# Car Price Prediction


## Overview
This project implements an end-to-end car price prediction system using FastAPI as the core backend framework. The system provides a machine learning model for predicting car prices, integrated with caching, monitoring, and observability tools. The entire pipeline is designed with scalability and production readiness in mind.

## Tech Stack
- **FastAPI**: API framework
- **scikit-learn / joblib**: ML model training and serialization
- **Redis**: Caching predictions
- **Prometheus**: Metrics and monitoring
- **Grafana**: Metrics visualization
- **Uvicorn**: ASGI server
- **Docker**: Containerization