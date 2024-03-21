# IMDb Dataset Analysis

This Python script analyzes the IMDb dataset containing information about the top 1000 movies and TV shows. The script performs various data exploration and visualization tasks using libraries such as NumPy, pandas, seaborn, and matplotlib.

## Dataset Overview

The IMDb dataset contains information about the top 1000 movies and TV shows, including features like title, genre, IMDb rating, metascore, number of votes, and runtime.

## Code Overview

1. **Loading and Preprocessing the Data:**
   - The dataset is loaded using pandas from a CSV file.
   - The first few rows of the dataset are displayed to understand its structure.
   - Information about the dataset such as data types and non-null counts is printed.
   - Missing values are checked and dropped from the dataset.

2. **Correlation Matrix:**
   - A correlation matrix is computed for selected numerical features (`IMDB_Rating`, `Meta_score`, `No_of_Votes`, `Runtime`).
   - The correlation matrix is visualized using a heatmap to explore the relationships between features.

3. **Top Movies Analysis:**
   - The dataframe is sorted by IMDb rating in descending order.
   - The top 20 movies by IMDb rating are displayed, including features like title, genre, IMDb rating, and gross revenue.

4. **Top Genres Visualization:**
   - The top genres among the top 100 movies with the highest IMDb ratings are identified.
   - A bar plot is created to visualize the distribution of the top genres.

5. **Viewer Votes vs IMDb Ratings:**
   - A scatter plot is generated to explore the relationship between the number of votes and IMDb ratings.

6. **Average IMDb Ratings by Director and Actor:**
   - The average IMDb rating for the top 10 directors and actors is computed and displayed.

## Requirements

To run the code, you need Python installed on your system along with the following libraries:

- NumPy
- pandas
- seaborn
- matplotlib

## Usage

1. Download the IMDb dataset from the provided source.
2. Adjust the file path in the script to point to the downloaded dataset.
3. Run the script to perform data analysis and visualization on the IMDb dataset.
