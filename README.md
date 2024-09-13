# Nav-Aarambh - A Post Partum Depression Predictor

## Overview

The Postpartum Depression Analysis System provides a comprehensive tool for assessing and analyzing postpartum depression. The system is divided into two main parts:

1. **Postpartum Depression Test**: Developed using HTML, CSS, JavaScript, PHP, and Firebase.
2. **Data Analysis**: Implemented with Python-based Jupyter Notebook.

## User Interface

### Postpartum Depression Test

The test is designed to evaluate the user's mental health through a structured questionnaire. It is divided into three pages:

1. **Page 1**: Answer ten multiple-choice questions, each with four options. Responses are weighted from 0 to 3. The weights are used to calculate the total score.
2. **Page 2**: Collects demographic information such as age range, gender, household income, country of residence, and mental health-related questions.
3. **Page 3**: Displays the results based on the calculated criteria. Users can receive their results via email. If the total score is between 14 and 30, the system will suggest nearby psychological centers and hospitals.

### Data Analysis

The data analysis section uses a dataset retrieved from Kaggle and a dataset of 1503 records collected through a Google Form. The dataset includes the following attributes:

- **Attributes**: Timestamp, Age, Feeling sad or Tearful, Irritable towards baby & partner, Trouble sleeping at night, Problems concentrating or making decisions, Overeating or loss of appetite, Feeling anxious, Feeling of guilt, Problems of bonding with baby, Suicide attempt.
- **Target Attribute**: "Feeling Anxious" is used as the predictor for postpartum depression.


## Getting Started

### Prerequisites

- Python 3.x
- Streamlit library
- Jupyter Notebook
- HTML/CSS/JavaScript/PHP knowledge

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repository/Postpartum-Depression-Analysis-System.git
   cd Postpartum-Depression-Analysis-System
   pip install -r requirements.txt
   streamlit run app.py
