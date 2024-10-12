# Text (Lyrics) Analysis with Python

## Overview

This data science project is focused on analyzing song lyrics using Python. It leverages various libraries for data manipulation, visualization, and natural language processing to extract insights about the sentiment of lyrics over time.

## Features

- **Data Loading**: Reads lyrics data from a CSV file and prepares it for analysis.
- **Sentiment Analysis**: Utilizes the NLTK library's SentimentIntensityAnalyzer to compute sentiment scores for lyrics.
- **Data Visualization**: Plots sentiment trends over time using Matplotlib and Seaborn to visualize changes in sentiment across albums.
- **Keyword Analysis**: Analyzes the frequency and sentiment associated with specific keywords like "night" and "day".

## Installation

To set up the project and run the Jupyter Notebook, ensure you have Python installed on your machine. Then, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install Jupyter Notebook and the required packages:

   ```bash
   pip install jupyter pandas seaborn matplotlib nltk
   ```

3. Open the `analyze-lyrics-notebook.ipynb` file in the Jupyter interface and run the cells to perform the analysis.

## Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook analyze-lyrics-notebook.ipynb
   ```

2. Run the cells in the notebook to load the data, perform sentiment analysis, and visualize the results.

3. Review the outputs to understand the sentiment trends and keyword analysis.

## File Descriptions

- **analyze-lyrics-notebook.ipynb**: The main Jupyter Notebook containing the analysis code, visualizations, and insights derived from the lyrics data.
- **lyrics_all.txt**: A text file containing the lyrics data in CSV format, which is used for analysis.

## Dependencies

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations in Python.
- **Seaborn**: For statistical data visualization based on Matplotlib.
- **NLTK**: For natural language processing tasks, including sentiment analysis.
- **Jupyter**: For running the notebook interface.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.
