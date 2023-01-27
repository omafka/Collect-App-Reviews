# Collect-App-Reviews
The goal of this issue is to collect a minimum of 1000 reviews for any 10 cryptocurrency-related applications (100 each). These could be the apps of the blockchain wallets, crypto custodians, or any crypto projects.

1. Collect reviews for the apps of your choice and make sure that you define where the reviews are coming from Apple App Store or Google Play Store.
2. Identify sentiment score for each review using one of the existing sentiment analysis tools.
3. Identify either geolocation, or language for each review.
4. For the final deliverable, create:
 - CSV-file with the following structure: app name/username/timestamp/app review text/sentiment score (in process) /country (language) /marketplace*
*marketplace - Apple App Store or Google Play Store

 - short report with graphs (based on the reviews that you collected) and basic descriptive statistics

# Decision:
1. Collect 1000 reviews (Parser.ipynb) for 10 cryptocurrency-related applications (cryptocurrency-related applications.csv) -> get Reviews_CryptoApp.csv.
2. Analyzing collected reviews (Analyze_reviews.ipynb)
3. Identify sentiment score (Sentiment_analysis.ipynb) -> get Reviews_sentiment_score.csv.
