# Movie Recommender System

[cite_start]This project is a complete movie recommender system implemented using The Movies Dataset[cite: 4, 13]. [cite_start]It integrates key machine learning topics, including exploratory data analysis (EDA), feature engineering, modeling, evaluation, and lightweight MLOps for deployment[cite: 4].

## Setup and Prerequisites

To run this project locally, you must first install Python and the required libraries.

1.  **Clone the Repository:**
    ```bash
    git clone <Your Repository URL>
    ```

2.  **Install Dependencies:**
    Install all necessary libraries using the `requirements.txt` file with the following command:
    ```bash
    pip install -r requirements.txt
    ```

## How to Run the Project

### **1. Train and Evaluate Models**

To train the models and view the evaluation results, execute the scripts located in the `src/` directory. [cite_start]These scripts handle data preparation, training of baselines [cite: 35][cite_start], content-based (CB) [cite: 41][cite_start], and collaborative filtering (CF) models [cite: 48][cite_start], and finally, their evaluation[cite: 60].

### **2. Run the Interactive Application**

After training the models and saving the necessary artifacts, you can run the interactive application. [cite_start]This app allows you to get movie recommendations with short explanations[cite: 65].

The main script for the application is located in the `app/` folder. Run it with the following command:

```bash
python app/run_app.py