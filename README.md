# LGMVIP-Python-Task-5
# Simple Chatbot with Python
This is a simple chatbot built in Python using NLTK (Natural Language Toolkit) and scikit-learn libraries.

## Overview
This chatbot can engage in basic conversations on topics such as greetings, farewells, and expressions of gratitude. It uses a TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer and cosine similarity to determine the most appropriate response based on user input.

 # Installation
Clone the repository:

bash
git clone https://github.com/your-username/simple-chatbot.git
Install the required dependencies:

pip install -r requirements.txt
Download NLTK resources:

python -m nltk.downloader wordnet
Usage
Run the chatbot.py script to start interacting with the chatbot:

python chatbot.py
The chatbot will prompt you to input messages, to which it will respond accordingly. Type "exit" to end the conversation.

 # Files
chatbot.py: The main script containing the chatbot implementation.
requirements.txt: A list of Python dependencies required to run the chatbot.
classifier.pkl: Pickle file containing the trained classifier.
vectorizer.pkl: Pickle file containing the TF-IDF vectorizer.
  # Contributing
Contributions are welcome! If you have suggestions or encounter any issues, feel free to open an issue or submit a pull request.
