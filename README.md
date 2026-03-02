# Weather-forecast
Weather daily forecast for cities

**Goal:** To provide high-resolution, short-term predictions for the next 10 days, allowing cities to manage daily operations and execute immediate responses to upcoming weather events.

---

### 🛠 Technical Overview
* **Provided by:** Ficlima & Municipia.
* **Methodology:** Raw models optimized through **Machine Learning (AI)** methods using local observed data from city weather stations.
* **Delivery:** Optimized daily forecasts supplied to URBREATH tools via **WMS**.
* **Update Frequency:** 🕒 **Daily.** The information is refreshed every 24 hours.

---

### 📊 Data & Variables: Probabilistic Forecast
The system focuses on the probability of reaching specific conditions to improve risk management.

| Category | Variables Included |
| :--- | :--- |
| **Basic Variables** | Maximum Temperature, Minimum Temperature, Daily Accumulated Precipitation, and Daily Highest Wind Gust. |
| **Tailored Variables** | Indicators co-defined with cities (combining basic variables), list to be presented at the Pilsen event. |

---

### 🔍 How to Interpret the Data
The interpretation is optimized through the use of **thresholds**.
* **Custom Thresholds:** The tool offers an extensive range for each variable.
* **Probability of Exceedance:** Users can select the most relevant thresholds for their specific interests and consult the probability of those limits being exceeded over the next 10 days.

---

### 💡 Practical Example: Safety & Planning
> **Case Study (Madrid):** Outdoor work is restricted under extreme heat conditions (e.g., temperatures > 35°C). Using this tool, city managers can assess the probability of exceeding this 35°C threshold to plan outdoor activities safely and comply with labor regulations.

---

### 🔗 Explore the Tool
You can access the weather visualization system here:
👉 [Ficlima Weather Tool](https://urbreath.virtualcitymap.de/ficlima/)

---

### 🔗 Synergies with other scales
Weather forecasts are the final operational link. While **Climate Projections** identify long-term risks and **Seasonal Forecasts** show monthly trends, the **Weather Forecast** provides the precise data needed for immediate action and protection of NBS assets.
