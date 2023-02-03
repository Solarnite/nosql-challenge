# nosql-challenge
 
# Background

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Initial Steps
establishments.json file was provided and imported into MongoDB. Pymongo was used to confirm database and collection were imported correctly to local system. Insertion of one establishment Penang Flavours and removal of establishments in Dover was updated into the database. Updated document data types for latitude and longitude from string to double. There were questinos to be answered for the analysis portion.

# Questions 

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
