Weathercast Using Python and Django 
Weather-Forecast app is what the title says it is. It's a quick, simple weather app. The features include the basics, including forecasts, current temperature, pressure, humidity etc.

Intergrates with a free weatherAPI (OpenWeaterMap's) 
url = 'https://api.openweathermap.org/data/2.5/weather'
Access current weather data for any location on Earth!

## Requirements
1.  Python
2.  Django

## Setup, Installation and Run

To run the app on your local machine, you need Python , installed on your computer. Follow all the steps to run this project.
1. Create Virtual Enviornment 
    py -m venv "environment name"
    
2.  Activate `venv` virtual environment:
    source venv/Scripts/activate

3. Then enter the corresponding directory:

cd WeatherDashboard
    
4. Install all the requirements using pip:
pip install -r requirements.txt

5.	Run server:
python manage.py runserver

6. open  http://localhost:8000/
    Enter a city name in search bar and press Enter.
    View the current Weather.

# Tools
## Front-end Part
* HTML
* CSS
## Back-end
* Django

Tool Used on this project 
* Visual Studio Code

Future Improvements

1. Changes In Design
2. Add a current location locaton feature
3. Change in error handling for invalid cities
