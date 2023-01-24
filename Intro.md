## Types of recommender systems

### 1. Collaborative filtering

Collaborative filtering leverages the power of community to provide recommendations.

It can be classified into two types:

  #### - User based filtering
 The main idea behind user-based filtering is that if we are able to find users that have
bought and liked similar items in the past, they are more likely to buy similar items in the
future too.
Therefore, these models recommend items to a user that similar users have also
liked.

  #### - Item-based filtering
 If a group of people have rated two items similarly, then the two items must be similar.
Therefore, if a person likes one particular item, they're likely to be interested in the other
item too.


The biggest problem collaborative filters have is the **Cold start problem**. See collaborative filters need past activity data. This might be a problem with new applications seeing as they probably dont have enough user data to use for collaborative filtering.


### 2. Content-based systems
  Unlike collaborative filters, content-based systems do not require data relating to past
activity. Instead, they provide recommendations based on a user profile and metadata it
has on particular items.

  Since content-based systems don't leverage the power of the community, content-based systems usually provide recommendations that are obvious.
  
