# Travel & Tourism Recommendation System

A comprehensive travel recommendation system built using machine learning algorithms and deployed as a Flask web application. This system provides personalized travel recommendations based on user preferences and behavior patterns.

## 🌟 Features

- **Personalized Recommendations**: Tailored travel suggestions based on user preferences
- **Multiple ML Algorithms**: Collaborative Filtering, Content-Based Filtering, and Hybrid Approach
- **Interactive Web Interface**: User-friendly Flask web application with real-time recommendations
- **Comprehensive Dataset**: Built using extensive travel and tourism data

## 🗃️ Dataset

This project utilizes the [Travel Recommendation Dataset](https://www.kaggle.com/datasets/amanmehra23/travel-recommendation-dataset) from Kaggle, containing travel destinations, user preferences and ratings, tourism activities, location-based features, and user interaction data.

## 🤖 Machine Learning Approaches

### Collaborative Filtering
- **User-Based**: Recommends destinations based on similar users' preferences
- **Item-Based**: Suggests destinations similar to those previously liked by the user

### Content-Based Filtering
- Analyzes destination features and matches user preferences with destination attributes
- Considers location type, activities, climate, and budget considerations

### Hybrid Approach
- Combines collaborative and content-based filtering for more accurate and diverse recommendations

## 🚀 Installation & Setup

### Prerequisites: Python 3.8+, Conda (recommended) or pip

```bash
# Clone repository
git clone https://github.com/yourusername/travel-recommender-flask.git
cd travel-recommender-flask

# Create virtual environment
conda create --name travel-rec python=3.8
conda activate travel-rec

# Install dependencies and run
pip install -r requirements.txt
python app.py
