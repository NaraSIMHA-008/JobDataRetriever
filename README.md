# Job Details Retrieval

This Flask-based web service utilizes Flask API and Google GenAI (Gemini) API key for content generation. It employs
FAISS for similarity matching and Sentence Transformers for semantic representation. Returns job details in JSON
format based on input text similarity to job descriptions.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Codename-shaShank/Job_recommender.git
   cd Job_recommender

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt

## Usage

1. **Run the `resume_model.ipynb` notebook:**
Make sure to run the resume_model.ipynb notebook completely to generate the necessary pickle files (`pickle_file`).

2. **Run the Flask app:**
   ```bash
   python app.py

## Files

• `app.py`: The main Streamlit application file.

• `resume_model.ipynb`: Jupyter Notebook used to create the dictionaries and similarity matrix for movie recommendations.

• `requirements.txt`: Contains all the dependencies required to run the application.




Replace `"YOUR_GEN_AI_API_KEY"` with your actual Google GenAI API key in both `app.py` and `resume_model.ipynb`. Make sure the `jobs.csv` file is placed correctly and has the necessary columns.
