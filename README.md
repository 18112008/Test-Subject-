# Facebook Messenger Bot (Unofficial)

## Description

This repository contains a simple Facebook Messenger bot implemented using an unofficial Facebook API. The bot can perform various actions and respond to commands in group chats.

## Features

- Responds to commands starting with a customizable prefix (default: "!").
- Sends a welcome message when someone says "!hi".
- Provides a list of available commands with "!help".
- Allows users to add members to the group using "!add <username>".
- Fetches and sends images from Google Images using "!img <query>".
- Fetches and sends high-quality images from Unsplash using "!imgu <query>".
- Offers an anime guessing game that sends an anime character image and accepts answers using "!game" and "!ans <answer>".

## User Manual

To use this bot, follow these steps:

1. Clone this repository: `git clone https://github.com/Schmavery/facebook-chat-api`
2. Set up your Facebook API credentials and save them in an 'appstate.json' file.
3. Customize the bot's prefix or other settings as needed.
4. Run the bot using `node bot-code.js`.

### Setting up 'apstate.json'
'appstate.json' is a credentials file that uses Facebook cookies for login. To set up the correct 'appstate' and login with cookie credentials, please refer to the following issue link:
https://github.com/Schmavery/facebook-chat-api/issues/890#issuecomment-1021151788
Here is a Youtube tutorial: https://youtu.be/y9_yd5a3scM?si=U6zVodtRGNdlwoZX

If you have any kind of issue about Facebook Unofficial api, check this link https://github.com/Schmavery/facebook-chat-api

Please note that this is an unofficial Facebook Messenger bot, and it may not be officially supported by Facebook. Use it responsibly and ensure compliance with Facebook's policies and terms of service.


## Disclaimer

Dont use your main Facebook account. Facebook will suspend your account. So you can create any fake account or bot account to prevent any kind of ban issue. You can add some cooldown time to your bot. 

This bot is for educational purposes only and should not be used for spamming or any malicious activities on Facebook. Use it responsibly and in compliance with Facebook's policies and terms of service. Additionally, being an unofficial implementation, users should be prepared to handle any potential issues that may arise.

Feel free to explore the code and further customize the bot to suit your specific needs. The repository is a valuable resource for those interested in building and experimenting with Facebook Messenger bots.
