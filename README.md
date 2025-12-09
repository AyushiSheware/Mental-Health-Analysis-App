Table of Contents:-

Overview,
Features,
Technologies Used,
Project Flow,
Installation,
Usage,
Future Improvements,
Screenshots,
Contributing,
License.

Overview:-

The Mental Health Analysis Web Application helps users evaluate their mental health through a questionnaire and provides severity predictions using machine learning models. 
It offers a clean and simple interface for users and includes an admin panel for managing user submissions.

Features:-

User Authentication – Separate login for users and admin.
Mental Health Check – Interactive form-based data collection.
Severity Prediction – Uses Machine Learning models (Logistic Regression & Gaussian Naive Bayes) to predict severity levels: Minimal, Mild, Moderate, or Severe.
Data Visualization (Planned) – Future integration with Power BI dashboards for analysis.
Clean UI Design – Simple interface with blue gradient themes and centralized layouts.
Technologies Used
Backend: Python, Flask
Frontend: HTML, CSS, Bootstrap
Database: SQLite/MySQL (choose your implementation)
Machine Learning Models: Logistic Regression, Gaussian Naive Bayes, Confusion matrix & Classification Metrics
Data Visualization: Planned Power BI integration

Project Flow:-

Home Page
Register/Login Page: Users can register and log in.
User Dashboard
Option to take a Mental Health Check 📝
View predicted severity results
View all user submissions
Manage user data (trends and statistics to be visualized later)

ML Model Integration:-

Questionnaire responses are processed by Logistic Regression or Gaussian Naive Bayes
Severity level is predicted automatically

Data Storage:-

User responses and predictions are stored for future analysis

Installation:-

Clone the repository:-

git clone https://github.com/AyushiSheware/Mental-Health-Analysis-App.git
cd Mental-Health-Analysis-App


Create a virtual environment:-

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows


Install dependencies:-

pip install -r requirements.txt


Run the Flask application:-

python app.py


Open your browser and navigate to http://127.0.0.1:5000

Usage:-

Users can register and log in.
Complete the mental health questionnaire.
View predicted severity levels immediately.
Admin can log in to view all user submissions.

Future Improvements:-

Connect Power BI dashboards for real-time data visualization.
Integrate additional ML models for improved prediction accuracy.
Add email notifications for user results.
Enhance UI/UX with dark mode and accessibility features.

Screenshots:- 

[Home Page]<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d2840f3b-cb5d-4054-9754-54bfad772488" />
[Home Page]<img width="1920" height="1080" alt="Screenshot (262)" src="https://github.com/user-attachments/assets/93d7f46b-0b18-4f7a-814b-77a2ec75c2c8" />
[Register Page]<img width="1920" height="1080" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/c3611f36-a90c-4a43-b69c-94ddecd360cf" />
[Login Page]<img width="1920" height="1080" alt="Screenshot (264)" src="https://github.com/user-attachments/assets/f5cf3b71-e48f-437f-a90f-cb52cdb18381" />
[User Dashboard]<img width="1920" height="1080" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/94f73def-5207-47fe-b8cc-b37973e0ad5d" />
[PHQ-9 Quessionaire]<img width="1920" height="1080" alt="Screenshot (267)" src="https://github.com/user-attachments/assets/c386220f-d525-4d0f-811a-f54677952fb4" />
[GAD-7 Quessionaire]<img width="1920" height="1080" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/aaa57eff-731e-43c1-a70a-1f4285cbd420" />
[Result Page]<img width="1920" height="1080" alt="Screenshot (270)" src="https://github.com/user-attachments/assets/3f6d51a5-3664-469f-9ea0-860d99bbf782" />
[History Page]<img width="1920" height="1080" alt="Screenshot (271)" src="https://github.com/user-attachments/assets/718196d6-2c67-44eb-90ea-c7dbf154babd" />

Contributing:-

Contributions are welcome! Open an issue or submit a pull request for improvements, bug fixes, or new features.

Note:-

This project is currently not licensed. All code and content are for personal/educational use only.
