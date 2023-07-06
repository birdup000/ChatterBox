# ChatterBox - Chat Client (Made By AI, Directed by Human)

![ChatterBox Icon](icon.png)

ChatterBox is a chat client application that allows users to have interactive conversations with an AI assistant powered by OpenAI's ChatGPT model. This README provides an overview of the code and its functionality.

## Features

- Real-time chat interface with a user-friendly GUI
- Dark theme for a visually appealing experience
- Typing animation to simulate the assistant's responses
- System messages to provide additional information
- Ability to exit the application by typing "exit"

## Prerequisites

To run this code, you need to have the following:

- Python 3.x installed on your machine
- PyQt5 library installed (`pip install PyQt5`)
- OpenAI Python library installed (`pip install openai`)

## Getting Started

1. Clone the repository or download the code files.
2. Open the terminal or command prompt and navigate to the project directory.
3. Install the required dependencies mentioned in the "Prerequisites" section.
4. Replace the placeholder `API KEY GOES HERE` with your OpenAI API key.
5. (Optional) If you have a custom API endpoint, replace `Custom API ENDPOINT GOES HERE` with your endpoint.
6. Run the code using the command `python chat_client.py`.

## Usage

1. Upon running the code, the ChatterBox application window will open.
2. Type your message in the input field at the bottom and press "Send" or press Enter to send the message.
3. The assistant's response will appear in the message view area, with a typing animation to simulate real-time typing.
4. You can have a back-and-forth conversation with the assistant by sending multiple messages.
5. To exit the application, type "exit" in the input field and press "Send" or press Enter.

## Customization

### Changing the ChatGPT Model

By default, the code uses the `gpt-4` model for generating responses. If you want to use a different model, modify the `model` parameter in the `generate_response` method of the `ChatClient` class.

### Modifying the GUI

You can customize the GUI by modifying the code in the `init_ui` method of the `ChatClient` class. You can change the window title, window icon, window size, widget styles, and layout.

## License

This code is licensed under the [MIT License](LICENSE).
