# Rule-Based Chatbot

def chatbot():
    print("Chatbot: Hello! I am a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        # Exit condition
        if user_input in ["bye", "exit", "quit"]:
            print("Chatbot: Goodbye! Have a nice day 😊")
            break

        # Rule-based responses
        elif "hello" in user_input or "hi" in user_input:
            print("Chatbot: Hello there! How can I help you today?")

        elif "how are you" in user_input:
            print("Chatbot: I'm just a program, but I'm doing great! How about you?")

        elif "your name" in user_input:
            print("Chatbot: I'm a simple rule-based chatbot 🤖")

        elif "weather" in user_input:
            print("Chatbot: I can't check the weather right now, but I hope it's nice where you are!")

        elif "time" in user_input:
            from datetime import datetime
            now = datetime.now().strftime("%H:%M:%S")
            print(f"Chatbot: The current time is {now}")

        else:
            print("Chatbot: Sorry, I don’t understand that. Can you try rephrasing?")

# Run chatbot
chatbot()# Rule-Based Chatbot

def chatbot():
    print("Chatbot: Hello! I am a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        # Exit condition
        if user_input in ["bye", "exit", "quit"]:
            print("Chatbot: Goodbye! Have a nice day 😊")
            break

        # Rule-based responses
        elif "hello" in user_input or "hi" in user_input:
            print("Chatbot: Hello there! How can I help you today?")

        elif "how are you" in user_input:
            print("Chatbot: I'm just a program, but I'm doing great! How about you?")

        elif "your name" in user_input:
            print("Chatbot: I'm a simple rule-based chatbot 🤖")

        elif "weather" in user_input:
            print("Chatbot: I can't check the weather right now, but I hope it's nice where you are!")

        elif "time" in user_input:
            from datetime import datetime
            now = datetime.now().strftime("%H:%M:%S")
            print(f"Chatbot: The current time is {now}")

        else:
            print("Chatbot: Sorry, I don’t understand that. Can you try rephrasing?")

# Run chatbot
chatbot()
