# Aviation Machine Learning Chatbot

**Second Prize Winner – UTA Business Symposium 2025**  

An AI-powered Streamlit chatbot and forecasting system built for smarter, greener aviation. Aviation ML Chatbot leverages Natural Language Processing (NLP), Machine Learning, and Cloud Computing to optimize fuel consumption, analyze flight trends, and provide real-time decision-making insights.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Use Cases](#use-cases)
- [Sample Visuals](#sample-visuals)
- [Business Impact](#business-impact)
- [Future Enhancements](#future-enhancements)
- [How to Run](#how-to-run)

## Overview

The aviation industry is grappling with rising air traffic, higher fuel consumption, and environmental concerns. To tackle these, **Aviation ML Chatbot** offers a comprehensive solution combining:

- AI Chatbot to handle aviation-related queries
- Predictive analytics for fuel efficiency and flight scheduling
- Visual insights into fuel burn and CO2 emissions
- Cloud-based architecture for scalability and real-time performance

## Key Features

- **AI Chatbot** – Uses OpenAI API to answer complex queries related to aviation fuel, emissions, routes, etc.
- **Predictive Modeling** – ARIMA, Random Forest, and LSTM models forecast flight trends and fuel needs
- **Document Extraction** – Supports CSV, PDF, and TXT using AWS Textract
- **Data Visualization** – Generates heatmaps, trend lines, and interactive charts
- **Cloud Integration** – Built with AWS Lambda, EC2, S3, DynamoDB, and API Gateway

## Tech Stack

| Category              | Tools/Technologies                                         |
|-----------------------|------------------------------------------------------------|
| Programming           | Python, Streamlit                                          |
| Machine Learning      | Scikit-Learn, ARIMA, LSTM, Random Forest                   |
| NLP                   | OpenAI API, LangChain                                      |
| Cloud Services        | AWS EC2       |
| Data Processing       | Pandas, NumPy, SQL                                         |
| Visualization         | Plotly, Seaborn, Matplotlib                                |
| Deployment            | Streamlit, AWS                                             |

## Use Cases

- *“Which routes have the highest fuel consumption?”*
- *“What are the seasonal patterns of flight operations?”*
- *“Can you summarize the fuel burn data from this PDF?”*
- *“How can airlines reduce CO2 emissions from JFK airport?”*

## Sample Visuals

- Fuel Burn Heatmaps
- CO2 Emission Trends
- Efficient vs Inefficient Route Comparisons
- Seasonal Traffic Forecasting using LSTM

## Business Impact

| Goal                 | Enabled Through                                         |
|----------------------|----------------------------------------------------------|
| Cost Reduction     | Forecasting, route optimization, fuel analysis           |
| Sustainability     | Emissions tracking and reduced fuel wastage             |
| Better Decisions   | Real-time, data-driven insights                          |
| Profit Maximization | Route prioritization and demand forecasting             |

## Future Enhancements

- Live integration with flight APIs and weather data
- Multilingual chatbot support
- Mobile-friendly UI
- Integration with reinforcement learning for ticket pricing

## How to Run

**Clone the repository:**
   ```bash
   git clone https://github.com/hariharan-uta/Aviation_ML_Chatbot.git
   cd Aviation_ML_Chatbot
