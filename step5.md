# Create and Configure Amazon Lex Chatbot
![step5]()
### Navigate to Amazon Lex in the AWS Console.

#### Create a new bot:
- Select Create Bot and choose a Custom Bot (Traditional).
- Configure the bot’s name, language, and session timeout.
- Use the IAM role created earlier to allow Lex to interact with Bedrock and S3.

#### Define Intents and Slots:
- Set up predefined intents

## Build And Test The Chatbot
![step5.1]()

#### Build the Bot
- After configuring intents and slots, click Build to compile the chatbot configuration.

#### Test the Chatbot
- Use the Test Chatbot option in Amazon Lex to simulate conversations.
- Verify that the bot can handle common queries and respond correctly by referencing the knowledge base and utilizing AI models from Bedrock.