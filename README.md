
# Movie Recommendation System using k-NN Classifier

## Overview

This Movie Recommendation System is a Python-based application that utilizes the k-Nearest Neighbors (k-NN) algorithm to provide movie recommendations to users based on their viewing history and preferences. It analyzes user behavior and compares it with other users' behavior to suggest movies they might like.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Algorithm](#algorithm)

## Features

- Movie rating and review system for capturing user preferences.
- Recommendation generation based on k-NN algorithm.
  
## Requirements

To run this Movie Recommendation System, you'll need the following dependencies:

- Python 3.x
- NumPy
- pandas
- scikit-learn
- json
- matplotlib
- nltk
- operator
- seaborn

You can install the required Python packages using `pip`:

```bash
pip install numpy pandas scikit-learn json matplotlib nltk operator seaborn
```

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yogee2904/Recommended-System.git
```

2. Change to the project directory:

```bash
cd Recommended-System
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

4. Activate the virtual environment (Linux/macOS):

```bash
source venv/bin/activate
```

   On Windows, use:

```bash
venv\Scripts\activate
```

5. Install the required packages as mentioned in the [Requirements](#requirements) section.

6. Initialize the database:

```bash
python init_db.py
```

## Usage

1. Start the application:

```bash
python app.py
```

2. Register or log in as a user.

3. Rate and review movies you've watched.

4. Get movie recommendations based on your preferences by selecting the "Get Recommendations" option.

## Dataset

This Movie Recommendation System uses a sample dataset of movie ratings and reviews. You can replace this dataset with your own by modifying the `data/movies.csv` file.

The dataset should have the following columns:

- `user_id`: Unique identifier for users.
- `movie_id`: Unique identifier for movies.
- `rating`: User rating for the movie (e.g., on a scale of 1 to 5).
- `review`: User review text (optional).

## Algorithm

The recommendation system is based on the k-Nearest Neighbors (k-NN) algorithm. It identifies users with similar movie preferences to recommend movies that those users have liked but the current user has not yet seen.

---

Feel free to customize this README to match your specific project's details and requirements. Include additional sections or details as needed to make it informative and user-friendly.
