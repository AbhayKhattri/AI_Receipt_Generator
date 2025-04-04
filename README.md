# AI-Powered Recipe Generator (Cyfuture Assignment)

This project is an AI-powered recipe generator built in Python that allows users to input the name of a dish (e.g., "pasta", "chicken curry", or "vegan biryani") and get relevant recipes, ingredients, and instructions. It uses fuzzy matching and NLP techniques to handle user input variations.

---

##  Tech Stack

- Python
- spaCy: for NLP and named entity recognition
- Pandas: for data manipulation
- FuzzyWuzzy & RapidFuzz: for fuzzy string matching
- Jupyter Notebook

---

##  Features

- Accepts user input for dish names.
- Finds the best match using exact and fuzzy search.
- Displays dish name, ingredients, and cooking steps.
- Handles typos and similar-sounding dish names.
- Uses an external recipe CSV dataset.

---

##  Dataset

The project uses a custom `recipe_df.csv` dataset with the following columns:

- Dish: Name of the dish
- Ingredients: List of ingredients
- Steps: Step-by-step cooking instructions

---

##  How It Works

1. The user is prompted to enter a dish name.
2. The system searches for an exact match.
3. If no exact match is found, it uses fuzzy matching to suggest the closest recipes.
4. Displays the matched recipe with ingredients and instructions.

---

##  Running the Notebook

1. Clone this repository.
2. Open the Jupyter notebook: `Cyfuture Assignment.ipynb`.
3. Install dependencies:

