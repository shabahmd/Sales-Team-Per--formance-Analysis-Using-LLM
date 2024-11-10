# Sales-Team-Per--formance-Analysis-Using-LLM
# Sales Performance Analysis API

## Overview

This project provides a RESTful API to analyze sales data using a Hugging Face Large Language Model (LLM). It features endpoints for individual sales representative analysis, team performance summary, and sales trends.

## Features

- **Analyze Individual Performance:** Get detailed feedback on a specific sales representative.
- **Team Performance Summary:** Obtain an overall view of team performance.
- **Sales Trends & Forecasting:** Analyze historical sales data to predict future trends.

## Technologies Used

- **Flask:** Backend framework for creating the API.
- **Pandas:** Data manipulation and analysis.
- **Hugging Face API:** Access to powerful LLMs.
- **Ngrok:** Public tunneling for local development.

## Endpoints

### 1. **Sales Representative Performance Analysis**

- **URL:** `/api/rep_performance`
- **Method:** `GET`
- **Parameters:**
  - `rep_id` (int): The unique ID of the sales representative.
- **Response:**
  ```json
  {
    "rep_id": "123",
    "analysis": "Detailed performance insights..."
  }
