# 🏡 Real Estate Price Predictor App

A web application that predicts the price of real estate properties based on features such as location, square footage, number of bedrooms, and more. Built with **Python**, **Flask**, and **scikit-learn**, this project demonstrates a practical application of machine learning in real estate.

---

## 🚀 Features

- 🔮 **Price Prediction**  
  Get estimated property prices based on user input.
  
- 🤖 **Machine Learning Model**  
  Trained on real-world historical housing data using `scikit-learn`.

- 💻 **Interactive Web Interface**  
  Simple and responsive frontend built with HTML, CSS, and JavaScript.

---

## ⚙️ How It Works

1. The user enters property details such as:
   - Location
   - Area (in square feet)
   - Number of bedrooms, bathrooms, etc.

2. The **Flask backend** receives this input and feeds it into a trained ML model.

3. The model processes the input and returns the predicted price to the user.

---

## 🛠️ Installation & Setup

### 📦 Prerequisites

Make sure Python 3.x is installed on your system. Install the required Python libraries:

```bash
pip install flask scikit-learn pandas numpy
```

---

### 📁 Clone the Repository

```bash
git clone https://github.com/Raaed-Mirza/Real-Estate-Price-Predictor-App.git
cd Real-Estate-Price-Predictor-App
```

---

### 🚀 Running the App

#### 1. Start the Flask Backend

```bash
cd server
python server.py
```

This will launch the backend server at `http://localhost:5000`.

#### 2. Launch the Frontend

```bash
cd ../client
```

Open `app.html` in your browser. If you're using **VS Code**, right-click the file and select **"Open with Live Server"**.

---

## 📊 Example Use Case

> Enter a 3-bedroom, 2-bathroom house in Whitefield, Bengaluru with 1200 sqft — get an instant price estimate powered by machine learning.

---

## 👨‍💻 Author

Made with ❤️ by [Raaed Mirza](https://github.com/Raaed-Mirza)

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Contributions

Feel free to fork, clone, and contribute to this project!
