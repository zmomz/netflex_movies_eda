# Netflix Movies Exploratory Data Analysis (EDA)

This project involves an exploratory data analysis (EDA) of Netflix movie data. The main objective is to understand various qualitative factors and their relationship with movie success, using IMDb ratings as the success metric.

## Objective

- Derive actionable insights about factors influencing the success of movies.
- Assess the qualitative aspects of Netflix movies that correlate with higher IMDb scores.

## Data Source

The dataset used for this analysis is available from Kaggle:

[Netflix TV Shows and Movies](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies)

## Libraries and Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Data Overview

| Attribute         | Description                          | Type       |
|-------------------|--------------------------------------|------------|
| release_year      | Year of movie release                | Numeric    |
| runtime           | Duration of the movie (minutes)      | Numeric    |
| seasons           | Number of seasons (for TV shows)     | Numeric    |
| imdb_score        | IMDb rating                          | Numeric    |
| imdb_votes        | Number of IMDb votes                 | Numeric    |
| tmdb_popularity   | Popularity score from TMDb           | Numeric    |
| tmdb_score        | TMDb rating                          | Numeric    |

## Key Findings

1. **Genre Dominance:**
   - Drama (30%) and Comedy (25%) genres dominate Netflix content.

2. **Vote Correlation:**
   - Movies with more IMDb votes typically have higher IMDb ratings.

3. **Runtime Popularity:**
   - Movies with an average runtime tend to be more popular.

4. **Reality Genre Ratings:**
   - Reality genre movies rarely score below 5.5 on IMDb.

5. **Genre Score Insights:**
   - Horror movies, on average, have the lowest IMDb rating (around 5.4).
   - History, Documentary, Reality, and War genres have the highest average IMDb scores, ranging between 6.6 and 6.9.

## Getting Started

1. Clone this repository.
   
```bash

git clone https://github.com/zmomz/netflex_movies_eda.git
```
   
3. Install required libraries:

```bash

cd netflex-movies-eda
pip install pandas matplotlib seaborn
```

3. Run the EDA notebook/script provided.
```bash

jupyter notebook netflex_movies.ipynb
```

## Contributions

Suggestions and contributions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) file for details.

