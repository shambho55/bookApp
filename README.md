# bookApp
# Using pandas to read csv of books, users and ratings
# Checking for most loved books by merging ratings with books 
# create a column for average ratings and number of ratings in our dataframe by finding their mean and grouping by title , rounding rating to 2 place of decimals
# finding first 50 by sorting based on number of ratings above 250 and dropping duplicates in descending order
# Creating another dataframe for only these columns "Book-Title","Book-Author","Image-URL-M","num_ratings","avg_rating"
# Used Collaborative Filtering to classify user id of books having number of rating greater than 200
# classifying books for users who rated for books greater than 50 and dropping duplicates
#  forming a pivot table with book title and user id having values of book ratings , filling not a number places with 0
# importing cosine similarity from sklearn to find out cosine similarity of a book with each of other books in similarity scores
# cosine similarity is based on vectors which is calculated of each book with each other book
# forming a recommend function
#        -> storing book title in numpy array 
#        -> finding out similar books based on similarity scores
#        -> creating a list of lists as data and storing values of book Title , book Author,
#            and Image URL of medium image size
# Used Flask for backend to run on server port 5000 and rendering user interface on html using bootstrap
# rendering two html files one is home and other is to find similar kind of book based on user favourite book
# using thread to run the app on server
#############################END#####################################
