## Introduction
"Shark Tank India" is a popular reality show where entrepreneurs pitch their business ideas to a panel of investors. This recommendation system helps viewers discover episodes they might enjoy based on their viewing history and preferences.
## Dataset
The dataset used in this project includes:
- Episode details (title, description, air date)
- User ratings for each episode
## Methodology
1. **Data Preprocessing**: Clean and prepare the dataset for analysis.
2. **Matrix Factorization**: Apply SVD to decompose the user-item interaction matrix.
3. **Recommendation Generation**: Use the decomposed matrices to predict ratings for unseen episodes.
## Implementation
The implementation is done in Python using the following libraries:
- NumPy
- pandas
- scikit-learn
- Surprise (for SVD)
