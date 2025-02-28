AI Chatbot - Predefined Intents with User Identity Recognition

Overview

This project defines a set of predefined chatbot intents using Python. The chatbot can recognize user inputs and respond based on predefined patterns. It also includes user identity recognition, allowing the bot to remember and acknowledge user names.

Features

Greeting & Farewell: Recognizes basic greetings and farewells.

Gratitude Response: Responds appropriately when a user says "Thank you".

Bot Information: Provides details about the chatbot when asked.

User Identity Recognition: Identifies and remembers user names.

Weather & Time Inquiry: Responds to weather and time queries.

Learning Capability: Indicates whether the bot can learn new things.

Hobbies & Fun: Engages users with casual conversation.

Motivation & Inspiration: Provides motivational responses.

Jokes: Tells jokes to entertain the user.

Handling Unknown Inputs: Provides a default response for unrecognized inputs.

JSON Structure

The chatbot's intent data is structured as a dictionary containing an intents list. Each intent consists of:

tag: A unique identifier for the intent.

patterns: A list of phrases that trigger the intent.

responses: A list of possible responses for the bot to choose from.

Example Intent

{
    "tag": "greeting",
    "patterns": ["Hi", "Hello", "Hey", "Good morning", "Good afternoon", "Howdy"],
    "responses": ["Hello! How can I assist you?", "Hey there! What’s on your mind?", "Hi! How’s your day going?"]
}

User Identity Recognition

The bot can recognize when a user asks about their identity (e.g., "What is my name?").

Users can introduce themselves with phrases like "My name is *".

The chatbot will acknowledge and attempt to remember the user's name.

How to Use

Load the predefined intents into your chatbot system.

Use Natural Language Processing (NLP) to match user input with defined patterns.

Respond with an appropriate response from the matched intent.

Expand the predefined intents by adding new tags, patterns, and responses.

Future Enhancements

Dynamic Learning: Enable the bot to learn new responses from user interactions.

API Integration: Fetch real-time weather and time updates.

Memory Persistence: Store user names for long-term recall.

License

This project is open-source and can be modified or extended as needed.

Author: [Your Name]Version: 1.0Date: [Date]

