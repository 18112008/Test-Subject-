Description:
This repository contains a simple Facebook Messenger bot implemented using an unofficial Facebook API. The bot can perform various actions and respond to commands in group chats.

Features:

Responds to commands starting with a customizable prefix (default: "!").
Sends a welcome message when someone says "!hi".
Provides a list of available commands with "!help".
Allows users to add members to the group using "!add <memberId>".
Fetches and sends images from Google Images using "!img <imageName>".
Fetches and sends high-quality images from Unsplash using "!imgu <imageName>".
Offers an anime guessing game that sends an anime character image and accepts answers using "!game" and "!ans <your answer>".
User Manual:

Clone this repository: git clone https://github.com/yourusername/fb-unofficial-bot.git
Set up your Facebook API credentials and save them in an 'appstate.json' file.
Customize the bot's prefix or other settings as needed.
Run the bot using node yourbotfile.js.
Please note that this is an unofficial Facebook Messenger bot, and it may not be officially supported by Facebook. Use it responsibly and ensure compliance with Facebook's policies and terms of service.

Features and Functionality:

Welcome Message: When a user initiates a conversation with the bot by typing "!hi," the bot responds with a friendly welcome message. It even uses mentions to highlight the user's name, making the interaction more personalized.

Help Command: Users can easily discover what commands are available by typing "!help." The bot responds with a list of available commands, helping users navigate and make the most of its capabilities.

Adding Members: One useful feature of this bot is the ability to add members to a group chat using the "!add <memberId>" command. This can be particularly handy for group administrators who need to manage group members efficiently.

Image Retrieval: The bot can fetch and send images from Google Images using the "!img <imageName>" command. Users simply specify the image they want, and the bot does the rest. It also provides the option to fetch high-quality images from Unsplash using "!imgu <imageName>."

Anime Guessing Game: This bot offers an engaging anime guessing game. It randomly selects an anime character name from a predefined list and sends an image of that character to the group chat. Users can then attempt to guess the character's name by typing "!ans <your answer>." The bot evaluates the answers and provides feedback. It's a fun way to engage group members and test their knowledge of anime characters.

Error Handling: The bot is equipped with error-handling mechanisms. It can send error messages to the chat in case of issues, such as when it fails to download an image or encounters an unexpected error.

Cleanup: The bot also performs cleanup tasks. For instance, after sending an image, it deletes the image file from the local directory to keep things tidy.

Customization: Users can customize the bot's prefix, allowing them to set their own trigger for commands. This makes it adaptable to different group chat contexts and preferences.

User Manual:

The provided user manual in the repository's description offers clear instructions on how to set up and use the bot. By following these steps, users can easily get the bot up and running in their own Facebook group chats.

Remember, while this bot provides a fun and interactive experience in group chats, it should be used responsibly and in compliance with Facebook's policies and terms of service. Additionally, being an unofficial implementation, users should be prepared to handle any potential issues that may arise.

Feel free to explore the code and further customize the bot to suit your specific needs. The repository is a valuable resource for those interested in building and experimenting with Facebook Messenger bots.

Disclaimer: This bot is for educational purposes only and should not be used for spamming or any malicious activities on Facebook.
