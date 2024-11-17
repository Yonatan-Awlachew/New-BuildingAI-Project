# AI Travel Reccomender

The final project for the Building AI course  

## Summary  

The AI Travel Recommendation app is an intelligent trip organizer that integrates multimodal travel options (flights, trains, buses, ferries, etc.) and leverages AI to provide personalized route suggestions and recommendations. It simplifies trip planning and optimizes routes for travelers.  

## Background  

Planning trips with multiple modes of transport can be overwhelming. Travelers often face:  
* Difficulty comparing and optimizing routes across transport modes.  
* Challenges in managing travel budgets and preferences.  
* Frustration with adapting to sudden changes like delays or cancellations.  

Millions of trips are planned daily, making this a common issue for tourists, business professionals, and students. This idea originated from my UI/UX design course, where I focused on creating solutions to improve the user experience. Integrating AI into this project ensures smarter, stress-free travel planning.  

## Data sources and AI methods  

**Data sources:**  
- APIs from travel platforms like Google Maps, Rome2Rio, and Skyscanner for real-time transport data.  
- User-generated preferences and feedback to enhance recommendations.  
- Geo-location data for nearby transport hubs and travel updates.  

**AI methods:**  

- **Recommendation Systems**: suggest personalized travel options (routes, accommodations, activities) based on user preferences and past behavior. These systems use collaborative filtering to recommend items liked by similar users and content-based filtering to suggest items similar to those the user has shown interest in.

- **Natural Language Processing (NLP)**: enables the app to understand and process user queries in natural language. It uses intent recognition to extract key details (e.g., source, destination) and entity recognition to identify places and dates. The system can then provide tailored travel recommendations and answers to user queries.

- **Optimization algorithms**: calculate the most efficient travel plans, considering factors like cost, time, and user preferences. Techniques like Dijkstra's Algorithm and Genetic Algorithms help find the best routes and itineraries, ensuring that users get the most efficient travel options based on their needs.

## How is it used?  

The AI Travel Companion is used during trip planning and in real-time during journeys. Users input their destination, travel preferences, and priorities (e.g., budget or time), and the app provides tailored suggestions.  

**Use cases:**  
1. A traveler planning a multi-city trip with various transport options.  
2. A businessperson prioritizing efficient routes to save time.  
3. A student seeking affordable and convenient travel options.  

**Users:**  
- Tourists  
- Business professionals  
- Students  

## Challenges  

While the AI Travel Companion provides seamless trip planning, it does not solve the following:  
* **Data integration issues**: Reliable data may not be available in all regions.  
* **Real-time disruptions**: Unexpected cancellations or delays require additional resilience.  
* **Ethical concerns**: Safeguarding user data privacy and avoiding biased recommendations.  
* **Service limitations**: Dependence on APIs from third-party providers for accuracy.  

## What next?  

To enhance the project:  
* Integrate support for diverse languages and regional travel preferences.  
* Develop partnerships with travel agencies and local businesses to enrich data sources.  

## Acknowledgments  

This project draws inspiration from:  
* Building AI course by Reaktor Innovations and the University of Helsinki.  
* Travel apps like Rome2Rio, TripIt, and Omio.  
* Open-source APIs such as Google Maps and Scikit-learn for AI functionalities.  
