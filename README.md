# Exploratory-Data-Analysis
# Play Store App Review Analysis

# Introduction -

**In this EDA, we will explore and analyze the given datasets based on "Play Store Review Analysis".The objective of this project is to deliver insights to understand customer demands better and thus help developers to popularize the product.In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.
We have two datasets in this project :playstore data.csv: contains all the details of the applications on Google Play. There are 13 features that describe a given app.
user_reviews.csv: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.**


# Problem Statement -
**Android is expanding as an operating system. It has captured around 74% of the total market which is a true indicator of the huge amount of population using android. Our goal is to help android developers to know what is the motivating factor for people to download an app. It will also help to find out the factors that affect someone’s decision to download an app. I would like to analyse category, reviews, price, ratings and installs for this purpose and find out how they are inter related.**


# Conclusion -
**From the plots, we've seen that apps from categories 'Game' and 'Communication' have a higher number of installs though are present in a very less number as compared to Category 'Family' in play store.The most installed genre is 'Communication'.
Apps with content rating 'Everyone' are present and installed in huge amount but we also observed that apps rated for 'Teen' also have a good number of installs. It shows that content rating 'Teen' needs to be explored more. Apps rated for 'Adults only 18+' has the highest average rating.
Also we noticed that users prefer Free apps more than Paid apps,the top 20 highest installed apps are all from Free type. Minecraft is the only app in the paid category with over 10M installs. Also one of the factors that matters while installing any app is Size. The apps whose size varies with device has the highest number average app installs.
Most of the apps that are having large number of reviews are from the categories of SOCIAL, COMMUNICATION and GAME like Facebook, WhatsApp Messenger, Instagram, Messenger – Text and Video Chat for Free, Clash of Clans etc indicating the active participation of users on these apps. Eventhough apps from the categories like GAME, SOCIAL, COMMUNICATION and TOOL are having the highest number of installs, rating and reviews , they are not appearing as category in the top 5 most expensive apps in the store (which are mostly from FINANCE and LIFESTYLE). We analysed that users like apps mostly from categories involving either assisting, communicating or entertaining .
Most of the reviews are of Positive Sentiment, while Negative and Neutral have low number of reviews.Collection of reviews shows a wide range of subjectivity and most of the reviews fall in [-0.50,0.75] polarity scale implying that the extremely negative or positive sentiments are significantly low. Sentiment subjectivity is not always proportional to sentiment polarity but in maximum number of case, shows a proportional behavior, when variance is too high or low.
Hope this will be helpful for app developers  to understand users needs and preference more.**   
