# Movie Recommendation System | PCA & Content-Based Filtering

**Technologies:** R, PCA, Euclidean Distance, Content-Based Filtering, Data Analysis

## Business Question
**How can streaming platforms recommend relevant movies to users based on similarities in movie characteristics, improving content discovery and potentially increasing user engagement?**

With thousands of movies available on streaming platforms, users can struggle to find content that matches their interests. A content-based recommendation system can help solve this problem by identifying movies with similar characteristics, reducing the effort required to discover relevant content.

## Project Overview
Developed a content-based movie recommendation system using R to identify the 10 most similar movies to a selected film, *Cool Hand Luke (1967)*.

The project utilized Principal Component Analysis (PCA) to reduce over 1,000 movie characteristics into 447 principal components while preserving at least 90% of the dataset's variance. Euclidean distance was then used to measure similarity between movies, producing a ranked list of recommendations.

## Methodology
1. **Data Preparation:** Imported movie metadata and Movie Genome datasets, organizing movie characteristics and identifiers for analysis.
2. **Dimensionality Reduction:** Applied PCA to reduce the number of features while preserving 90% of the original variance.
3. **Similarity Analysis:** Calculated Euclidean distances between the selected movie and all other movies using their principal components.
4. **Recommendation Generation:** Ranked movies by similarity and identified the 10 closest matches.
5. **Data Integration:** Merged recommendation results with movie titles to produce an interpretable output.

## Technical Skills Demonstrated
- **R Programming:** Data manipulation, functions, loops, and analytical workflows
- **Principal Component Analysis (PCA):** Dimensionality reduction and feature transformation
- **Statistical Analysis:** Variance analysis, standardization, and cumulative explained variance
- **Similarity Modeling:** Euclidean distance calculations and similarity-based ranking
- **Recommendation Systems:** Content-based filtering and movie-to-movie recommendations
- **Data Preparation:** Data importing, filtering, merging, and sorting
- **Data Interpretation:** Translating numerical similarity scores into understandable movie recommendations
- **Reproducible Analysis:** Documenting analytical methods and results using R Markdown

## Business Value
This project demonstrates how organizations can leverage high-dimensional data to develop recommendation systems that support content discovery and personalization.

For streaming services, similar techniques could help improve the user experience, increase content engagement, and support customer retention. These outcomes represent potential business applications rather than measured results from this project.

## Future Improvements
Integrate user ratings and collaborative filtering to predict individual movie preferences, evaluate recommendation accuracy, and develop a more personalized recommendation engine.
