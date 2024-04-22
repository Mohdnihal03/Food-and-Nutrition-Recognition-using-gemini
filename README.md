# Food and Nutrition Recognition using gemini 


## Your Dietitian and Nutritionist

 your personalized dietitian and nutritionist powered by advanced AI. Easily discover key details about your favorite dishes, explore cooking techniques, and get insights into nutritional values—all from a single image!

---

## Table of Contents

- [Features](#features)
- [Languages](#languages)
- [How to Use](#how-to-use)
  - [Setup](#setup)
  - [Run the Application](#run-the-application)
- [Alternative Dish Suggestions](#alternative-dish-suggestions)
- [Get in Touch](#get-in-touch)

---
## Features

- **Get Dish Name and Ingredients:** Uncover the secrets of your uploaded dish, including its name and culinary essence.

- **How to Cook:** Follow meticulous steps to craft the featured dish, from selecting the finest ingredients to mastering the cooking process.

- **Nutritional Value for 1 Person:** Receive a comprehensive overview of the dish's nutritional value, presented in descending order.

- **Alternative Dishes with Similar Nutritional Values:** Act as a dietitian and nutritionist, providing two vegetarian and two non-vegetarian dish alternatives with the same nutritional value as the original.

---

## Languages

Supports both English and Hindi, allowing you to explore the culinary world in your preferred language.

---

## How to Use

### Setup

1. **Install Required Libraries:**
   ```bash
   pip install streamlit google-generativeai python-dotenv pathlib Pillow
   ```

2. **Configure API Key:**
   - Create a `.env` file in your project directory.
   - Add your Google API key to the `.env` file:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

### Run the Application

```bash
streamlit run app.py
```

1. **Select Language:** Choose your preferred language—English or Hindi.

2. **Input Prompt:** Describe the dish or ask about its details using the input prompt.

3. **Upload Image:** Choose an image of the dish you want to explore.

4. **Explore Features:** Click on the buttons to explore dish details, cooking techniques, nutritional values, or alternative dish suggestions.

---

## Alternative Dish Suggestions

Act as a culinary matchmaker with dishes. Provide alternative dishes with parallel nutritional excellence:

1. **Vegetarian Alternatives:**
   - Craft a detailed list elucidating the nuances of two vegetarian alternative dishes with nutritional values akin to the original.

2. **Non-Vegetarian Alternatives:**
   - Extend your culinary prowess to outline a list for two non-vegetarian alternatives, ensuring a harmonious nutritional match.

---

## Get in Touch

For inquiries and support, please contact:

- **mohammed nihal**
- **Email:** mohammednihal9986@gmail.com