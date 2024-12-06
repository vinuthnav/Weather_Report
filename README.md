Weather Fetcher
This Python application fetches and displays the current weather data for a given city using the OpenWeatherMap API. The script allows users to input a city name and receive details like the temperature and weather condition.

Features:
Fetches real-time weather data: Displays the current temperature and weather description.
Uses OpenWeatherMap API: Fetches data using the free OpenWeatherMap API.
Error handling: Catches errors like invalid city names or API request issues.
Requirements:
Python 3.x
requests library (for making HTTP requests)
Setup:
Sign Up for OpenWeatherMap API Key:

Create a free account on OpenWeatherMap.
Navigate to API Keys under your profile, and copy the generated key.
Install Dependencies:

Install the required library by running the following command in your terminal:
bash
Copy code
pip install requests
Update API Key:

Replace 'your_api_key_here' in the script with your OpenWeatherMap API key.
How to Run:
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/weather-fetcher.git
Navigate to the directory where the script is saved:

bash
Copy code
cd weather-fetcher
Run the Python script:

bash
Copy code
python weather.py
Enter the city name when prompted, and the current weather details for the city will be displayed.

Example:
If you input "London", the output will look like:

yaml
Copy code
Weather in London, GB:
Temperature: 12.3°C
Condition: Light rain
License:
This project is licensed under the MIT License.

