# capstone-kaggriculture

# 🌾 Kaggriculture: Autonomous AI Farm Manager Agent

## Overview

Kaggriculture is an AI-powered farm management simulation developed for the **5-Day AI Agents: Intensive Vibecoding Course with Google and Kaggle**. The project demonstrates how autonomous agents can make intelligent decisions in a dynamic environment by managing resources, responding to changing market conditions, and maximizing long-term profit.

The project implements an autonomous farming agent that continuously analyzes weather conditions, market prices, crop growth cycles, and available resources to make optimal farming decisions.

---

## Problem Statement

Agriculture involves complex decision-making regarding crop selection, resource allocation, harvesting schedules, and market participation. These decisions become more challenging when factors such as weather changes and fluctuating market prices are introduced.

The objective of this project is to develop an AI agent capable of:

- Managing a virtual farm autonomously
- Allocating resources efficiently
- Adapting to environmental changes
- Identifying profitable opportunities
- Maximizing cumulative profit over time

---

## Project Objectives

- Build an autonomous decision-making AI agent
- Simulate a realistic farming environment
- Implement a dynamic market economy
- Model weather-driven uncertainties
- Compare multiple farming strategies
- Analyze agent performance through visual analytics

---

## Key Features

### 🌱 Farm Management
- Virtual farm with multiple land plots
- Seed inventory management
- Water resource management
- Crop growth monitoring

### 🌦 Weather Simulation
- Sunny
- Rainy
- Cloudy
- Storm
- Drought

Weather conditions influence:
- Crop growth
- Water consumption
- Harvest yield

### 📈 Dynamic Market
- Daily price fluctuations
- Demand and supply effects
- Random market events
- Historical market trends

### 🤖 Autonomous AI Agent
The AI agent automatically decides:
- Which crops to plant
- When to purchase seeds
- How to allocate available land
- When to harvest crops
- When to sell produce

### 📊 Analytics Dashboard
- Profit trend analysis
- Crop selection frequency
- Resource utilization tracking
- Market price visualization
- Strategy performance comparison

---

## System Architecture

```text
+-------------------+
| Streamlit UI      |
+---------+---------+
          |
          v
+-------------------+
| Simulation Engine |
+---------+---------+
          |
  ---------------------
  |         |         |
  v         v         v
Farm     Market    Weather
  \         |         /
   \        |        /
    \       |       /
      +-----------+
      | AI Agent  |
      +-----------+
```

---

## AI Agent Workflow

1. Observe farm status
2. Analyze weather conditions
3. Monitor market prices
4. Evaluate available resources
5. Select optimal crop strategy
6. Execute farming actions
7. Harvest mature crops
8. Sell produce for profit
9. Repeat for the next simulation day

---

## Implemented Strategies

### Conservative Strategy
- Focuses on stability
- Minimizes risk
- Prioritizes consistent profits

### Profit Maximizer Strategy
- Selects crops with the highest expected returns
- Takes advantage of favorable market conditions

### Adaptive Strategy
- Responds dynamically to weather and market trends
- Balances risk and reward
- Optimizes long-term performance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Streamlit

---

## Project Structure

```text
project/
│
├── app.py
├── simulator.py
├── farm.py
├── market.py
├── weather.py
├── agent.py
├── config.py
│
├── data/
├── logs/
├── assets/
│
├── requirements.txt
└── README.md
```

---

## Simulation Process

The simulation runs for 100 virtual farming days.

During each day:

- Weather conditions are generated
- Market prices are updated
- Crop growth is processed
- AI agent makes decisions
- Transactions are recorded
- Daily profit is calculated

All results are stored for analysis and visualization.

---

## Performance Metrics

The following metrics are tracked:

- Total Profit
- Daily Revenue
- Crop Yield
- Resource Usage
- Inventory Levels
- Market Trends
- Agent Efficiency

---

## Results

The autonomous AI agent successfully demonstrates:

- Resource optimization
- Adaptive decision-making
- Economic reasoning
- Long-term planning
- Autonomous farm management

The project highlights how AI agents can operate effectively in uncertain and dynamic environments while maximizing profit and resource utilization.

---

## Future Enhancements

- Multi-Agent Competition
- Reinforcement Learning Integration
- Advanced Forecasting Models
- Real-Time Market Simulation
- Agent Collaboration and Trading
- Seasonal Farming Strategies
- Cloud Deployment

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/kaggriculture-ai-agent.git
```

### Navigate to the Project Directory

```bash
cd kaggriculture-ai-agent
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## Learning Outcomes

Through this project, the following concepts were explored:

- AI Agent Design
- Autonomous Decision Making
- Resource Optimization
- Dynamic Simulations
- Market-Based Systems
- Data Visualization
- Strategy Evaluation
- Python Application Development

---

## Acknowledgements

This project was developed as part of the **5-Day AI Agents: Intensive Vibecoding Course with Google and Kaggle**. The Kaggriculture challenge provided an opportunity to design, build, and evaluate autonomous AI agents within a simulated agricultural economy.

---

## Author

### Divyansh Deore

Aspiring AI Engineer | Data Science Enthusiast | AI Agents Developer

Connect with me on GitHub and LinkedIn to follow my projects and learning journey.

---

⭐ If you found this project interesting, consider giving it a Star on GitHub!
