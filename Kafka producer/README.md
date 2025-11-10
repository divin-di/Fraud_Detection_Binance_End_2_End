# Fraud_Detection_Binance_End_2_End
# Real-Time Fraud Detection Pipeline

## Overview
This project streams live Binance transaction data via WebSocket into Kafka, processes it in real time with Spark Structured Streaming, and stores results for fraud analytics.

## Components
- **Data Source:** Binance US WebSocket (BTC/USDT trades)
- **Stream Ingestion:** Apache Kafka
- **Stream Processing:** Spark Structured Streaming (coming next)
- **Storage:** S3 / Snowflake (planned)
- **Dashboards:** Power BI / Grafana (planned)

## Setup
```bash
pip install -r requirements.txt
python kafka_producer/binance_producer.py
