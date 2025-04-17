
# Voice Assistant Project

## Project Description:
This is a voice assistant project designed to perform various tasks based on voice commands. It uses speech recognition, text generation (using GPT models), and a simple interface to interact with the user. The project aims to simulate a voice-based AI assistant.

## Key Features:
- **Speech Recognition**: The assistant listens to user input and converts speech to text.
- **Text Generation**: Based on the input, it generates responses using models like GPT or other alternatives.
- **Text-to-Speech**: Converts the generated text back to speech for the user to hear.

## Technologies Used:
- `SpeechRecognition` (for speech-to-text)
- `pyttsx3` (for text-to-speech)
- `transformers` (for GPT-like models)
- `Google Search API` (for fetching information from the web)

## Challenges Faced:
- **Latency in Response Time**: The response time for generating answers was sometimes slow, especially when using large models.
- **Accuracy Issues**: Some voice inputs weren't recognized accurately due to background noise or unclear speech.
- **Integration of Web Search**: Integrating Google search results with GPT models to provide accurate and context-aware answers was a challenge.

## Mistakes Made:
- **Inconsistent Handling of Input**: Early versions of the code didn’t handle varying user inputs well, leading to incorrect responses.
- **API Limitations**: I initially tried using some APIs that were not suitable for the project due to API rate limits or lack of accuracy.

## Changes & Enhancements:
- **Improved Input Handling**: I added more robust error handling and validation to ensure the assistant can handle diverse inputs.
- **Optimized Response Generation**: Switched to a more lightweight GPT model (`distilgpt2`) to improve speed and reduce latency.
- **Voice Feedback**: Integrated text-to-speech functionality to provide verbal feedback to the user.

## Future Improvements:
- **Expand Voice Commands**: Add more voice commands for controlling other applications or performing complex tasks.
- **Improve Speech Recognition**: Use a more accurate model for speech-to-text to handle various accents and noise conditions.

## How to Run the Project:
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python main.py
   ```
