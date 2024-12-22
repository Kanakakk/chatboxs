# chatboxs
def chatbot():
    responses = {
        "hello": "Hello! How can I help you today?",
        "hi": "Hi there! What can I do for you?",
        "how are you": "I'm doing well, thank you. How are you?",
        "what's your name": "You can call me the Chatbot.",
        "what can you do": "I can answer your questions, provide information, and assist with tasks. How can I help you?",
        "tell me a joke": "Sure, here's a joke: Why did the scarecrow win an award? Because he was outstanding in his field!",
        "bye": "Goodbye! Have a nice day.",
        "goodbye": "Goodbye! Have a nice day."
    }

    while True:
        user_input = input("> ").lower()

        if user_input in responses:
            print(responses[user_input])
        else:
            print("I'm not sure I understand. Can you rephrase that?")

if __name__ == "__main__":
    chatbot()
