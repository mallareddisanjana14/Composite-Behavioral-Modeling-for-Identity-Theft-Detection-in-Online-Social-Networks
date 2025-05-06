# Composite-Behavioral-Modeling-for-Identity-Theft-Detection-in-Online-Social-Networks
"Composite Behavioral Modeling for Identity Theft Detection in OSNs" uses SVM, Random Forest, and Decision Tree in an ensemble to detect fraud. Admin module manages data; User module visualizes behavior. Built with Python, Flask, SQLite, it achieves 99.67% accuracy. Future plans: deep learning, live deployment.
Project Description
The project develops a machine learning-based system to detect identity theft in online social networks (OSNs). It uses an ensemble of Support Vector Machine (SVM), Random Forest, and Decision Tree classifiers to achieve high detection accuracy and adaptability to evolving cyber threats. The system is divided into two modules: the Admin module handles dataset management, preprocessing, model training, and performance evaluation with visual analytics, while the User module enables real-time behavioral visualization and sends theft detection alerts. Built to process large-scale OSN data efficiently, it reduces false positives and enhances user trust. Experimental results show strong performance, with Random Forest achieving 99.67% accuracy.

Key Features
Ensemble Learning: Combines SVM, Random Forest, and Decision Tree classifiers for improved accuracy and robustness.
Admin Module: Manages dataset upload, preprocessing, model execution, and performance visualization (accuracy, precision, recall).
User Module: Provides real-time behavioral analysis, visualization graphs, and instant theft detection alerts.
Scalability: Efficiently processes large-scale OSN datasets with optimized algorithms.
Adaptability: Updates models to counter emerging threats, minimizing false positives.
User-Friendly Interface: Intuitive dashboards for admins and users to monitor and analyze activities.
Technologies Used
Programming Language: Python
Web Framework: Flask
Database: SQLite
Machine Learning Libraries: Scikit-learn (for SVM, Random Forest, Decision Tree), Pandas, NumPy
Visualization: Matplotlib
Development Tools: PyCharm, Python IDLE
Operating System: Windows 11
Database Connectivity: Python Database Connectivity (PDBC)
File and Folder Structure
Based on the project report, the system likely follows a typical Python web application structure with Flask. Below is a hypothesized structure, as the report does not explicitly list it:

text

Copy
project_root/
│
├── static/                     # CSS, JavaScript, and image files for frontend
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/                  # HTML templates for Flask
│   ├── home.html             # Homepage
│   ├── admin_login.html      # Admin login page
│   ├── user_login.html       # User login page
│   ├── admin_home.html       # Admin dashboard
│   ├── user_home.html        # User dashboard
│   ├── upload_dataset.html   # Dataset upload page
│   ├── view_dataset.html     # Dataset preview page
│   ├── behaviour_graph.html  # User behavior visualization
│   └── theft_detect.html     # Theft detection results
│
├── datasets/                   # Directory for storing OSN datasets
│   └── sample_dataset.csv
│
├── models/                     # Trained ML models
│   ├── svm_model.pkl
│   ├── rf_model.pkl
│   └── dt_model.pkl
│
├── app.py                      # Main Flask application file
├── config.py                   # Configuration settings (e.g., database path)
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
└── database.db                 # SQLite database file
static/: Stores frontend assets like CSS for styling and JavaScript for interactivity.
templates/: Contains HTML files for rendering web pages (e.g., admin and user interfaces).
datasets/: Stores input datasets for training and testing.
models/: Saves trained machine learning models in pickle format.
app.py: Core application script handling routing, logic, and ML integration.
database.db: SQLite database for storing user data and metrics.
Setup
To set up and run the project locally, follow these steps based on the report’s details:

Install Python:
Download and install Python 3.7.0 from python.org.
Verify installation: python --version.
Set Up Virtual Environment:
Create a virtual environment: python -m venv venv.
Activate it:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate
Install Dependencies:
Create a requirements.txt with:
text

Copy
flask
scikit-learn
pandas
numpy
matplotlib
sqlite3
Install: pip install -r requirements.txt.
Configure the Project:
Place the project files in a directory (e.g., project_root/).
Ensure the SQLite database (database.db) is initialized or created by running the application.
Run the Application:
Navigate to the project directory: cd project_root.
Run the Flask app: python app.py.
Access the application at http://localhost:5000 in a web browser.
Hardware Requirements:
Processor: Pentium Dual Core
RAM: 1 GB
Hard Disk: 120 GB
Monitor: 15" LED
Input Devices: Keyboard, Mouse
Prepare Dataset:
Place OSN datasets in the datasets/ folder.
Ensure datasets are in CSV format for preprocessing.
Test the System:
Access the admin interface to upload datasets and train models.
Use the user interface to register, log in, and monitor behavior or detect theft.
