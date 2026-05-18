**Simple Rule-Based Chatbot**

A beginner-friendly Python chatbot that responds to user inputs using pre-defined rules and keyword matching.

**Features**

- Responds to common greetings (hello, hi, hey)
- Handles farewells (bye, goodbye)
- Answers simple questions about the weather
- Falls back to a default response for unrecognized inputs
- Runs entirely in a Jupyter Notebook environment

##  How It Works

The chatbot uses a rule-based approach:
1. User input is captured and converted to lowercase
2. The input is checked against a dictionary of predefined keywords
3. If a keyword match is found, the corresponding response is returned
4. If no keywords are recognized, a default "I don't understand" message is shown

### Example Rules

| User Says | Bot Responds |
|-----------|---------------|
| "hello" | "Hello! How can I help you today?" |
| "hi" | "Hi there! What can I do for you?" |
| "weather" | "The weather is sunny and warm today." |
| "bye" | "Goodbye! Have a great day!" |

##  Prerequisites

- Python 3.x installed on your system
- Jupyter Notebook or JupyterLab (recommended)

 **Project Structure**
 
text
Simple-Rule-Based-Chatbot/
└── SimpleRuleBasedChatbot.ipynb    # Main chatbot implementation

**Customization**

You can easily extend the chatbot's capabilities by adding new rules to the self.rules dictionary:

python
self.rules = {
    # Existing rules...
    "your_keyword": "Your custom response here",
    # Add more as needed
}   

**👤 Author**

Aishaaa-dev - GitHub Profile

**Acknowledgments**

Built as a learning project to understand rule-based chatbot fundamentals

Inspired by classic keyword-matching chatbot architectures
