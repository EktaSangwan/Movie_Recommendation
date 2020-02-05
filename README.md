This is a basic **Movie Recommendation** system.

The main components are:

**CountVectorizer**

**cosine_similaity**

It uses CountVectorizer to count number of words and cosine_similarity to find similar words by looking at the orientation of words.

cosine_similarity is a better measure because other methods say Eucledian distance works on magnitude which can be very large for one doc and very small for other.
This would discriminate the similarities of features.
