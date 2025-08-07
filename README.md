# Ethiopian Medical Business Data Platform

## 📌 Project Overview

This project builds a robust data platform to generate insights about Ethiopian medical businesses using data scraped from public Telegram channels. It combines modern data engineering practices with AI-powered enrichment to answer key business questions.

## 🎯 Goals

- Extract and store raw data from Telegram channels
- Clean and transform data into a dimensional star schema using dbt
- Enrich image data using YOLO object detection
- Expose insights through an analytical API using FastAPI

## 🛠️ Technologies Used

- **Telethon** – Telegram API scraping
- **PostgreSQL** – Data warehouse
- **dbt** – Data transformation and modeling
- **YOLOv8 (Ultralytics)** – Object detection on images
- **FastAPI** – Analytical API development
- **Docker** – Containerized environment
- **Google Colab** – Development environment
- **GitHub** – Version control and collaboration

## 🚀 Setup Instructions

### 1. GitHub Setup
- Create a new repository on GitHub
- Clone it in Google Colab:
  ```python
  !git clone https://github.com/YOUR_USERNAME/ethiomed-data-platform.git
  %cd ethiomed-data-platform
  ```
