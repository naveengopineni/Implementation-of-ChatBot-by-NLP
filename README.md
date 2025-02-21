# Implementation-of-ChatBot-by-NLP
This project aims at the development of a ChatBot that can hold human-like conversation with the users, using the various Natural Language Processing techniques.The chatbot is designed to understand user intents and provide appropriate responses based on predefined patterns and responses. It utilizes the nltk library for natural language processing, scikit-learn for machine learning, and streamlit for creating an interactive web interface
<h2>Features</h2>
Understands various user intents such as greetings, farewells, gratitude, and more.
Provides relevant responses based on user input.
Maintains a conversation history that can be viewed by the user.
Built using Python and leverages popular libraries for NLP and machine learning.
<h2>Technologies Used</h2>
1) Python
2) NLTK
3) Scikit-learn
4) Streamlit
5) JSON for intents data




<h2>Technologies Used</h2>
Python
NLTK
Scikit-learn
Streamlit
JSON for intents data
<h2>Installation</h2>
1. Clone the Repository
git clone <repository-url>
cd <repository-directory>
2. Create a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install Required Packages
pip install -r requirements.txt
4. Download NLTK Data
import nltk
nltk.download('punkt')
<h2>Usage</h2>
To run the chatbot application, execute the following command:

<h2>streamlit run app.py</h2>
Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

<h2>Intents Data</h2>
The chatbot's behavior is defined by the intents.json file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

<h2>Conversation History</h2>
The chatbot saves the conversation history in a CSV file (chat_log.csv). You can view past interactions by selecting the "Conversation History" option in the sidebar.

<h2>Contributing</h2>
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

<h2>Acknowledgments</h2>
NLTK for natural language processing.
Scikit-learn for machine learning algorithms.
Streamlit for building the web interface.

