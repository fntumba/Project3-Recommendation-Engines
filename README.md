# Project3-Recommendation-Engines

### Project motivation
In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.


The project will be divided into the following tasks

### I. Exploratory Data Analysis

Before making recommendations of any kind, we explored the data we are working with for the project. Dive in to see what we can find. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. We use this space to explore, before we dive into the details of our recommendation system in the later sections.

### II. Rank Based Recommendations

To get started in building recommendations, we first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, we might come up with some extremely creative ways to develop a content based recommendation system. We are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

### V. Matrix Factorization

Finally, We complete a machine learning approach to building recommendations. Using the user-item interactions, we build out a matrix decomposition. Using our decomposition, we get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). We finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.
