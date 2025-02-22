# 🏡 Airbnb Superhost Prediction  

## 📌 Overview  
This project aims to predict whether an Airbnb host will become a **Superhost** using a neural network. The model is built using **Python**, leveraging **pandas**, **NumPy**, and **Keras** to process and analyze Airbnb listing data.  

## 📊 Dataset  
The dataset contains various Airbnb host and listing attributes, including:  
- **Host-related features** (e.g., response rate, number of reviews, years hosting)  
- **Listing details** (e.g., price, availability, number of listings)  
- **Guest satisfaction indicators** (e.g., average rating, review count)  
- **Target Variable**: Binary classification (Superhost = 1, Not Superhost = 0)  

## 🛠️ Tools & Technologies  
- **Python**  
- **pandas** for data preprocessing  
- **NumPy** for numerical computations  
- **Keras** for building and training the neural network  

## 🔬 Methodology  
1. **Data Cleaning & Preprocessing**  
   - Handle missing values and outliers  
   - Convert categorical variables into numerical representations  
   - Normalize numerical features  

2. **Feature Engineering**  
   - Selected key features affecting Superhost status  
   - Created new features based on listing and host behavior  

3. **Neural Network Architecture**  
   - Input layer: Preprocessed features  
   - Hidden layers: Fully connected layers with ReLU activation  
   - Output layer: Sigmoid activation for binary classification  
   - Optimizer: Adam  
   - Loss function: Binary cross-entropy  

4. **Model Training & Evaluation**  
   - Split dataset into **training (80%)** and **testing (20%)**  
   - Used **accuracy, precision, recall, and F1-score** to evaluate performance  

## 📈 Results & Insights  
- The model achieved **83% accuracy** on the test set  
- Important features influencing Superhost status include **review scores, response rate, and host experience**  
- Further improvements can be made with **hyperparameter tuning and feature selection**  

## 🔮 Future Work  
- Experiment with **other ML models** like Random Forest or XGBoost  
- Incorporate **text-based features** from guest reviews  
- Fine-tune **neural network hyperparameters**  

## 📜 License  
This project is open-source and available under the [MIT License](LICENSE).  

## 🙌 Acknowledgments  
- Airbnb for the dataset  
- TensorFlow/Keras community for deep learning resources  
