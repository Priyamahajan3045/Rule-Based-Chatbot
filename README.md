# Basic Rule-Based Chatbot

This is a **simple rule-based chatbot** built in Python using Jupyter Notebook. It can answer FAQs and handle unknown questions with a **Google search fallback**.

---

## Features

- Responds to **predefined questions** (FAQs).  
- Handles **unknown questions** by providing a Google search link.  
- Simple **console-based chatbot** interface in Jupyter Notebook.  
- Easy to **customize FAQs** to suit your own requirements.  

---

## FAQs Included

Some example questions:

- "hello", "hi" → greetings  
- "how are you" → bot response  
- "what is python" → explanation  
- "what is java" → explanation  
- "tell me a joke" → fun response  
- "bye" → exits the chatbot  

---

## How to Run

1. Open the Jupyter Notebook file `chatbot.ipynb`.  
2. Run the notebook **cell by cell**.  
3. Type your questions in the input box.  
4. To exit, type `"bye"`, `"exit"`, or `"quit"`.  

---

## Customizing FAQs

You can edit the `faq_dict` dictionary in the notebook to:

```python
faq_dict = {
    "hello": "Hi there!",
    "what is python": "Python is a programming language.",
    ...
}
