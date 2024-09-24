
# Flight Price Prediction Model

Leverage the power of Machine Learning to predict flight prices using a Random Forest model.

## Description

This project is a web-based application designed to predict flight prices based on various flight-related parameters. With a user-friendly interface built using Flask, users can input flight details and receive accurate predictions. The interface is enhanced with engaging animations and a professional design for an improved user experience.

## Key Features

- **Machine Learning Model:** Utilizes a Random Forest model to predict flight prices.
- **User Interface:** Developed using Flask, featuring intuitive forms for user inputs and engaging animations.
- **Deployment:** The application is deployed using Gunicorn, hosted on Render for a seamless experience.

## Technologies Used

- **Backend:** Python, Flask
- **Machine Learning:** Random Forest
- **Deployment:** Gunicorn, Render

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akanand03/Flight-price-prediction-.git
   cd Flight-price-prediction-
   ```

2. **Create and activate a virtual environment:**
   - On Linux/Mac:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
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
3. Click "Predict Now" to see the predicted flight price.

## Credits

- Akshit Anand - Developer

## License

This project is licensed under the MIT License.
