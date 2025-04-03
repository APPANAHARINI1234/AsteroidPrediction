# Asteroid Prediction

## Overview

The **Asteroid Prediction** project aims to analyze and predict asteroid trajectories using scientific data and analytical models. This project provides insights into asteroid movements and potential Earth impact probabilities.

## Features

- Predict asteroid trajectories based on historical data.
- Analyze potential asteroid collisions with Earth.
- Provide visualization and reports of asteroid paths.
- Fetch real-time asteroid data from reliable sources.

## Technologies Used

- **Python** (for data processing and analysis)
- **Machine Learning Models** (for prediction and classification)
- **Data Visualization Tools** (for graphical representation of results)

## Approach & Algorithms

Our approach integrates various computational techniques to ensure accurate asteroid predictions:

- **Orbit Determination Algorithms**: Utilized to compute an asteroid's trajectory based on its past observations.
- **Keplerian Motion Equations**: Used to estimate asteroid motion under gravitational forces.
- **Machine Learning Models**:
  - **XGBoost**: Used for high-accuracy regression and classification of asteroid impact probabilities.
  - **Ridge Regression**: Applied to improve trajectory prediction by reducing overfitting.
  - **Random Forest & Decision Trees**: Used for impact probability analysis based on historical data.
- **Clustering Techniques**: Grouping asteroids based on size, velocity, and trajectory similarities.

We collect and preprocess data from astronomical datasets, train predictive models, and validate results using known asteroid orbits.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/APPANAHARINI1234/AsteroidPediction.git
   cd AsteroidPrediction
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up NASA API Key (if applicable):**

   - Sign up at [NASA API Portal](https://api.nasa.gov/)
   - Get an API Key and update the `.env` file.

## Usage

- Run the program to analyze and predict asteroid movements.

## Contributors

- **Harini** - Project Lead
- **Eda Durga Sri Lahari** 
- **Tanu Sri Burra** 
- **Ch Harshitha** 

## Future Enhancements

- Implement advanced deep learning models for improved accuracy.
- Develop an interactive dashboard for asteroid tracking.
- Enhance visualization and reporting features.


