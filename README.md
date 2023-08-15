# EasyChatGPT - AI-Powered Chat App
Welcome to EasyChatGPT - your AI-powered chat application! This app demonstrates real-time conversations with the OpenAI GPT-3 model using the OkHttp library for API calls. Below, we provide an overview of key files and features:
![Untitled design](https://user-images.githubusercontent.com/60041910/218378637-adf9bcbf-5c7e-4274-8491-1ebe2a28b396.gif)


## Key Features

- **Real-time Conversations:** Engage in dynamic conversations with the OpenAI GPT-3 model.
- **User-friendly Interface:** Simple and intuitive user interface for seamless chatting.
- **Message History:** Display a history of sent and received messages.
- **OpenAI Integration:** Utilize the power of the OpenAI API for text completion.

## Usage

1. Clone or download the repository to your local machine.
2. Open the project in Android Studio.
3. Replace `YOUR_API_KEY` in `callAPI()` with your OpenAI API key.
4. Build and run the app on your Android device or emulator.

## File Structure

- `MainActivity.java`: The main activity managing chat functionality and API calls.
- `Message.java`: Data model for individual chat messages.
- `MessageAdapter.java`: RecyclerView adapter for displaying messages.
- `activity_main.xml`: Layout XML file for the main chat activity.

## How It Works

1. User inputs a message and taps the send button.
2. The message is added to the chat history as "Sent by Me".
3. The app calls the OpenAI API with the user's message.
4. The API response (bot's reply) is added to the chat history as "Sent by Bot".

## Important Note

Ensure you have obtained your OpenAI API key and added it to the `Authorization` header in the `callAPI()` function.

## Disclaimer

Please be cautious while integrating API keys and sensitive information in your code. This repository is for educational purposes and to showcase integration with the OpenAI API.

## Resources

- [OpenAI API Documentation](https://beta.openai.com/docs/)
- [OkHttp Library](https://square.github.io/okhttp/)

Feel free to explore, experiment, and contribute to this project. Happy coding!

---

*Disclaimer: This repository is for educational purposes and does not provide guarantees or warranties for any purpose. It is recommended to follow best practices for securing API keys and sensitive information.*
