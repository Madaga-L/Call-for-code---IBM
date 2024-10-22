# MkulimaBot - Maize Farming Chatbot

This work is an attempt to create a Farming chatbot Using IBM's Watsonx assistant. It is designed to provide tailored maize farming advice to farmers in Tanzania. The bot offers localized information, including maize planting schedules/tips, pest control tips, weather updates, and market prices for maize based on specific regions and months. 

Features of MkulimaBot
- Maize Planting Schedules/tips: Get recommended planting times based on your location.
- Pest Control Tips: Receive advice on how to prevent and control common maize pests.
- Weather Updates: Access weather forecasts to help plan your farming activities.
- Market Prices for Maize: Query the latest predicted maize prices for your region and time period.
  
Data Sources
- The predicted maize prices come from a Random Forest model built using three years of maize price data obtained from the Tanzania Ministry of Industry and Trade. This model incorporates various factors and generates region-specific and month-specific maize price predictions. The predictions are focused on key market locations with a population of 20,000 or more, obtained from OpenStreetMap (OSM). These market predictions are integrated into the chatbot.
- Weather Data: Currently, the weather data used is not real-time, but future updates aim to make it real-time for more accurate farming insights.
