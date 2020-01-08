# Wine Recommendation System

#### Project Overview and Problem Statement(s):
Can we demystify wine reviews/ descriptions?

The first goal of this project was to use NLP topic models to demystify and uncover trends in wine reviews/descriptions. The second goal was to use the topic models to recommend similar (and cheaper) wines to consumers.

#### The Data and Models
The data: More than 100,000 wine reviews from sommeliers for Wine Enthusiast. Taken from Kaggle.

The models: For project goal #1, I used many different topic models to uncover underlying themes in the wine descriptions. The final model used was a Gensim LDA model. For project goal #2, I built a recommendation system based off of the Jensen-Shannon Distance between the topic distributions of the wines.

See the project presentation [here](https://github.com/atersakyan/Projects/blob/master/MetisProject4/Metis%20Project%204-%20NLP%20Wine%20Presentation.pdf).
