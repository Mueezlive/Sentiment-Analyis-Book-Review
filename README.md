# Book-Review-
This is a small subset of dataset of Book reviews from Amazon Kindle Store category.  Content 5-core dataset of product reviews from Amazon Kindle Store category from May 1996 - July 2014. Contains total of 982619 entries. Each reviewer has at least 5 reviews and each product has at least 5 reviews in this dataset.

Columns
- asin - ID of the product, like B000FA64PK
- helpful - helpfulness rating of the review - example: 2/3.
- overall - rating of the product.
- reviewText - text of the review (heading).
- reviewTime - time of the review (raw).
- reviewerID - ID of the reviewer, like A3SPTOKDG7WBLN
- reviewerName - name of the reviewer.
- summary - summary of the review (description).
- unixReviewTime - unix timestamp.

Acknowledgements


This dataset is taken from Amazon product data, Julian McAuley, UCSD website. http://jmcauley.ucsd.edu/data/amazon/

License to the data files belong to them.

Inspiration
- Sentiment analysis on reviews.
- Understanding how people rate usefulness of a review/ What factors influence helpfulness of a review.
- Fake reviews/ outliers.
- Best rated product IDs, or similarity between products based on reviews alone.

- Conclusion
- SVM is the best-performing model in this comparison. It has the highest accuracy and weighted F1-score, alongside balanced recall for negative and positive reviews. Logistic Regression is a close second and also provides balanced classification performance.

Random Forest is particularly effective at identifying positive reviews, but its lower negative recall may make it less suitable if detecting negative customer feedback is a priority.

One important qualification: these conclusions assume that all four models were evaluated on the same test set using the same class definitions. Also, because precision is not included in your table, the results do not show how reliable each model's positive and negative predictions are.
