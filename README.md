
# Flight Price Prediction Model

Leverage the power of Machine Learning to predict flight prices using a Random Forest model.

## Description

This project is a web-based application that predicts flight prices based on various flight-related parameters. The user-friendly interface built with Flask allows users to input flight details and get the predicted price. Engaging animations and a professional design enhance the user experience.

## Key Features

- **Machine Learning Model:** Utilizes a Random Forest model for predicting flight prices.
- **User Interface:** Built with Flask, featuring forms for user inputs and engaging animations.
- **Deployment:** Deployed using Gunicorn for serving the Flask application.

## Technologies Used

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, Bootstrap
- **Machine Learning:** Random Forest
- **Deployment:** Gunicorn, Render

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd flight-price-prediction
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add the dataset:**
   Ensure the `data/train.csv` and `data/val.csv` files are in the `data` directory.

5. **Run the application:**
   ```bash
   python app.py
   ```

## Usage

1. Navigate to `http://127.0.0.1:5000/home` in your web browser.
2. Enter the flight details in the form provided.
3. Click "Predict Now" to see the predicted flight price with a plane take-off animation.

## Credits

- Akshit Anand - Developer

## License

This project is licensed under the MIT License.
