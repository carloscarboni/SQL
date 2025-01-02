# Spotify and Youtube Data Analysis

- **Objective:**
  - Analyze Spotify track data to derive key insights about artist performance, track popularity, and album characteristics. Present findings through queries ranging from exploratory data analysis (EDA) to advanced metrics computation.

- **Description:**
  - The SQL script explores a dataset named `spotify` using various query levels:
    - **EDA:** Basic exploration of the dataset, including counts, unique values, and data cleaning.
    - **Easy Level:** Aggregates metrics such as top-streamed tracks, album-artist pairings, and licensed track statistics.
    - **Medium Level:** Analyzes track characteristics like danceability, energy, views, and popularity by platform.
    - **Advanced Level:** Utilizes window functions and CTEs to calculate rankings, cumulative sums, and complex ratios (e.g., energy-to-liveness).
  - These analyses enable detailed insights into track performance and user engagement across Spotify and YouTube.

- **Skills:**
  - SQL for data cleaning, transformation, and analysis.
  - Advanced SQL techniques: window functions, CTEs, and subqueries.
  - Trend analysis for features like energy, danceability, and liveness.
  - Cross-platform comparisons for popularity metrics.

- **Technology:**
  - SQL.
  - Relational database for data storage and querying.

- **Results:**
  - **Data Insights:**
    - Total tracks, albums, and distinct artists identified through EDA.
    - Tracks with over 1 billion streams identified, along with their contributing artists.
    - Album-specific trends in danceability and energy.
  - **Platform Comparisons:**
    - Tracks streamed more on Spotify than YouTube highlighted.
  - **Performance Metrics:**
    - Top 3 most-viewed tracks per artist calculated using window functions.
    - Energy-to-liveness ratios computed to identify dynamic track properties.
