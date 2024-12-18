# Air Canada Customer Seat Choice Prediction Model

This repository contains a predictive model that forecasts Air Canada customers' seat purchase decisions (ADVANCE, PREFERRED, or NO PURCHASE). The model utilizes machine learning to analyze factors such as pricing strategies, seat availability, trip details, and customer preferences.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Performance](#performance)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop a high-performance predictive model to assist Air Canada in optimizing revenue by forecasting customer seat purchase decisions based on various influencing factors. The model is evaluated based on the **F1 Score** to ensure balanced performance across all classes.

## Dataset

The dataset used for this project includes the following features:

- **Ticket Purchase Date**: The date when the ticket was purchased.
- **Flight Date**: The scheduled date of the flight.
- **Price**: Ticket price for each seat category.
- **Seat Availability**: The number of seats available in each category.
- **Trip Details**: Trip duration, destination, and origin.
- **Customer Preferences**: Historical data on customer choices, loyalty status, etc.
- **Weekday/Weekend**: Indicates if the flight falls on a weekday or weekend.

**Note**: Ensure that sensitive data is anonymized before using it in the project.

## Features

- **Time Difference**: The time between ticket purchase and flight date.
- **Price Sensitivity**: Relative impact of pricing on seat choice.
- **Weekday/Weekend Effect**: Differentiation in purchasing trends based on flight day.

## Model

The model employs machine learning techniques, tuned for high performance:

- **Algorithm**: [Insert algorithm name, e.g., Random Forest, XGBoost, etc.]
- **Evaluation Metric**: F1 Score
- **Current Accuracy**: ~93% (Targeting improvement)

## Performance

| Metric         | Value    |
|----------------|----------|
| F1 Score       | [Value]  |
| Accuracy       | ~93%     |
| Precision      | [Value]  |
| Recall         | [Value]  |

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/air-canada-seat-prediction.git
