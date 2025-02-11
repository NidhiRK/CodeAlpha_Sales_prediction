Sales Prediction using Machine Learning

📌 Project Overview

This project focuses on predicting product sales based on advertising expenditures on TV, Radio, and Newspaper. Using various machine learning models, we analyze how different advertisement channels impact sales and determine the most accurate prediction method.

📊 Dataset

The dataset contains the following columns:

TV - Advertising budget spent on TV (in $1000s)

Radio - Advertising budget spent on Radio (in $1000s)

NewsPaper - Advertising budget spent on Newspapers (in $1000s)

Sales - Sales generated (in units)

🔧 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📈 Models Used

We evaluated multiple models:

Linear Regression (Baseline model) ✅

Random Forest Regressor 🌲

Gradient Boosting Regressor 🚀

Polynomial Regression (Best performer) 🎯

Installation & Usage

1️⃣ Clone the Repository                                                                                                                                                                  
git clone https://github.com/NidhiRK/CodeAlpha_Sales_prediction.git
cd sales-prediction

2️⃣ Install Dependencies                                                                                                                                                                   
pip install -r requirements.txt

3️⃣ Run the Model                                                                                                                                                                          
python sales_prediction.py

🎯 Results & Conclusion

       Model          and    R² Score        
                                                          
Linear Regression         0.899         
Random Forest             0.981          
Gradient Boosting         0.983          
Polynomial Regression     0.987           


Polynomial Regression performed the best, capturing non-linear relationships effectively. However, Gradient Boosting and Random Forest also showed strong results.

Project Structure                                                                                                                                                                         
├── data                                                                                                                                                                                   
│   ├── sales_data.csv                                                                                                                                                                     
├── src                                                                                                                                                                                    
│   ├── sales_prediction.py                                                                                                                                                                
├── README.md                                                                                                                                                                              
├── requirements.txt                                                                                                                                                                       
                                  
📌 Future Enhancements

Add more features (e.g., seasonality, customer demographics)

Hyperparameter tuning for better performance

Deploy as a web app using Flask or FastAPI

📢 Connect with Me
🔗 LinkedIn:(https://www.linkedin.com/in/nidhi-kushwaha-1b64b62a1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
📧 Email: nidhirk1706@gmail.com
