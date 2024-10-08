# 🎵 Music Recommender System

## Overview

The **Music Recommender System** is a Python-based application designed to provide personalized music recommendations based on user preferences. This project focuses on two major music categories: **Bollywood** and **Hollywood**. Using machine learning and NLP techniques, the system analyzes song features and user input to recommend songs that align with the user's taste.

This project leverages various Python libraries including **Streamlit** for the frontend, **Spotipy** for interacting with the Spotify API, and **scikit-learn** and **nltk** for machine learning and natural language processing.

## Features

- **Two Music Categories**: Users can choose between **Bollywood** and **Hollywood** songs for tailored recommendations.
- **User Interaction**: The recommender system captures user input about mood, favorite artists, or genres to provide dynamic recommendations.
- **Machine Learning Models**: Utilizes classification and recommendation algorithms from **scikit-learn**.
- **Spotify Integration**: Fetches real-time song metadata via the **Spotify API**.
- **Interactive Web Interface**: Built using **Streamlit** for a clean, user-friendly experience.

## Tech Stack

The application utilizes the following technologies:

- **Frontend**: Streamlit (for building the interactive interface)
- **Backend**: Python
- **APIs**: Spotify Web API (via Spotipy)
- **Machine Learning**: scikit-learn
- **Natural Language Processing**: nltk
- **Environment Management**: dotenv

## Installation

### Prerequisites

Make sure you have Python 3.x installed on your machine.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/music-recommender-system.git
cd music_recommender_system
```

### Step 2: Install Dependencies

Install the required libraries from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### Step 3: Set Up Spotify API Credentials

Create a `.env` file in the project directory with your **Spotify API** credentials:

```plaintext
CLIENT_ID=your-client-id
CLIENT_SECRET=your-client-secret
```

Get these credentials by creating a new application in the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).

### Step 4: Run the Application

To start the Streamlit app, run:

```bash
streamlit run app.py
```

Open the app in your browser using the URL provided in the terminal.

## Usage

### Bollywood Music Recommendations

Simply select "Bollywood" in the app, and input any specific song preferences. The system will provide you with a list of Bollywood songs that match your input.

### Hollywood Music Recommendations

Choose "Hollywood" in the app and enter your preferences. The system will generate recommendations based on your choices.

## Project Structure

```bash
├── streamlit_app.py         # Main file to run the Streamlit app         
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
├── Model Training.ipynb     # Jupyter NB for training the Model on dataset
├── .env                     # Spotify API credentials (not included in repo)
└── data/                    # (Optional) Data used for model training
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contact

For any inquiries or feedback, please contact:

- **Author**: Jishnu Duhan
- **Email**: duhanjishnu@gmail.com
- **LinkedIn**: [Jishnu Duhan](https://www.linkedin.com/in/jishnu-duhan-b23ee006/)
