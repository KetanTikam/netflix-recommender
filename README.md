\# Netflix Recommendation System



\## Problem Statement



Build a personalized recommendation system using the Netflix Prize Dataset.



\## Dataset



\- 50,000 ratings

\- 24,430 users

\- 504 movies



\## Models Implemented



\### Item-Based Collaborative Filtering (KNN)



Uses cosine similarity between movies to generate recommendations.



\### SVD Matrix Factorization



Learns latent user preferences using matrix factorization.



\## Results



| Model | RMSE |

|--------|--------|

| KNN | 1.1857 |

| SVD | 1.0409 |



\## Best Model



SVD achieved the lowest RMSE and produced better recommendations.



\## Technologies



\- Python

\- Pandas

\- Matplotlib

\- Scikit-Surprise



\## Repository Structure



data/

notebooks/

report/

presentation/



