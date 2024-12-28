# ISS-Overhead_Notifier
The ISS Overhead Notifier is a Python project that notifies you when the International Space Station (ISS) is visible overhead at your location. It uses the ISS API to determine its position and combines it with your location and weather data to ensure optimal visibility conditions.

         Features

Fetches the current location of the ISS.

Checks whether the ISS is overhead based on your geographic coordinates.

Sends notifications (via email or other preferred methods) when the ISS is visible.

Optional: Weather integration to ensure clear visibility conditions.

          Technologies Used

Python 3.x: Core programming language.

           APIs:

Open Notify ISS API: For ISS location data.

Sunrise-Sunset API: To determine nighttime hours.

(Optional) Weather API (e.g., OpenWeatherMap): For visibility conditions.

SMTP: For sending email notifications.

          Prerequisites

Python installed on your machine.

API keys for optional weather integration (if using a weather service).

Email credentials for sending notifications (if using email notifications).

        Installation

Clone the repository:

git clone https://github.com/yourusername/iss-overhead-notifier.git

      Navigate to the project directory:

cd iss-overhead-notifier

              Install the required Python libraries
pip install -r requirements.txt

                Add your location and notification details in the config.py file (if provided) or as environment variables.
