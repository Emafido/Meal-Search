# 🍽️ Meal Finder App

A simple web application that lets you search for meals based on ingredients and view their recipes. Built with **HTML**, **CSS**, and **JavaScript**, and powered by the [TheMealDB API](https://www.themealdb.com/).

---

## 🚀 Features
- 🔍 Search meals by entering any ingredient.
- 📜 View recipes with detailed instructions.
- 🎥 Watch YouTube videos of the recipe preparation.
- 📱 Responsive design for both desktop and mobile.
- ⌨️ Press Enter to search (keyboard and button are linked).

---

## 📂 Project Structure
```
project/
│── index.html       # Main HTML file
│── style.css        # Styling
│── script.js        # App logic (fetches data, handles UI)
│── img/
│   └── food.jpg     # Favicon & placeholder image
│── README.md        # Project documentation
```

---

## ⚙️ How It Works
1. Type an ingredient (e.g., `chicken`) in the search box.
2. Click the **search button** or press **Enter** on your keyboard.
3. The app fetches meal data using `filter.php?i=` from TheMealDB API.
4. Click **Get Recipe** to view detailed instructions and a YouTube link.

---

## 🛠️ Technologies Used
- HTML5  
- CSS3  
- Vanilla JavaScript  
- TheMealDB API  

---

## 🔑 API Reference
- **Search Meals by Ingredient:**  
  `https://www.themealdb.com/api/json/v1/1/filter.php?i=INGREDIENT`
- **Lookup Meal by ID:**  
  `https://www.themealdb.com/api/json/v1/1/lookup.php?i=MEAL_ID`

---

---

## 💻 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/meal-finder-app.git
   ```
2. Open `index.html` in your browser.
3. Start searching for meals using the search box or Enter key.

---

## 📌 Future Improvements
- Add favorites with local storage.  
- Allow multiple ingredients search.  
- Implement pagination for results.  
- Add loading indicators while fetching data.  

---

## 📜 License
This project is free to use under the **MIT License**.
