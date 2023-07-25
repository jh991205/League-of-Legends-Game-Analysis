# League of Legends Game Winning Condition Analysis

This project is an analysis of League of Legends game data to identify the factors that contribute to a team's victory. The analysis is performed using Python and Jupyter Notebook. Logistic Regression and K-Nearest Neighbors (KNN) models are utilized to predict the winning condition based on various in-game metrics.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

## Introduction

League of Legends is a popular multiplayer online battle arena (MOBA) game developed by Riot Games. In this game, two teams of players compete against each other with the goal of destroying the enemy's Nexus, their main base structure. Throughout the match, players collect gold, acquire items, and gain experience to grow stronger.

The objective of this analysis is to investigate the factors that contribute to a team's victory. By understanding which in-game metrics are more likely to lead to a win, players can strategize and improve their chances of winning.

## Data

The analysis is based on data collected from various League of Legends matches. The dataset includes a wide range of in-game metrics such as:

- Gold earned by each player
- Number of kills, deaths, and assists per player
- Minions and jungle monsters killed
- Damage dealt to champions and structures
- Vision score
- Game duration
- And more...

## Methodology

The project follows these main steps:

1. Data Collection: Obtain match data from League of Legends API or other reliable sources.

2. Data Preprocessing: Clean the data, handle missing values, and perform feature engineering if necessary.

3. Exploratory Data Analysis (EDA): Explore the dataset to gain insights into the distribution of variables and their relationships.

4. Feature Selection: Identify relevant features that may influence the game's outcome.

5. Model Training: Utilize Logistic Regression and K-Nearest Neighbors (KNN) algorithms to build predictive models.

6. Model Evaluation: Evaluate the models' performance using appropriate metrics like accuracy, precision, recall, and F1-score.

7. Interpretation: Analyze the results and draw conclusions on which factors contribute most to winning conditions.

## Installation

To run the Jupyter Notebook and replicate the analysis, follow these steps:

1. Install Python (if not already installed) from the official Python website (https://www.python.org/downloads/).

2. Install Jupyter Notebook using pip:
   ```bash
   pip install jupyter
   ```
3. Clone this repository
4. Install the required Python packages:
   ```bash
   pip install pandas matplotlib scikit-learn
   ```
5. Launch Jupyter Notebook:
   ```
   Jupyter Notebook
   ```

## Usage

1. Open the `league_of_legends_analysis.ipynb` notebook in Jupyter.

2. Follow the step-by-step instructions in the notebook to execute the code and run the analysis.

## Results

The results of the analysis will be presented in the Jupyter Notebook. This includes visualizations of important features, performance metrics of the models, and insights into which factors contribute most to winning conditions.

## License
MIT License


