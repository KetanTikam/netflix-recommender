\# Netflix Recommendation System
## Project Summary

This project develops a personalized movie recommendation system using the Netflix Prize Dataset. Two recommendation approaches—Item-Based Collaborative Filtering and SVD Matrix Factorization—were implemented and evaluated using RMSE. Experimental results showed that SVD achieved superior performance and generated more accurate personalized recommendations.


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



