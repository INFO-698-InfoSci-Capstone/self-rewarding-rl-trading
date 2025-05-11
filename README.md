# A Self-Rewarding Deep Reinforcement Learning Mechanism for Trading Strategy Optimization

## 📌 Project Overview

This Capstone Project develops a novel Self-Rewarding Deep Reinforcement Learning (SRDRL) mechanism aimed at enhancing trading strategy optimization. Our proposed approach, the Self-Rewarding Double Deep Q-Network (SRDDQN), dynamically adjusts reward signals by integrating supervised learning-based predictions with expert-defined financial metrics (Sharpe Ratio, Return, Min-Max indicators).

## 🧑‍💻 Team Members

* **Project Manager:** Tanmay Naik
* **Team Member:** Sohan Shankar *(Expertise: Deep Learning, Reinforcement Learning, Financial Market Analysis)*

**Potential Advisor:** Prof. Greg Chism

## 🚩 Project Goals

* Overcome limitations of traditional static reward functions in dynamic financial environments.
* Employ advanced time-series feature extraction methods (TimesNet, WFTNet, NLinear).
* Dynamically select rewards between expert-defined metrics and self-generated predictions for robust decision-making.

## 🛠️ Methodology

The research is structured into three key phases:

1. **Data Preprocessing:**

   * Collection and preparation of historical stock market data (DJI, SP500, IXIC indices).

2. **Supervised Reward Function Training:**

   * Training a Reward Network to predict rewards based on expert features (Sharpe Ratio, Return, Min-Max).

3. **Reinforcement Learning Model Implementation:**

   * Development of the SRDDQN model leveraging supervised reward predictions.

## 📊 Key Deliverables

* **Research Paper:** Documenting the SRDRL approach, methodology, results, and comparative benchmarks.
* **Open-source Code:** Complete Python-based implementation, freely available for community use.
* **Performance Benchmarks:** Demonstration of improved cumulative return stability (>90%) and Sharpe Ratio improvements (\~20%) over baseline models.

## 📅 Project Timeline and Progress

**Week 1 (March 14, 2025):**

* Data pipeline creation with historical data extraction using yfinance.

**Week 2 (March 21, 2025):**

* Data preprocessing for daily and weekly formats.

**Week 3 (March 28, 2025):**

* Derivation and integration of weekly features into daily data.

**Week 4 (April 4, 2025):**

* Construction of expert features (Sharpe Ratio, Return, Min-Max).

**Week 5 (April 11, 2025):**

* Developed Reward Network using TimesNet for short-range correlations and local price patterns.

**Week 6 (April 18, 2025):**

* Built and trained the RL agent, achieving \~40% ROI with simulated capital.

**Week 7 (April 21, 2025):**

* Evaluated dashboard tools (Streamlit, PowerBI, Plotly) for dynamic vs. static visualization.

**Week 8 (April 28, 2025):**

* Designed research poster for the iShowcase event, highlighting full project methodology and results.

**Week 9 (May 2, 2025):**

* Finalized research poster, incorporating mentor feedback and rehearsing for the iShowcase.

**Week 10 (May 9, 2025):**

* Presented at the iShowcase event, finalized the Power BI dashboard, and updated comprehensive documentation on GitHub.

## 🚧 Challenges Faced

* Ambiguity in initial data formats.
* Restructuring data into optimal weekly formats.
* Constructing robust reward networks and fine-tuning RL models.
* Balancing visual clarity with technical accuracy for the dashboard and poster presentations.

## 🚀 Future Directions

* Refine integration of self-rewarding mechanisms for more complex market conditions.
* Enhance adaptability under diverse financial scenarios.
* Explore the integration of large language models (GPT, FinBERT) for sentiment analysis to further improve predictive accuracy.


## 💻 Technologies Used

* Python
* yfinance
* TensorFlow, Keras
* TimesNet, WFTNet, NLinear
* Power BI for dashboards


## 📧 Contact

* Tanmay Naik *(Project Manager)*
* Sohan Shankar *(Technical Lead)*

Feel free to reach out with questions or collaborations!
