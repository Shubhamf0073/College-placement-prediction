# College-placement-prediction
 Student Placement Prediction  This project is a Django-based web application that predicts whether a student will get placed based on various input features like age, gender, stream, internship experience, CGPA, hostel stay, and number of backlogs.

Features

	•	Web Interface: User-friendly interface to input student details and predict placement outcomes.
	•	Machine Learning: Logistic Regression model implemented to make predictions.
	•	Django Framework: Utilizes Django for backend and template rendering.

Project Structure
Placement/
│
├── Placement/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── placements/
│   ├── __init__.py
│   ├── main.py
│   ├── urls.py
│   ├── templates/
│       ├── index.html
│       ├── predict.html
│
├── manage.py
└── collegePlace.csv

Setup Instructions

1.	Clone the repository:
 git clone https://github.com/Shubhamf0073/College-placement-prediction.git
cd student-placement-prediction

2.	Install dependencies:
   pip install -r requirements.txt
  	
	3.	Run the Django server:
    python manage.py runserver
   	
 4.	Open your web browser and visit http://127.0.0.1:8000/ to use the application.

Usage

	•	Home Page: Enter the input details and click on “Predict” to see the placement result.
	•	Prediction: The model predicts whether the student is likely to be placed or not based on the input features.
 
License

This project is licensed under the MIT License. See the LICENSE file for details.

Contributing

Feel free to fork this project, submit pull requests, or suggest enhancements by opening an issue.
