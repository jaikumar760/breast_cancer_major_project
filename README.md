# Breast Cancer Major Project

This project is a web application built using Flask for predicting breast cancer outcomes based on user input and uploaded data. It includes user authentication, a symptom checker, and options for manual data entry or CSV file uploads.

## Requirements

- Python 3.6 or higher
- Flask
- Flask-SQLAlchemy
- Flask-Login
- Pandas
- Scikit-learn
- Werkzeug

## Installation

1. **Clone the repository:**

   git clone <repository-url>
   cd breast_cancer_major_project

2. **Create a virtual environment:**

   python -m venv venv

3. **Activate the virtual environment:**

   - On Windows:
     venv\Scripts\activate
   - On macOS/Linux:
     source venv/bin/activate

4. **Install the required packages:**

   pip install -r requirements.txt

   If `requirements.txt` is not available, you can manually install the required packages:

   pip install Flask Flask-SQLAlchemy Flask-Login pandas scikit-learn Werkzeug

## Running the Application

1. **Ensure the model file is in place:**

   Make sure the `breast_cancer_model.pkl` file is located in the `model` directory.

2. **Run the application:**

   python app.py

3. **Access the application:**

   Open your web browser and go to `http://localhost:8000`.

## Database Setup

The application uses SQLite for user management. The database file `users.db` will be created automatically when the application runs for the first time.

## Usage

- **Register:** Create a new user account.
- **Login:** Access the dashboard and other features after logging in.
- **Symptom Checker:** Evaluate symptoms and get risk assessments.
- **Manual Entry:** Input features manually for predictions.
- **Upload CSV:** Upload a CSV file containing features for batch predictions.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
