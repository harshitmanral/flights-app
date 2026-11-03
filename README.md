✈️ Flight Search & Analytics App

A data-driven Flight Search & Analytics Web Application developed using Python, Streamlit, Object-Oriented Programming (OOP), and MySQL.

The application provides an interactive platform to search for flight information and analyze flight data through visual representations using bar charts.

📌 Project Overview

The Flight Search & Analytics App is designed to make flight data accessible and easier to understand through a simple and interactive dashboard.

The application consists of two major sections:

🔍 1. Check Flights

This section allows users to check flight information stored in the MySQL database.

Features:

Retrieve flight details from the MySQL database.
Execute SQL queries to fetch relevant flight records.
Display flight search results through an interactive Streamlit interface.
Present the retrieved information in an organized format.
📊 2. Analytics

The Analytics section provides a visual representation of flight data to help users understand different flight-related insights.

Features:

Displays flight analytics using bar charts.
Provides visual comparisons of flight-related information.
Converts database records into meaningful graphical insights.
Makes flight data easier to interpret and analyze.
🛠️ Technologies Used
Technology	Purpose
Python	Core application development
Streamlit	Interactive web application and UI
MySQL	Database management
SQL	Database queries and data retrieval
OOP	Code organization and reusability
Pandas	Data manipulation (if implemented)
Matplotlib / Plotly	Data visualization (depending on implementation)
Python-dotenv	Environment variable management
📂 Project Structure
text
Flight-Search-Analytics/
│
├── app.py
│   └── Main Streamlit application
│       ├── Application interface
│       ├── Check Flights section
│       ├── Analytics section
│       └── Bar chart visualizations
│
├── db_helper.py
│   └── Database helper module
│       ├── MySQL database connection
│       ├── SQL queries
│       └── Data retrieval functions
│
├── venv/
│   └── Python virtual environment
│
├── .env
│   └── Environment variables and database credentials
│
├── .gitignore
│   └── Files and folders excluded from Git
│
└── requirements.txt
    └── Project dependencies

📄 File Descriptions
1. app.py – Main Application
Acts as the entry point of the project.
Contains the Streamlit application code.
Handles the user interface and application workflow.
Provides navigation between Check Flights and Analytics.
Displays flight search results.
Generates bar charts for flight data analytics.
2. db_helper.py – Database Helper
Manages the connection between Python and MySQL.
Contains reusable database connection functions.
Executes SQL queries to retrieve flight data.
Separates database operations from the Streamlit interface.
Helps maintain clean and modular code.
3. venv/ – Virtual Environment
Contains an isolated Python environment.
Keeps project dependencies separate from global Python packages.
Helps maintain a consistent development environment.
4. .env – Environment Configuration
Stores sensitive database configuration details.
Keeps database credentials separate from application code.
Helps protect confidential information.

Example:

env
HOST=localhost
USER=your_mysql_username
PASSWORD=your_mysql_password
DATABASE=your_database_name

5. .gitignore
Specifies files and directories Git should ignore.
Prevents sensitive information and unnecessary files from being pushed to GitHub.

Example:

gitignore
venv/
.env
__pycache__/
*.pyc

6. requirements.txt
Contains the Python libraries required by the project.
Makes it easier for other developers to install project dependencies.
⚙️ Installation & Setup

Follow these steps to run the project on your local machine.

Step 1: Clone the Repository
bash
git clone https://github.com/harshitmanral/Flight-Search-Analytics.git

bash
cd Flight-Search-Analytics

Step 2: Create a Virtual Environment
bash
python -m venv venv


Activate the environment:

Windows:

bash
venv\Scripts\activate


Mac/Linux:

bash
source venv/bin/activate

Step 3: Install Dependencies
bash
pip install -r requirements.txt

Step 4: Configure MySQL Database
Install and start MySQL Server.
Create the required database.
Create or import the flight data tables expected by the application.
Configure your database credentials in the .env file.
Step 5: Run the Application
bash
streamlit run app.py


The application will launch in your default web browser.

💡 Key Concepts Implemented
Object-Oriented Programming: Writing modular, reusable, and maintainable Python code.
Database Connectivity: Connecting Python with MySQL.
SQL Querying: Retrieving and processing flight records from the database.
Streamlit Development: Building an interactive web application.
Data Visualization: Representing flight data using bar charts.
Modular Programming: Separating UI logic from database operations.
Environment Management: Managing dependencies and database credentials securely.
🚀 Future Enhancements
Advanced flight search filters.
Airline-wise flight comparisons.
Source and destination-based filtering.
Flight price analysis.
More interactive charts and visualizations.
Real-time flight data integration.
Flight booking functionality.
👨‍💻 Author

Harshit Manral

GitHub: @harshitmanral
LinkedIn: Connect with me
⭐ Support

If you find this project useful or interesting, please consider giving it a ⭐ on GitHub.

Developed with ❤️ using Python, Streamlit, OOP & MySQL.