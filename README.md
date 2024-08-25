# Artificial-intelligence -TASK 1 (chatbot)
def greeting_chatbot(user_input):
    user_input = user_input.lower()

    if "hello" in user_input or "hi" in user_input:
        return "Hello! How can I help you today?"
    elif "good morning" in user_input:
        return "Good morning! I hope you have a wonderful day ahead!"
    elif "good night" in user_input:
        return "Good night! Sweet dreams!"
    else:
        return "I'm not sure how to respond to that."

# Test the chatbot
user_input = input("You: ")
print("Chatbot:", greeting_chatbot(user_input))
