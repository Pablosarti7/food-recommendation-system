# Food Recommendation System
A recommendation system with a TF-IDF Vectorizer and some math to compute the similarity between tags.

## What is this system for?
This recommendation system was originally designed for a barcode-scanning web app for food items at the grocery store. The app identifies ingredients in grocery store items that are detrimental to your health and then uses this recommendation system to provide users with a suggestion for a better product.

## How Does It Work?
This content-based recommendation system suggests healthier alternatives by analyzing the ingredients of a scanned product and finding similar, but healthier, options. It compares the TF-IDF vectors to determine how similar two products are based on their ingredients. To find healthier alternatives, it filters out products that do not meet a certain health threshold and displays the better options to the user.
