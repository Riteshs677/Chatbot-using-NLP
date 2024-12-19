# Chatbot using NLP

## Overview
This project focuses on developing a chatbot that leverages Natural Language Processing (NLP) techniques to interpret user intents and generate appropriate responses. The chatbot is built using Python and incorporates libraries such as nltk for NLP tasks, scikit-learn for machine learning functionalities, and streamlit for creating an interactive web interface.


## Features
Intent Recognition: The chatbot can identify various user intents, including greetings, farewells, and expressions of gratitude.
Response Generation: It provides contextually relevant responses based on user inputs.
Conversation History: Users can view their conversation history, enhancing the interactive experience.
Technology Stack: Developed in Python, utilizing well-known libraries for NLP and machine learning.

---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation


### 1. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 2. Install Required Packages
```bash
pip install -r requirements.txt
```

### 3. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

