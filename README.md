# Item-based-colaborative-filtering
An implementation of item-based collaborative filtering for recommendation systems.

## 

Recommendation systems may have content based filtering where we make use of attributes or they may have collaborative filtering. Collaborative Filtering is a technique to predict a user’s taste and find the items that a user might prefer on the basis of information collected from various other users having similar tastes or preferences. It takes into consideration the basic fact that if person X and person Y have a similar reaction for some items then they might have the same opinion for other items too. Collaborative filtering may be memory based or model based.

- Memory-based methods use user rating historical data to compute the similarity between users or items.
- Model-based CF uses machine learning algorithms to predict users’ rating of unrated items.

Memory based Collaborative filtering may further be divided into:

- **User Based:** Here, we look for the users who have rated various items in the same way and then find the rating of the missing item with the help of these users.
- **Item Based:** Here, we explore the relationship between the pair of items (the user who bought Y, also bought Z). We find the missing rating with the help of the ratings given to the other items by the user.
