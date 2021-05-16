# AI-Chatbot
## Discover the open source AI Chatbot 
This AI chatbot is an open source project you can always improve it by adding some examples and subjects to the model itself
in the **intents.json** file
## How to use it ? 
Just run the **chatbot.py** using the command `python chatbot.py` and then start to your exprience and whenever
you add some new data to the model (basically adding them to **intents.json**) run the `python training.py` after
that go back to the **chatbot.py** and test you're data
### PS : 
```python
bug if report() else fix()
``` 
### intents.json :
```json
{
    "tag": "Greeting",
    "patterns": ["Hi", "How are you", "Is anyone there?", "Hello", "Good day", "Whats up", "Hey", "greetings"],
    "responses": ["Hello!", "Good to see you again!", "Hi there, how can I help?"],
    "context_set": ""
  }

```
