# Movie Recommendation System

![image](https://github.com/abhijeetgupta23/Movie_Recommendation_System/assets/16919762/5ec1df1b-e7d6-4043-9cf7-4163584efa04)

This project makes use of Movie Datasets to demonstrate how major organizations like Netflix, Amazon, Google, Meta etc. build Recommender System using techniques like Collaborative Filtering, Content Based Filtering, and Hybrid of these to enhance Customer Experience in terms of Personalization, Content Discovery, Retention and Engagement to boost Revenue Generation. 

## Collaborative Filtering

Code found at - https://github.com/abhijeetgupta23/Movie_Recommendation_System/blob/main/Collaborative_Filtering.ipynb 

Steps:

1) For a user, list of all their highest rated movies are found
2) Assuming user has rated all movies they watched, Cosine similarity of these movies are calculated w.r.t movie not rated/watched by user
3) All consine similarities are collated, and top k unwatched movies with highest cosine similarities are returned

<h3> Example : </h3>

User's highest rated movies

Since you like :

- Twelve Monkeys (a.k.a. 12 Monkeys) (1995)
- Birdcage, The (1996)
- Star Trek: First Contact (1996)

You might also like :

- Toy Story (1995)
- Seven (a.k.a. Se7en) (1995)
- Usual Suspects, The (1995)
- Braveheart (1995)
- Star Wars: Episode IV - A New Hope (1977)
- Pulp Fiction (1994)
- Shawshank Redemption, The (1994)
- Star Trek: Generations (1994)
- Fugitive, The (1993)
- Jurassic Park (1993)
- Terminator 2: Judgment Day (1991)
- Batman (1989)
- Silence of the Lambs, The (1991)
- Trainspotting (1996)
- Terminator, The (1984)
- Star Trek VI: The Undiscovered Country (1991)
- Star Trek II: The Wrath of Khan (1982)
- Star Trek III: The Search for Spock (1984)
- Star Trek IV: The Voyage Home (1986)
- Mars Attacks! (1996)
