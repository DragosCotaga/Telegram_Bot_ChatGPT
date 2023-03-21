# Telegram ChatGPT Bot
This Python Telegram Chatbot uses OpenAI's API to generate responses to user requests in a Telegram group. The bot can be configured with different OpenAI models and personalities to provide responses in different tones.
## Setup  
To use the bot, follow these steps:
1. Clone this repository to your local machine.
2. Install the required libraries by running pip install -r requirements.txt.
3. Open the telegram_chatbot.py file in a text editor.
4. Add your OpenAI API key to the API_KEY variable.
5. Choose the OpenAI model you want to use by changing the MODEL variable. The available models are: text-davinci-003, text-curie-001, text-babbage-001, and text-ada-001.
6. Add your Telegram bot token to the BOT_TOKEN variable.
7. Define the bot's personality using adjectives by modifying the BOT_PERSONALITY variable.
8. Specify your Chat Bot handle by modifying the CHATBOT_HANDLE variable.
9. Save the changes to the telegram_chatbot.py file.
## Usage
- To use the bot, start a Telegram group and add the bot to the group. Then, send messages to the group mentioning the bot's username (@ask_chatgptbot) and your request.
- The bot can respond to text requests and image requests. To request an image, include the text /img in your message, followed by a prompt for the image.
## Running the Bot
To start the bot, run the telegram_chatbot.py file in a terminal. The bot will run continuously, checking for new requests in the Telegram group every 5 seconds. To stop the bot, press CTRL + C in the terminal.
