# Netflix Content Analysis

## Project Overview
This project focuses on analyzing Netflix's vast content library. Using the **Netflix Titles** dataset, the goal is to uncover insights about content trends, ratings, genres, and the relationships between various factors such as release year, duration, and content type. The analysis provides a deeper understanding of Netflix's content strategy and audience preferences.

## Dataset
The dataset includes information about TV shows and movies available on Netflix, with columns such as:
- `show_id`: Unique identifier for each show
- `type`: Type of content (e.g., Movie, TV Show)
- `title`: Name of the show or movie
- `director`: Director(s) of the show/movie
- `cast`: List of actors involved
- `country`: Country where the content is available
- `date_added`: Date the content was added to Netflix
- `release_year`: Year the content was released
- `rating`: Rating of the content (e.g., PG, TV-MA)
- `duration`: Duration of the movie or TV show (in minutes or seasons)
- `listed_in`: Categories of content (e.g., Drama, Action)
- `description`: Short summary of the content

## Features
- **Content Trends**: Analysis of the release year of content to observe trends over time.
- **Genre Distribution**: Insights into the most popular genres on Netflix and their distribution.
- **Duration & Rating Analysis**: Explore the relationship between content length (duration in minutes or number of seasons) and its rating.
- **Top Content**: Identification of the highest-rated and most frequent genres and shows.

## Technologies Used
- **Python Libraries**:
  - Pandas, NumPy (for data processing)
  - Matplotlib, Seaborn (for data visualization)
  - Scikit-learn (for machine learning models, if applicable)

## Setup Instructions
1. Clone the repository:
bash
   git clone https://github.com/farzadjenab/Netflix-Content-Analysis.git
   
2. Install the required packages:

   pip install -r requirements.txt
   
3. Run the Jupyter notebook:

   jupyter notebook netflix_analysis.ipynb
   
Contributing
Feel free to open issues and submit pull requests. Contributions are welcome!

License
This project is licensed under the MIT License 

   
