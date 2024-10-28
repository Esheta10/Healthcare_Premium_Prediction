## Healthcare_Premium_Prediction
### A machine learning application built with Streamlit that predicts health insurance costs based on user inputs like age, income, genetics, and lifestyle.
![image](https://github.com/user-attachments/assets/5550af05-0183-4cc0-9d19-2ee18fe676c8)


### Features
- Predicts health insurance costs based on user input.
- Factors in age, genetics, employment, lifestyle, and medical history.
- User-friendly interface with dropdowns for easy data input.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the Streamlit app:
   ```bash
   streamlit run main.py
   ```
2. Open `localhost:8501` in your browser to access the app.
### Project Structure
- `main.py`: Contains the Streamlit app code.
- `model.joblib`: Trained machine learning model for prediction.
- `requirements.txt`: Lists necessary dependencies.
  
### Model Details
- Utilizes a trained machine learning model to predict insurance costs.
- Features include age, dependents, income, gender, BMI, smoking status, etc.

### Example

Input Example:
- Age: 23
- Income: 1 lakh
- Smoking Status: Regular
- Output: Predicted Health Insurance Cost: 4996

### License
This project is licensed under the MIT License.
