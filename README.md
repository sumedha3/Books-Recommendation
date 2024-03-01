# Books-Recommendation

## Steps
* EDA
* Data Preprocessing
* Hyperparameter Tuning
* Classification Genre
* Recommendation

## Word2Vec model
The genre prediction process is carried out after the vector representation of book titles is generated. In this script, genre prediction is carried out by looking for similarities between the vector representation of the book title and the vector representation for each previously determined genre. The genre most similar to the vector representation of book titles, based on cosine similarity, is selected as the genre predictor.

It is worth noting that the trained Word2Vec model only learns patterns from the text given during training. So, if a book title is in multiple languages ​​such as English, Spanish, French, Turkish, Russian, or any other language, the Word2Vec model will learn the word patterns in that language and generate a vector representation based on those patterns. Then, genre prediction is carried out based on the resulting vector representation, without paying attention to the original language of the book title. Therefore, this model does not explicitly consider language when making genre predictions.

## Conclusion
Word2Vec works by converting each word in a book title into a vector that has a mathematical representation. This means looking for similarities between the vector representation of book titles and the vector representation for each predetermined genre. The genre most similar to the vector representation of book titles, based on cosine similarity, is selected as the genre predictor.

Then based on the results of the graphic analysis, the genre with the most interest is Horror and Fiction.

* Achieved 74% accuracy in genre prediction using Naive Bayes with hyperparameter tuning.
* Developed a recommendation system utilizing Word2Vec embeddings to suggest similar books based on title and genre, enhancing user engagement and personalization.
