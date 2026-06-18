# 🍿 Movie Box Office Revenue Predictor (Task 1)

## 📌 Project Overview
This is a simple machine learning project that predicts how much money a movie will make at the global box office. 

Instead of typing long numbers (like 50,000,000), the app lets you type the budget in simple millions (like 50) and handles the rest automatically.

---

## 🚀 Live App Link
You can test and play with the live app directly in your web browser here:

👉 **[Click Here to Open the Live Web Interface](https://huggingface.co/spaces/alizahbaig/MLtask01)**

---

## 📊 How It Works
The app uses a **Linear Regression** model trained on the TMDB 5000 Movie Dataset from Kaggle. You give it 4 simple inputs:

* **Movie Title:** The name of your movie.
* **Production Budget:** The budget entered easily in millions (e.g., 50 means $50 Million).
* **Internet Hype Level:** A slider from 1 to 300 to guess how much online buzz the movie has.
* **Runtime:** How long the movie is in minutes.

---

## ⚙️ How to Run It Locally

If you want to run this code on your computer or inside Google Colab, follow these steps:

1. **Install the required libraries:**
   ```bash
   pip install gradio kagglehub pandas scikit-learn numpy
