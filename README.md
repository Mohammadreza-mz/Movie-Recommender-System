# Movie-Recommender-System
Suggesting movies to users based on three methods:
- Content-based filtering
- Collaborative filtering
- Ensemble model

## Content-based filtering:
This method only uses the similarity between movies and the feedback from people's previous behavior to suggest movies to new members. For this purpose, the features of each film, such as title and genre, are used.

## Collaborative filtering:
This method utilizes the similarities between people's tastes. This model is unaware of the actual content, which some people have reacted similarly. 

## Ensemble model:
By combining collaborative and content-based filtering, we achieve a model that is aware of both the context of the movies and the similarities among people's votes.

## Dataset:
9000 IMDB movies rated by 700 people. In total, 100,000 rates.