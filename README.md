# n8n-weather-workflow
# Weather Forecast Workflow 🌤️

Welcome to my personal project repository! As an **Artificial Intelligence major student**, I believe that the best way to master complex systems is by bridging theoretical knowledge with practical implementation. This project documents my journey in building an automated **Weather Forecast Workflow** using **n8n**.

This workflow is the result of my self-directed study, where I translated concepts from technical books and documentation into a functional automation tool.

---

### 📖 About the Workflow
The core purpose of this workflow is to provide real-time weather updates based on user input. It demonstrates how to orchestrate various APIs to handle data processing, translation, and geocoding.

#### **How it works:**
1.  **Chat Input**: The user initiates the request by providing a city name (in any language).
2.  **Language Translation**: Using an API integration, the system automatically detects the input language and translates the city name into English to ensure compatibility with weather data sources.
3.  **Geocoding**: The system queries a Geocoding API to retrieve the exact latitude and longitude coordinates of the requested city.
4.  **Weather Fetching**: With the coordinates, the workflow fetches live weather data (temperature, conditions, etc.) from the Open-Meteo API.
5.  **Response**: Finally, the system formats the weather data and sends a user-friendly response back to the chat interface.

---

### 🛠️ Tech Stack
* **n8n**: The primary workflow automation engine.
* **Open-Meteo API**: For accurate, open-source weather data.
* **Translation APIs**: For cross-language city name handling.
* **JSON Processing**: For data mapping and transformation between nodes.

---

### 💡 My Learning Approach
This project is part of my **"Learning by Doing"** workflow. Instead of just reading theory, I document my progress by creating live, testable automated systems. Each node in this workflow represents a challenge I encountered and solved during my study sessions.

* **Status**: Active Learning / Developing
* **Goal**: To automate real-world problem solving through AI and workflow orchestration.

---

### 📫 Contact
Feel free to explore the code. If you have any suggestions for optimizing this workflow or want to discuss AI-driven automation, I would love to connect!

* **Student Major**: Artificial Intelligence
* **GitHub**: [HEIN LATT ZAW]
