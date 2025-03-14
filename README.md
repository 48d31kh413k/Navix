# Navix: Your Personal Activity and Weather Guide

## 🌍 Overview
Navix is an innovative web application that combines geolocation, real-time weather data, and personalized activity suggestions to help users discover exciting local experiences.

## ✨ Features
- Real-time geolocation tracking
- Current weather information
- Personalized activity suggestions
- Interactive Google Maps integration
- Dynamic route planning
- AI-powered activity recommendations

## 🛠 Technology Stack
- Frontend: HTML, JavaScript, Google Maps API
- Backend: Django, Python
- AI Integration: OpenAI GPT-3.5
- APIs: 
  - OpenWeatherMap
  - Google Maps Places
  - Google Directions (If the directions do not show up, please ensure that the Directions API is enabled in your Google Cloud Console and that your API key is correctly configured.)

## 📋 Prerequisites
- Python 3.10+
- Django
- OpenAI API Key
- Google Maps API Key
- OpenWeatherMap API Key

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/48d31kh413k/Navix.git
cd Navix
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r backend/requirements.txt
```

### 4. Configure Environment Variables
Create a `.env` file in the `backend` directory with:
```
DJANGO_SECRET_KEY=your_django_secret_key
OPENAI_API_KEY=your_openai_api_key
WEATHER_API_KEY=your_openweathermap_api_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

### 5. Run Migrations
```bash
cd backend
python manage.py migrate
```

### 6. Start Development Server
```bash
python manage.py runserver
```

## 🔍 How to Use
1. Open the web application
2. Open http://127.0.0.1:8000/location in your web browser
3. Click "Get Weather" button
4. Allow location access
5. View weather and activity suggestions
6. Click on activities to see map details and directions

## 📂 Project Structure
```
local-explorer/
├── LICENSE
├── README.md
└── backend/
    ├── local_explorer/  # Django project settings
    ├── manage.py
    ├── requirements.txt
    └── weather/         # Main application directory
        ├── views.py     # Backend logic
        ├── urls.py      # URL routing
        └── templates/   # HTML templates
```

## 🔐 Environment Setup
Ensure all API keys are kept confidential and not pushed to version control.

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

## 🐞 Troubleshooting
- Verify API keys
- Check internet connectivity
- Ensure all dependencies are installed

## 📞 Support
For issues, please open a GitHub issue 
