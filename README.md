1.) what is recommended system ? 
- it is model hepls us to find similar product that we like or we want from the database.

Types of Recommended System - 1. Content Based - recommend based on similarity  content (on the basic of tags)
or product 
                              2. collaborative filterin base - Recommend on basic of User intrest or Behaviour eg- (user1 and user2 are similar the we recommend same content to that both user) eg-facebook feed or insta feed according to oue friend
                              
                              3. hybrid - it is mixed of both approch.
----------------------------------------------------------------------------------------------------------------------------------------------------------

!! we are using content based recommended system technique  for this project which recommend similarity of content .


------------------------------------------------------------------------project Flow----------------------------------------------------------------------
1. Doing pre processing on Data
- performed Eda on columns and reformatted.
- created new column tags contain tags of all column that are important 



2. Bulding Model 
- applying steaming technique for consider same words of diffrent pronounce as(love,loved,loving) into - love

- after steming techn ique doing vectorization - using bag of words technique taking top 5000 words and doing vectorization and and not consider or 
remove stop words of english (like - and,or,not,whent,not)

- doing vectorization - using bag of words technique for convert text into vector
 not to consiter stop words - are, and, not, to, form.

- we calculate angle between vectors - cosine distance ,angle is small between two wector then similarity is high 
we find similarity of all movie with each movie

- created recommend function which show top 5 similarity score of movie according to index and fetch top 5 movie from index 




3. Convert Model Into Interactive Website
4. Deploy Website
















