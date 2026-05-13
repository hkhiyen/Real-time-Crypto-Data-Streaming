# Real-time Crypto Data Streaming Pipeline
- A real-time Big Data streaming pipeline using Apache Kafka, AWS EC2, and MinIO for collecting, processing, storing, and visualizing cryptocurrency price data.

## Architecture

CoinGecko API
→ Kafka Producer
→ Kafka Topic (crypto-prices)
→ Kafka Consumer
→ MinIO Storage
→ Realtime Dashboard

## Technologies
- Apache Kafka (KRaft Mode)
- AWS EC2
- Python (Pandas
Matplotlib)
- MinIO
- Linux
- Java 17 Amazon Corretto
# Features
- Deploy Apache Kafka on AWS EC2
- Stream realtime crypto prices from CoinGecko API
- Process data using Kafka Producer/Consumer
- Store batch CSV files into MinIO object storage
- Visualize Bitcoin & Ethereum prices in realtime
