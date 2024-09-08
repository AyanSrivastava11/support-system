# Decision Support System for Disease Prediction

This project is a decision support system that uses classification algorithms to predict the likelihood of a user suffering from any of the 32 diseases associated with the symptoms they input. It is designed to aid in early detection of potential health concerns and improve overall healthcare outcomes.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)

## Overview
The system helps users by:
- Taking input of symptoms.
- Using classification algorithms to predict possible diseases.
- Offering suggestions for early detection and cures for the identified disease.
- Redirecting the user to resources related to specific diseases for further guidance.

This system aims to improve the healthcare experience by providing quick, reliable predictions, thus allowing users to take timely action on potential health concerns.

## Features
- Predicts the likelihood of 32 different diseases based on symptoms.
- Provides early detection to improve healthcare outcomes.
- Uses data from the Mayo Clinic for accurate predictions and disease management.
- Redirects users to disease-specific resources.
- Easy to use interface for entering symptoms and receiving predictions.

## Technologies Used
- **Machine Learning**: Classification algorithms (e.g., Decision Trees, Random Forest, etc.)
- **Backend**: Python (Flask/Django)
- **Database**: MongoDB/MySQL for storing disease and symptom information
- **Deployment**: Python (Streamlit)

## Data Source
The system utilizes publicly available data from the Mayo Clinic to predict the likelihood of a disease and provide cures and redirection for specific diseases.

## Installation

### Prerequisites
- Python 3.x
- Pip
- Virtual Environment (Optional)

### Steps

1. Clone the repository:
    ```bash
    git clone <repository-link>
    ```

2. Navigate to the project directory:
    ```bash
    cd decision-support-system
    ```

3. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: `env\Scripts\activate`
    ```

4. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Run the application:
    ```bash
    python app.py
    ```

## Usage
1. Run the application.
2. Input your symptoms in the user interface.
3. The system will predict the likelihood of any of the 32 diseases associated with your symptoms.
4. It will suggest possible actions and provide links to resources for further information.

## Deployment
The system is deployed and available at the following link:

[Deployment Link](#) (Replace with actual link)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
