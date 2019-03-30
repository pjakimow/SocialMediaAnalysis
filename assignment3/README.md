# User communities in Twitter controversies

### Tasks

1. Using appropriate python module acquire Twitter dataset pertaining to a controversy of choice, identified through a hashtag (eg. covfefe, gamergate, alllivesmatter etc).

2. Use the previously obtained data to construct a network of Twitter users participating in the discussion surrounding the controversy. Use user Mentions and/or Follows as the basis for creating edges within the network.

3. Perform a community detection on obtained network(s). Ensure the communities do *not* overlap.

4. Visualise the network(s) and communities obtained in the previous step. 

5. Prepare an analysis of the community structure(s) using previously obtained visualisation. Extract relevant user-features (eg. usage of other topical hashtags, geolocation, average sentiment etc) and use them to train a simple classification model, that maps these features to the cluster space (user features -> cluster_id). Review the accuracy metrics. If you've created two network structures as a part of your work on task 2, review the differences between classification results on each of them.

### Readings
[Pandas tutorial](https://github.com/jorisvandenbossche/pandas-tutorial)

[NetworkX](https://networkx.github.io/documentation/stable/)

[Sklearn supervised learning](http://scikit-learn.org/stable/supervised_learning.html)
