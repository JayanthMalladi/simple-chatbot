
# Simple Chatbot Using Machine Learning and NLP

This project demonstrates the creation of a simple chatbot using **TensorFlow** for machine learning and **Natural Language Processing (NLP)** techniques. The chatbot is trained on a custom dataset to recognize user intents and respond appropriately. It handles a variety of interactions, from basic greetings to more specific information about a fictional institution and resources.

## Features

- **Intent Recognition**: Identifies user inputs and maps them to pre-defined categories.
- **Natural Language Processing (NLP)**: Processes text-based inputs to understand and respond to user queries.
- **Custom Dataset**: Trained on a small dataset of intents such as greetings, farewells, help requests, and information about a fictional "Jarvis" bot.
- **Flexible Responses**: Generates multiple responses for each recognized intent, enhancing the interaction's natural feel.

## Technologies Used

- **TensorFlow**: A powerful open-source library for machine learning, used to train and build the model.
- **Natural Language Toolkit (NLTK)**: For text preprocessing and tokenization, helping the chatbot to understand user inputs.
- **Python**: For building and running the chatbot scripts.

## Intents Dataset

The chatbot is trained on a collection of intents, each comprising multiple patterns (input examples) and corresponding responses. Key intents include:

- **Greeting**: Recognizes and responds to greetings like "Hello" or "Hi".
- **Goodbye**: Responds to farewells such as "Goodbye" or "See you later".
- **Thanks**: Acknowledges gratitude with responses like "You're welcome!" or "Happy to help!".
- **About**: Provides information about the chatbot itself (fictional assistant named "Jarvis").
- **Name**: Answers questions about the bot's name.
- **Help**: Offers assistance when the user requests help.
- **College**: Answers questions about a fictional college and related topics.
- **Gymkhana**: Responds to queries about a position in a fictional student body.
- **Resources**: Provides learning resources, pointing users to useful educational platforms.
- **Campus**: Offers information about a fictional college campus and its website.

The intents are stored in `intents.json`, which includes patterns for user inputs and predefined responses.

## Project Structure

- **intents.json**: Contains the training data for the chatbot, including intents, patterns, and responses.
- **chatbot.py**: Script to build, train, and save the machine learning model using TensorFlow.
- **actual_chatbot.py**: Main application script that loads the model and handles real-time user interactions.

## Future Enhancements

- **Add more intents**: Expand the chatbot’s capabilities by adding new categories and responses.
- **Improve NLP capabilities**: Use advanced NLP techniques to improve understanding and generate more sophisticated responses.
- **Integrate with messaging platforms**: Extend the chatbot’s usability by integrating it with platforms like Slack, Telegram, or a web application.
- **Enhance conversation flow**: Implement context management for more fluid and dynamic conversations.

## Contributing

Contributions are welcome! If you'd like to improve the chatbot or add new features, feel free to fork the repository and submit a pull request.

