# Composite Behavioral Modeling for Identity Theft Detection in Online Social Networks

A machine learning system to detect identity theft in online social networks (OSNs) using an ensemble of SVM, Random Forest, and Decision Tree classifiers. It features admin and user modules for dataset management, real-time behavioral analysis, and theft detection.

## Project Description
This project develops a robust system to combat identity theft in OSNs. It integrates Support Vector Machine (SVM), Random Forest, and Decision Tree classifiers in an ensemble framework for high accuracy. The **Admin module** manages datasets, preprocessing, model training, and performance evaluation. The **User module** offers real-time behavioral visualization and theft alerts. Built with Python, Flask, and SQLite, it processes large-scale data efficiently, achieving 99.67% accuracy with Random Forest.

## Key Features
- **Ensemble Learning**: Combines SVM, Random Forest, and Decision Tree for enhanced detection.
- **Admin Module**: Handles dataset upload, preprocessing, and model evaluation with visual analytics.
- **User Module**: Provides real-time behavior graphs and theft detection alerts.
- **Scalability**: Optimized for large OSN datasets.
- **Adaptability**: Evolves with new threats, reducing false positives.
- **User-Friendly**: Intuitive interfaces for admins and users.

## Technologies Used
- **Programming Language**: Python
- **Web Framework**: Flask
- **Database**: SQLite
- **ML Libraries**: Scikit-learn, Pandas, NumPy
- **Visualization**: Matplotlib
- **Tools**: PyCharm, Python IDLE
- **OS**: Windows 11
- **Connectivity**: PDBC

## file and folder structure 
Flask app: static/, templates/, datasets/, models/, app.py, config.py, SQLite DB

# Project Structure
📦 project_root  
├── 📂 static                 # Frontend assets (CSS, JS, images)  
├── 📂 templates             # HTML templates  
│   ├── home.html            # Homepage  
│   ├── admin_login.html     # Admin login  
│   └── user_login.html      # User login  
├── 📂 datasets              # OSN datasets  
├── 📂 models                # Trained ML models  
├── 📄 app.py                # Main Flask app  
├── 📄 config.py             # Configuration  
├── 📄 database.db           # SQLite database  
└── 📄 README.md             # Project docs  

-**static/**: Stores frontend assets like CSS for styling and JavaScript for interactivity.

-**templates/**: Contains HTML files for rendering web pages (e.g., admin and user interfaces).

-**datasets/**: Stores input datasets for training and testing.

-**models/**: Saves trained machine learning models in pickle format.

-**app.py**: Core application script handling routing, logic, and ML integration.

-**database.db**: SQLite database for storing user data and metrics.

## Setup
To set up and run the project locally, follow these steps:

1. **Install Python**:
   - Download Python 3.7.0 from [python.org](https://www.python.org/).
   - Verify: 
     ```bash
     python --version

2. **Set Up Virtual Environment**:

    -Create and activate a virtual environment:
    python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

3. **Install dependencies**:

-Create a requirements.txt with:

flask

scikit-learn

pandas

numpy

matplotlib

sqlite3

-Install:
pip install -r requirements.txt

4. **configure the project**:

Place project files in a directory (e.g., project_root/).

Ensure database.db is initialized by running the app.

5.**Run the Application**:

-Navigate to the project directory:
cd project_root

-Run the Flask app:
python app.py

-Access at http://localhost:5000

## Contribute 

If you would like to contribute, please submit a pull request. Any contributions and feedback are welcomed.
