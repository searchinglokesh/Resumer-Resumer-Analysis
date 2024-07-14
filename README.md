# AI Resume Analyzer

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the AI Resume Analyzer! This application allows users to upload their resumes in PDF format and receive detailed feedback, recommendations, and tips to improve their resumes. The system also offers suggestions for relevant courses and skills based on the content of the uploaded resume. This project is developed by Kolla Raghavendra Lokesh.

## Features
- **Resume Parsing:** Extracts information from PDF resumes using `pyresparser`.
- **PDF Display:** Shows the uploaded resume in the browser using an iframe.
- **Skills Recommendations:** Suggests skills based on the current skills in the resume.
- **Courses Recommendations:** Recommends courses from various fields like Data Science, Web Development, etc.
- **Resume Tips:** Provides tips to improve the resume content.
- **Admin Dashboard:** Admin can view and download user data, and visualize user statistics using pie charts.

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/AI-Resume-Analyzer.git
    cd AI-Resume-Analyzer
    ```

2. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download NLTK Stopwords:**
    ```python
    import nltk
    nltk.download('stopwords')
    ```

4. **Set up the database:**
    - Ensure you have MySQL installed.
    - Create a database named `cv`.

## Usage
1. **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2. **Upload Resume:**
    - As a user, upload your resume in PDF format.
    - View resume analysis, skill recommendations, and relevant courses.

3. **Admin Access:**
    - Login with the credentials (`loki` / `loki@123`).
    - View user data and download reports.
    - Visualize user statistics with pie charts.

## Technologies Used
- **Python:** The main programming language used.
- **Streamlit:** For building the web application.
- **PyResparser:** For parsing resume data.
- **PDFMiner:** For reading PDF files.
- **Pandas:** For data manipulation.
- **Plotly:** For data visualization.
- **MySQL:** For the database.
- **Pafy:** For handling YouTube video links.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License.