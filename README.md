# travel_agent_llm
LangChain-based Travel Planner

--Overview
This project involves building a Conversational Travel Planner using LangChain. It allows users to plan multi-day trips, providing detailed itineraries, weather information, flight options, and recommendations for sightseeing, food, and accommodation. The AI agent is integrated with real-time data from external APIs such as OpenWeatherMap and Google Maps to provide relevant and accurate information.
---Features
•	Travel Itinerary Creation: Plan a trip with day-wise activities, travel options, and places to visit.
•	Weather Updates: Retrieve real-time weather information for the destination.
•	Flight Information: Get flight details from multiple airlines to optimize travel plans.
•	Sightseeing Recommendations: Suggestions for tourist attractions and activities.
•	Food & Accommodation Suggestions: Recommendations for dining and staying.
----Installation
To run the project, you need to set up the environment and install the required dependencies.
Prerequisites
•	Python 3.7 or above
•	An OpenWeatherMap API key
•	Google Maps API key
•	LangChain and related libraries
Steps to Set Up

OPENWEATHER_API_KEY=your_openweathermap_api_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
├── requirements.txt     # List of project dependencies
├── travel_planner.py    # Main script for travel planning
├── README.md            # This file
API Integration
OpenWeatherMap
•	Purpose: Retrieves real-time weather data to recommend optimal travel dates and prepare users for the weather conditions.
•	API Used: OpenWeatherMap API
•	Documentation: OpenWeatherMap API Documentation
Google Maps
•	Purpose: Fetches place details for sightseeing recommendations, distance information, and travel routes.
•	API Used: Google Places API & Google Distance Matrix API
•	Documentation: Google Maps API Documentation
How it Works
1.	User Input: The user initiates a conversation, providing details about their trip, such as departure location, destination, and the number of days.
2.	Weather & Flight API Calls: Based on the input, the system fetches weather details from OpenWeatherMap and flight details from a flight API.
3.	LangChain for Conversations: LangChain processes the user input and interacts with the APIs to provide tailored responses for weather forecasts, flight options, and other travel-related data.
4.	Final Itinerary: The system generates a detailed itinerary, including sightseeing, food, accommodation suggestions, and travel logistics.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgements
•	LangChain for building the conversational agent framework.
•	OpenWeatherMap for providing weather data.
•	Google Maps for providing location and distance information.
Contact :- ankitdaradework@gmail.com
