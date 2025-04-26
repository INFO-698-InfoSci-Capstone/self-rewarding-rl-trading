# Weekly/Bi-Weekly Log From Tanmay Naik.

## Prompts
Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:

🗓 Date:
Week 1 – March 14, 2025

⏱ Number of hours:
~15-18 hours
(Constructing Project Flow, Collecting data, yfinance integration for historical price data)

🌹 Rose – Highlight of the week:
Successfully created data collection pipeline to fetch historical Index data, extracted six diifferent index data using yfinance.

🌱 Bud – Looking forward to:
Pre-processing the collected data to incorporate it with the Reward Network and further feed it to Reinforcement Learning Agent

🥀 Thorn – Challenges:
Ambiguity in collected data format.

---

🗓 Date:
Week 2 – March 21, 2025

⏱ Number of hours:
~20-25 hours
(Pre-processing the collected data)

🌹 Rose – Highlight of the week:
Successfully pre-processed the data into the expected format for easier feature engineering for expert features and seemless integration with Reward Network and RL agent.

🌱 Bud – Looking forward to:
Performing feature engineering and creating the expert features to feed into Reward network.

🥀 Thorn – Challenges:
Pre-processed data was in the daily format, our requirement is to get data in daily as well as weekly format. Restructuring data into weekly format especially following a Mon To Fri week formatting suitable for index data.

---

🗓 Date:
Week 3 – March 28, 2025

⏱ Number of hours:
~15-20 hours
(resturcturing the data to incorporate weekly features)

🌹 Rose – Highlight of the week:
Successfully derived weekly features from the daily data and merged them into the original data.

🌱 Bud – Looking forward to:
Performing feature engineering and creating the expert features to feed into Reward network.

🥀 Thorn – Challenges:
Using both the daily and weekly data to configure the expert features using the mathematical equations.

---

🗓 Date:
Week 4 – April 4, 2025

⏱ Number of hours:
~18-20 hours
(Constructing expert features and spliting data to feed it into Reward Network)

🌹 Rose – Highlight of the week:
Successfully constructed the expert features such as sharpe ratio, daily return, min-max reward and return reward

🌱 Bud – Looking forward to:
Scaling the OHLCV data for weekly and daily and feeding it to Reward Network.

🥀 Thorn – Challenges:
Constructing a custom supervised reward network which will use OHLCV and expert labels to predict rewards which in turn will be used by the RL Agent.

---

🗓 Date:
Week 5 – April 11, 2025

⏱ Number of hours:
~18-20 hours
(Constructing the Reward Network and predicting the rewards for buy sell and hold which will in turn will be fed into the RL agent)

🌹 Rose – Highlight of the week:
Successfully constructed reward Network using timesnet  block to detect mini patterns in time series datawhich will detect local price shifts, picking up momentum bursts
and learning short range correlation

🌱 Bud – Looking forward to:
Evaluating the the Reward Net block and then moving forward with construction of RL agent.

🥀 Thorn – Challenges:
deciding on the window size for reward dataset, aiming to move with the 20 day wind and going with the kernel size as 3 to look at [t-1,t,t+1] data.

---

🗓 Date:
Week 6 – April 18, 2025

⏱ Number of hours:
~18-20 hours
(Constructing the RL agent and evaluating the the agent actions visualizing them and testing them with a simulated capital)

🌹 Rose – Highlight of the week:
Successfully constructed RL Agent, trained it, recorded agent actions and visualized the buy sell actions made by RL agent. Simulated the actions by utilizing 10k capital and acheived ~40% ROI 

🌱 Bud – Looking forward to:
Fine-tuning the RL agent to make better predictions in-turn generating more ROI.

---