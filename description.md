# twitter-chat-gpt-bot
This Python script uses the Twitter and OpenAI APIs to listen for mentions of a Twitter account and generate automated replies using GPT-3. It checks for new mentions every hour and avoids giving duplicate responses. The script includes error handling to deal with rate limits, forbidden content, and tweets that exceed the maximum length.

The goal of this project is to build a Python script that will listen for mentions of a Twitter account and use OpenAI's GPT-3 API to generate a reply in the comments of the mentioned tweet. The script will continue running in a loop, checking for new mentions every hour and making sure to not give duplicate responses.

To accomplish this, the script will use the Twitter API to search for tweets that mention the account, and the OpenAI API to generate a reply using GPT-3. It will then post the reply as a comment on the original tweet.

The script will also include error handling to deal with various issues that might arise, such as rate limits, forbidden content, and tweets that exceed the maximum length.

Overall, this project aims to create a simple and automated system for generating replies to tweets that mention a particular Twitter account using GPT-3.
