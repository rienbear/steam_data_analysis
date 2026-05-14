# Steam Games Data Analysis

This project provides a comprehensive analysis of Steam store data using Python. The analysis covers data cleaning, feature engineering, statistical exploration, and data visualization to uncover trends in pricing, sales, and hardware requirements.

## 📋 Features

The analysis follows a structured data science workflow:

1.  **Data Preprocessing**: 
    * Handling missing values and data inconsistencies.
    * **Price Normalization**: Converting price strings (e.g., "$19.99" or "Free") into numeric formats for calculation.
2.  **Categorical Insights**: 
    * Grouping games by category.
    * Calculating the average discount (sale percentage) across different genres.
3.  **Hardware Trend Analysis**: 
    * Utilizing Regular Expressions (Regex) to scan system requirements.
    * Determining the percentage of games that specifically require a **64-bit processor**.
4.  **Data Visualization**: 
    * Creating visual reports using Seaborn and Matplotlib.
    * Generating bar charts with the `rocket` palette to visualize discount distributions.

## 📊 Key Findings

* **Hardware Requirements**: Approximately **58.54%** of the games in the dataset now require a 64-bit processor.
* **Sales Trends**: The analysis identifies which game categories are most likely to have higher average sale percentages.

## 🛠️ Technology Stack

* **Language**: Python 3.x
* **Libraries**:
    * `pandas`: Data manipulation and analysis.
    * `seaborn`: Statistical data visualization.
    * `matplotlib`: Plotting and graph generation.
    * `regex`: Pattern matching for system requirements.
## 📊 Dataset
The dataset used in this analysis is too large to be hosted on GitHub. 
You can download the original data from Kaggle:
[Steam Games Complete Dataset](https://www.kaggle.com/datasets/trolukovich/steam-games-complete-dataset)

To run the notebook, download the `steam_games.csv` and place it in the project root directory.

## 🚀 Getting Started


### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install pandas seaborn matplotlib regex
