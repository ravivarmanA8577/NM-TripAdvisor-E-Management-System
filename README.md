
TripAdvisor E-Management App

Overview The TripAdvisor E-Management App is a Salesforce-based travel management solution designed to streamline trip planning and booking. It allows users to manage hotels, food options, flights, and customer data efficiently while automating key processes such as flight reminders and real-time updates to hotel information. This app enhances operational efficiency, improves customer satisfaction, and ensures accurate data management for travel agencies.

Features Dynamic Food Option Management: Automatically updates the total count of food options linked to hotels. Flight Reminder Notifications: Sends automated reminders for upcoming flights to customers. Customer Discounts: Calculates and applies personalized discounts dynamically. Custom Reports and Dashboards: Provides insights into booking trends and customer preferences.

Key Objects Hotel: Manages hotel data and tracks the total food options. Food Option: Links food items to specific hotels. Flight: Tracks flight schedules and sends automated notifications. Customer: Stores customer details, including discount information. Installation Instructions

Deploy Custom Objects:

Create objects: Hotel, Food Option, Flight, and Customer. Define fields as per the design specifications. Set Up Apex Classes and Triggers:

Deploy FoodOptionTriggerHandler and FlightReminderScheduledJob classes. Add FoodOptionTrigger for dynamic hotel updates. Schedule Jobs:

Use the Salesforce Developer Console to schedule FlightReminderScheduledJob. Testing:

Run test classes for FoodOptionTriggerHandler and FlightReminderScheduledJob to ensure over 90% code coverage. Usage Adding/Updating Food Options: Automatically updates the TotalFoodOptions field for the linked hotel. Flight Notifications: Sends reminders for flights departing within 24 hours. Future Enhancements Integration with third-party booking systems for real-time updates. AI-based recommendations for hotels, food, and flights.
