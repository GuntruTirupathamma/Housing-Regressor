# Housing-Regressor

🏠 Regression Model Prediction Web App
This web application allows users to input housing features and predict house prices using a selected regression model.

📸 App Interface
Users can input:

Average Area Income

Average Area House Age

Average Area Number of Rooms

Average Area Number of Bedrooms

Area Population

They can also choose a regression model (e.g., Linear Regression) from a dropdown and hit "Predict" to see the results.

🚀 Features
Interactive web form for data entry

Dropdown model selection

Price prediction using selected regression model

Option to view model evaluation metrics

🛠️ Tech Stack
Frontend: HTML/CSS (rendered by Streamlit or Flask templates)

Backend: Python (Flask or Streamlit)

ML Models: Linear Regression, (optionally others like Ridge, Lasso, SVR, etc.)

Libraries:

scikit-learn

pandas

numpy

streamlit or flask (depending on framework used)

matplotlib (optional, for evaluation results)

🧪 How to Run the Project
📦 Step 1: Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/house-price-prediction-app.git
cd house-price-prediction-app
🐍 Step 2: Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate     # On Windows
# OR
source venv/bin/activate  # On Linux/Mac
📥 Step 3: Install requirements
bash
Copy
Edit
pip install -r requirements.txt
▶️ Step 4: Run the app
If you're using Streamlit:

bash
Copy
Edit
streamlit run app.py
If you're using Flask:

bash
Copy
Edit
python app.py
📁 Project Structure (Example)
csharp
Copy
Edit
house-price-prediction-app/
│
├── app.py                      # Main application file
├── models/
│   └── trained_model.pkl       # Trained ML model(s)
├── templates/                  # HTML templates (if Flask)
│   └── index.html
├── static/                     # CSS and JS files
├── requirements.txt
└── README.md


📊 Example Models Supported
Linear Regression

Ridge Regression

Lasso Regression

Support Vector Regression


<img width="1722" height="1002" alt="image" src="https://github.com/user-attachments/assets/a176d26f-28b1-4951-b491-844bdab60b48" />





