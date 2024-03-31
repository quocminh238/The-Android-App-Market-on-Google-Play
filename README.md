# The Android App Market on Google Play

## Google Play Store apps and reviews
Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.

<p align="center">
  <img width="100" src="https://github.com/quocminh238/The-Android-App-Market-on-Google-Play/blob/main/pictures/google_play.jpg">
</p>

Let's take a look at the data, which consists of two files:
- <code>apps.csv</code>: contains all the details of the applications on Google Play. There are 13 features that describe a given app.
- <code>user_reviews.csv</code>: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.
