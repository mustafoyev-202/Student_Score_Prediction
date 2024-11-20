# Student Score Prediction 📚

## Overview
This project is a machine learning application that predicts student math scores based on various demographic and academic factors. The system uses Flask to serve a web interface where users can input student information and receive predicted math scores.

![Proof](https://github.com/mustafoyev-202/Student_Score_Prediction/blob/main/proof.png)


## Features
- 🎯 Predicts student math scores with high accuracy
- 🌐 Web-based interface for easy interaction
- 📊 Takes into account multiple factors:
  - Gender
  - Race/Ethnicity
  - Parental Education Level
  - Lunch Type
  - Test Preparation Course
  - Reading Score
  - Writing Score

## Tech Stack
- Python
- Flask
- Scikit-learn
- Pandas
- HTML/CSS
- Machine Learning Algorithms

## Project Structure
```
Student_Score_Prediction/
├── app.py                      # Flask application main file
├── src/
│   └── pipeline/
│       └── predict_pipeline.py # Prediction pipeline
├── templates/
│   ├── index.html             # Landing page
│   └── home.html              # Prediction form page
└── README.md
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Student_Score_Prediction.git
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the Flask server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

3. Fill in the student information form and submit to get the predicted math score.

## API Endpoints

- `GET /` - Landing page
- `GET /predictdata` - Display prediction form
- `POST /predictdata` - Submit data and get prediction

## Input Features

| Feature | Description | Type |
|---------|------------|------|
| Gender | Student's gender | Categorical |
| Race/Ethnicity | Student's race/ethnicity | Categorical |
| Parental Education | Parent's education level | Categorical |
| Lunch | Type of lunch | Categorical |
| Test Preparation | Whether completed prep course | Categorical |
| Reading Score | Score in reading (0-100) | Numeric |
| Writing Score | Score in writing (0-100) | Numeric |

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Your Name - [@mustafoyev-202](https://github.com/mustafoyev-202)

Project Link: https://github.com/mustafoyev-202/Student_Score_Prediction

