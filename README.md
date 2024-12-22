# san_jiao_xing

三角形 or san jiao xing meams triangle. San jiao xing is a productivity tool designed to help you manage and balance your time between work, school, and personal life. This application tracks how you spend your time, generates insights, and helps you make data-driven decisions for a better work-life balance.

Features
	•	Log Time: Add entries with categories (e.g., Work, School, Personal), subcategories, and hours spent.
	•	View Logs: Retrieve and filter logs by date, category, or subcategory.
	•	Analytics: Gain insights into how your time is distributed.
	•	Cross-Platform: Built with NiceGUI for a modern and user-friendly frontend.
	•	Lightweight Backend: Powered by SQLite and FastAPI for seamless and fast operations.

Technologies Used

Frontend:
	•	NiceGUI: For creating an interactive and visually appealing user interface.

Backend:
	•	SQLite: Lightweight database for storing time logs.
	•	FastAPI: High-performance API framework for backend services.

Testing:
	•	pytest: For automated testing of database and application logic.

CI/CD:
	•	GitHub Actions: Automates testing and deployment pipelines.

Setup Instructions

1. Clone the Repository

git clone 
<github link>

2. Install Dependencies

Ensure you have Python 3.8+ installed. Then run:

pip install -r requirements.txt

3. Initialize the Database

Run the script to create the SQLite database:

python initialize_db.py

4. Start the Application

Launch the app locally:

python main.py

The app will be accessible at http://localhost:8080.

Running Tests

To ensure everything works as expected, run the test suite:

pytest

CI/CD Pipeline

The project includes a CI/CD pipeline using GitHub Actions:
	1.	Build: Installs dependencies and ensures the code builds successfully.
	2.	Test: Runs the test suite to validate functionality.
	3.	Deploy: Automates deployment to the server or container.

To set up CI/CD:
	•	Push your code to GitHub.
	•	GitHub Actions automatically triggers on new commits to the main branch.

Contributing

Contributions are welcome! Follow these steps:
	1.	Fork the repository.
	2.	Create a new branch:

git checkout -b feature-name


	3.	Commit changes:

git commit -m "Add feature"


	4.	Push the branch and open a pull request.

