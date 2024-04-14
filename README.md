# One_Tap_Emergency_Solution_using_Here [run index.html to webpage]

This HTML page utilizes the HERE API to locate nearby services(hospitals) based on the user's current location. It displays a map with the user's location marked by a home icon and the nearest hospital marked by a hospital icon. Additionally, it provides a button for emergency situations that sends an SMS containing the user's location to a specified recipient using Twilio's API.

Features:
Map Display: Shows a map using HERE API, centered at the user's current location.
Nearby Hospitals: Utilizes the HERE Places API to find and display nearby hospitals.
Emergency Button: Sends an SMS with the user's location to a predefined recipient in case of an emergency.
Reverse Geocoding: Converts the user's coordinates into a human-readable address.
Routing Service: Calculates the route and duration from the user's location to the nearest hospital.
Technologies Used:
HTML: Structure and content of the webpage.
CSS: Styling for the webpage elements.
JavaScript: Logic for fetching data, handling user interaction, and sending SMS.
HERE API: Provides map display, search for nearby hospitals, and reverse geocoding functionalities.
Twilio API: Enables sending SMS messages.
How to Use:
Enable Geolocation: Allow the browser to access your location.
View Nearby Hospitals: See hospitals near your location marked on the map.
Emergency Button: Click the "Emergency" button to send an SMS with your location to the specified recipient.
Important Notes:
Browser Compatibility: Geolocation feature needs to be supported by the browser.
API Keys: Ensure proper configuration of HERE API and Twilio API keys.
Recipient Number: Adjust the recipient's phone number in the sendMessage function according to your needs.
Contributors:
Developed by: [Team Yuktika]
Contact detail:[1priyagupta2003@gmail.com]


