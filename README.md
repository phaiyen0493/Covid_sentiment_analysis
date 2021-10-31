# Covid_sentiment_analysis
Execution Instructions

The user will need to get a Reddit API key to run Reddit_Archiver.ipynb file. To do this they will need to go to the following link: https://www.reddit.com/prefs/apps and create a new Reddit App. The app should be a script. It does not matter what they name it. It should probably just use http://localhost:8080 as a redirect uri. Once they have created the app, the keys should be formatted like so:

{
    "client_id": "14_CHARACTER_CLIENT_ID",
    "client_secret": "27_CHARACTER_SECRET_KEY",
    "user_agent": "WHATEVER_YOU_NAMED_THE_APP",
    "username": "YOUR_REDDIT_USERNAME",
    "password": "YOUR_REDDIT_PASSWORD"
}
For obvious reasons, we cannot share our passwords or secret keys.

The user will also need to get Twitter API keys to run Twitter_Archiver.ipynb file. Please check out this link to get instructions of how to get the keys:https://towardsdatascience.com/how-to-access-twitters-api-using-tweepy-5a13a206683b

Similarly, user also need to get Youtube Data v3 API. Check out this link to get instructions of how to set up the Google account and API key: https://blog.hubspot.com/website/how-to-get-youtube-api-key

Reddit_Archiver.ipynb, Twitter_Archiver.ipynb, Youtube_Archiver.ipynb and Data_Analysis.ipynb were run on Jupyter Notebook, while Topic_Modeling.ipynb and Sentiment_Analysis.ipynb were built on Google Colab.

Datasets are saved on Google Drive: https://drive.google.com/drive/folders/1SU7IAIOgdzuDgU4eCu03R2l8a436WKqU?usp=sharing
