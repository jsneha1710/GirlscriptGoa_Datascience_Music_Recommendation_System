Girlscript Goa-Data Science Track
Music Recommendation system

This is a Music Recommendation system that recommends music to the user based on
the popularity of the song as well as based on the user's history.
The datasets used are-
The Million song dataset -http://millionsongdataset.com/ consisting of
1)tr_file containing user_id, song_id and listen time-
2)mt_file containing song_id, title, release_by and artist_name.
 These 2 files are merged together to obtain a common dataset of songs listened
 by a large number of users indicated by their user_id.

 1) The first part of the project is the popularity based recommendation system
 that recommends the top scoring songs grouped by their listening count using the
 popularity_recommender function.
 The result is a list of the most popular songs along with their listen_count
 and ranks.

 2)The second part of the project is a content/collaborative filtering model
 which recommends music based on the user's history to produce a personalised
 list of songs using the item_similarity recommender function.
 This function also uses the concept of cooccurrence matrix to implement the
 filtering mechanism.
