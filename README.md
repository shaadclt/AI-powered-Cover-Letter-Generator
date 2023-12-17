# AI-powered Cover Letter Generator

## Overview

The AI-powered Cover Letter Generator is a Streamlit web application that leverages the GooglePalm language model to generate cover letters based on user input. Users can input details such as job description, company name, job position, experience, and the maximum number of characters for the cover letter.

## Features

- Dynamic UI with Streamlit
- Integration with GooglePalm language model
- Customizable cover letter generation
- User-friendly interface for inputting details

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/shaadclt/AI-powered-Cover-Letter-Generator.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variable:

   Update the values in the '.env' file, 'GOOGLE_API_KEY' required for the GooglePalm language model.

4. Run the application:

   ```bash
   streamlit run app.py
   ```

5. Access the application in your web browser at [http://localhost:8501](http://localhost:8501).
