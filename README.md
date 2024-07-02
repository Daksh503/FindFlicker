## Overview

The Netflix Recommender System aims to provide personalized movie recommendations to users based on their viewing history and preferences. This system leverages collaborative filtering and machine learning techniques to generate recommendations.

## Features

- **User Authentication**: Users can sign up and log in to access personalized recommendations.
- **Movie Recommendations**: Get movie recommendations based on your watch history and ratings.
- **Search Functionality**: Search for movies and view details about them.
- **Responsive Design**: The application is designed to work seamlessly across different devices.

## Technologies Used

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL
- **Machine Learning**: Collaborative Filtering

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Daksh503/FindFlicker
    cd netflix-recommender-system
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**:
    - Ensure PostgreSQL is installed and running.
    - Create a new database for the project.
    - Configure the database URI in the environment variables.

5. **Run the application**:
    ```bash
    python app.py
    ```

6. **Access the application**:
    Open your web browser and navigate to `http://127.0.0.1:5000`.

## Usage

1. **Sign Up/Login**: Create an account or log in with your existing credentials.
2. **Get Recommendations**: View your personalized movie recommendations on the dashboard.
3. **Search Movies**: Use the search bar to find movies and view their details.
4. **Rate Movies**: Provide ratings for movies you've watched to improve future recommendations.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.