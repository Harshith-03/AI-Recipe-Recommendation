# AI-Powered Recipe Recommendation System

This repository contains an AI-driven recipe recommendation system that suggests personalized recipes based on user preferences, ingredients, and historical interactions. The model leverages machine learning techniques to analyze large-scale recipe datasets and provide intelligent recommendations.

## Features
- **Data Processing:** Loads and preprocesses recipe datasets for analysis.
- **Ingredient Mapping:** Uses a mapping system to standardize ingredient names.
- **User Interaction Analysis:** Incorporates user ratings and interactions to improve recommendations.
- **Machine Learning Models:** Implements recommendation algorithms to suggest recipes based on preferences.

## Dataset
The project uses the following datasets:
- `RAW_recipes.csv`: Contains metadata for recipes, including ingredients, cooking time, and instructions.
- `RAW_interactions.csv`: Includes user interactions such as ratings and reviews.
- `ingr_map.pkl`: A mapping file for ingredient standardization.

## Installation
Ensure you have Python installed along with the required dependencies:
```bash
pip install pandas scikit-learn pickle5
```

## Usage
Run the Jupyter Notebook to explore the dataset and generate recommendations.

### Steps:
1. **Data Exploration:** Load datasets and inspect their structure.
2. **Preprocessing:** Clean and map ingredient data.
3. **Model Training:** Train machine learning models for personalized recommendations.
4. **Recommendation Generation:** Generate recipe suggestions based on user preferences.

## Future Enhancements
- Implement deep learning models for better personalization.
- Add a web interface for user-friendly recipe browsing.
- Integrate nutritional insights for health-conscious recommendations.

## License
This project is licensed under the MIT License.
