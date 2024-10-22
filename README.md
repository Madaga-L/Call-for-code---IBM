# MkulimaBot - Maize Farming Chatbot

This work is an attempt to create a Farming chatbot Using IBM's Watsonx assistant. It is designed to provide tailored maize farming advice to farmers in Tanzania. The bot offers localized information, including maize planting schedules/tips, pest control tips, weather updates, and market prices for maize based on specific regions and months. 

Features of MkulimaBot
- Maize Planting Schedules/tips: Get recommended planting times based on your location.
- Pest Control Tips: Receive advice on how to prevent and control common maize pests.
- Weather Updates: Access weather forecasts to help plan your farming activities.
- Market Prices for Maize: Query the latest predicted maize prices for your region and time period.
  
Data Sources
Maize Prices: Predicted maize prices are derived from a Random Forest model using 3 year price data obtained from the Tanzania Ministry of Industry and Trade. The model takes into account several factors and provides region-specific and month-specific maize price predictions.
Weather Data: Not yet real time. The goal is to make it real time.
