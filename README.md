# Movie Recommendation System

This project is built with Streamlit and Jupyter Notebook. It utilizes `pickle` for saving and loading data.

![Screenshot 2024-10-08 041746](https://github.com/user-attachments/assets/ba28b2f3-5e68-48a0-a768-cb373f876ed9)

## Prerequisites

Make sure you have the following installed on your machine to run this project locally:

- Python 3.7 or higher
- pip (Python package installer)
- Download the datasets from https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbE5tZFV2S1l1T1dlSXVwTmYtZHRjMEs2WExaQXxBQ3Jtc0tuWjBDelF3WGwxWGVaQTQwaWw1NElxemgyMXhVRlhKVWg5d1dUcDZNejFncl92QmhxTEE5NXQxQ3VXQkhISGVPbjdMU3U2T1p6cHNGeGxsLU0tTm1ELXgtUmlLb25FZmRRYmo4NzhBRUhzQlZGX1Blbw&q=https%3A%2F%2Fwww.kaggle.com%2Ftmdb%2Ftmdb-movie-metadata%3Fselect%3Dtmdb_5000_movies.csv&v=1xtrIEwY_zY

## Getting Started

Follow these instructions to set up and run the project locally.

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/manmeetnagii/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2. Create a Virtual Environment (Optional)

It's a good practice to create a virtual environment for your project:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

Install the required packages using requirements.txt:

```bash
pip install -r requirements.txt
```

### 4. Prepare Data Files

If you haven't already, create the necessary pickle files from your Jupyter Notebook:

- In the given Jupyter Notebook, run the following code to save your data:

```bash
import pickle

pickle.dump(new, open('movie_list.pkl', 'wb'))
pickle.dump(similarity, open('similarity.pkl', 'wb'))
```

- Once created, copy the movie_list.pkl and similarity.pkl files from your Jupyter project directory to the app directory of this repository.

### 5. Run the Streamlit App

You can now run your Streamlit app with the following command:

```bash
streamlit run app.py
```
