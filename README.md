# recommendation

new users or items can be described by their characteristics (content) and so relevant suggestions can be done for these new entities. 

new user collabrative not work because not have previous  history to  give recommendation so use content based recommendation.


collaborative:rely on user-item interactions

Content :User-user,Item-item interactions  

User-user:

1.identify users with the most similar “interactions profile” (nearest neighbours) in order to suggest items that are the most popular among these neighbours (and that are “new” to our user)

2.“user-centred” as it represent users based on their interactions with items and evaluate distances between users

3.k-nearest-neighbours to our user and then suggest the most popular items

4.we consider that two users are similar if they have interacted with a lot of common items

Item-item:

1.item-item method is to find items similar to the ones the user already “positively” interacted with

2.Two items are considered to be similar if most of the users that have interacted with both of them did it in a similar way.

3.“item-centred” as it represent items based on interactions users had with them and evaluate distances between those items.

4.recommendation for a given user consider the item this user liked the most and represent it

user-user method is based on the search of similar users in terms of interactions with items.

item-item method is based on the search of similar items in terms of user-item interactions.


Evaluation methods for recommender systems in two sets: 

1.evaluation based on well defined metrics   
predicts rating then mean square error (MSE),predicts numeric values binarize these values with a classical thresholding approach(“classification way”).

2.evaluation mainly based on human judgment and satisfaction estimation.
