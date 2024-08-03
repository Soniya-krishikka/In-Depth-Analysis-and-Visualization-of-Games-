# In-Depth-Analysis-and-Visualization-of-Games-

This project involves analyzing a dataset of top games, focusing on various attributes such as genre, platform, release year, and user ratings. The aim is to uncover trends, distributions, and correlations within the dataset through data cleaning, visualization, and statistical analysis.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Visualizations](#analysis-and-visualizations)
  - [Summary Statistics](#summary-statistics)
  - [Missing Values](#missing-values)
  - [Data Types](#data-types)
  - [Visualizations](#visualizations)
- [Contributing](#contributing)

## Introduction

The goal of this project is to analyze a dataset containing information about top games across different genres, platforms, and release years, and to visualize key insights such as the distribution of user ratings, genre and platform distributions, trends over time, and correlations between different variables.

## Dataset

The dataset used for this analysis contains the following columns:

- **Game Name**: The name of the game.
- **Genre**: The genre of the game.
- **Platform**: The platform on which the game is available (e.g., PC, PlayStation, Xbox).
- **Release Year**: The year the game was released.
- **User Rating**: The user rating of the game.

## Installation

To get started with the project, you need to install the necessary libraries. You can do this by running:

```bash
pip install pandas matplotlib seaborn
```

## Usage

To run the analysis and generate the visualizations, simply execute the provided Python script. Ensure that the dataset file is located in the specified path or update the path accordingly in the script.

## Analysis and Visualizations

### Summary Statistics

The script calculates and displays summary statistics for the dataset, including count, unique values, frequency, mean, standard deviation, min, and max values for numerical columns.

### Missing Values

The script checks for and removes any rows with missing values to ensure clean data for analysis.

### Data Types

The script ensures that the 'Release Year' column is of integer type and displays the data types of all columns.

### Visualizations

The following visualizations are generated to explore the dataset:

1. **Distribution of User Ratings**:
    - Histogram showing the frequency distribution of user ratings.
  
2. **Genre Distribution**:
    - Count plot showing the distribution of games across different genres.
  
3. **Platform Distribution**:
    - Count plot showing the distribution of games across different platforms.
  
4. **Distribution of Release Years**:
    - Histogram showing the frequency distribution of game release years.
  
5. **User Rating vs Release Year**:
    - Scatter plot showing the relationship between user ratings and release years, with genres as hue.
  
6. **Genre Distribution (Pie Chart)**:
    - Pie chart showing the proportion of games in each genre.
  
7. **Platform Distribution (Pie Chart)**:
    - Pie chart showing the proportion of games on each platform.
  
8. **User Ratings by Genre**:
    - Box plot showing the distribution of user ratings for each genre.
  
9. **User Ratings by Platform**:
    - Box plot showing the distribution of user ratings for each platform.
  
10. **Average User Ratings by Genre**:
    - Bar plot showing the average user rating for each genre.
  
11. **Average User Ratings by Platform**:
    - Bar plot showing the average user rating for each platform.
  
12. **Correlation Heatmap**:
    - Heatmap showing the correlation between release year and user rating.
  
13. **User Ratings Over Time**:
    - Scatter plot showing user ratings over time, with genres as hue.
  
14. **Heatmap of User Ratings by Genre and Platform**:
    - Heatmap showing the average user ratings for each genre-platform pair.
  
15. **Distribution of Games by Release Year and Genre**:
    - Count plot showing the distribution of games by release year and genre.
  
16. **Trends in Number of Game Releases Per Year**:
    - Line plot showing the number of game releases per year.
  
17. **KDE Plot of User Ratings by Genre**:
    - Kernel Density Estimate plot showing the density of user ratings for each genre.
  
18. **Average User Ratings Over Time**:
    - Line plot showing the average user ratings over time.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.

