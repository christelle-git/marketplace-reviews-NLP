# MarketPlace Reviews (NLP)

We investigate a reviews classification of PriceMinister marketplace. 
The dataset contains 60000 reviews described by 
* review content
* review title
* review stars
* hash code product

Each review is identified as usefil or not useful, we perform a classification to identity a review is useful or not.
The reviews are handled by NLP processing with 
* normalizing
* tokenization
* removing stopwords
* stemming & Lemmatization
* TF-IDF

We perform a Principal Components Analysis in order to reduce the number of features.
The Classification is performed by Logistic regression and others models comparison is conducted with Cross-validation. A grid-search strategy is applied on a Random Forest algorithm to improve the result, followed by a LightGBM algorithm.

<p align="center">
  <img src="https://github.com/christelle-git/marketplace-reviews-NLP/blob/master/index.jpeg">
</p>

OUTLINE:

 * 1) Data Exploration
 * 2) Data Processing
 * 3) Dimension reduction
 * 4) Classification by Logistic Regression
 * 5) Random Forest Grid-search
 * 6) LightGBM 
 * 7) Conclusion
