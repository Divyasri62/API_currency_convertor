#Flask Currency Converter API
This is a simple Flask-based web application for converting currencies using the ExchangeRate-API. The application allows users to select a base currency, target currency, and input an amount, which will be converted based on the latest exchange rates.

#Features
- Convert currencies between multiple options such as USD, EUR, GBP, JPY, INR, etc.
- Simple web interface with a form to input currencies and amount.
- Exchange rates fetched from the ExchangeRate-API.

#Technologies Used
Flask: A lightweight WSGI web application framework for Python.
HTML/CSS: For the front-end.
ExchangeRate-API: API to get real-time exchange rates.
Docker: Containerization of the application.

#Prerequisites
Python 3.x
Flask
Docker

#Installation and Setup
1. Clone the repository:
git clone https://github.com/Divyasri62/API_currency_convertor.git
cd API_currency_convertor
2. Install required dependencies:
If running locally, create a virtual environment and install Flask:
pip install Flask requests
3. Run the Application
python app.py
Navigate to http://127.0.0.1:5000 in your web browser to access the application.
4. Build the Docker image:
docker build -t divya715/flask-app .
5. Run the Docker container
docker run -d -p 5000:5000 divya715/flask-app

#Author
Lalam Divya Sri
Hafeeza Bhanu Mohmmad

#Acknowledgements
ExchangeRate-API: For providing the currency conversion service.
