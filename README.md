# J.A.R.V.I.S - OpenAI + Python Powered AI Desktop Assistant 🤖🎤

Welcome to **J.A.R.V.I.S**! This project is a Python-based AI Desktop voice assistant inspired by the famous Jarvis from the Iron Man movies. It can perform various tasks such as opening applications,
telling jokes, and even answering questions through ChatGPT Integration and just talks Like a Human.

## Features ✨

- 🎙️ **Voice Recognition**: Understands and responds to voice commands using the Google Web Speech API.
- 🗣️ **Text-to-Speech**: Converts text responses to speech for a conversational experience using Pyttsx3.
- 📝 **OpenAI Integration**: Answers questions using OpenAI's GPT-3 (with your API key).
- 🌐 **Web Automation**: Opens websites and performs web searches.
- 📅 **Date and Time**: Tells the current date and time.
- 📄 **System Applications**: Opens system application on command.

### OpenAI Integration 📝

One of the standout features of JarvisAI is its integration with OpenAI's GPT-3. This allows the voice assistant to answer a wide range of questions with intelligent and contextually relevant responses.
By leveraging the power of GPT-3, JarvisAI can handle complex queries, provide detailed information, and even engage in more natural and human-like conversations.

#### How It Works

- **OpenAI GPT-3 API**: JarvisAI uses the GPT-3 model from OpenAI, one of the most advanced language models available. This model has been trained on a diverse range of internet text, allowing it to generate human-like text based on the input it receives.
- **API Key**: To use GPT-3, you need an API key from OpenAI. This key is used to authenticate your requests to the OpenAI servers, enabling you to send queries and receive responses.

#### Setting Up OpenAI

1. **Obtain an API Key**:
   - Sign up for an API key at [OpenAI's website](https://beta.openai.com/signup/).
   - Once you have your key, keep it safe as it will be used to access the GPT-3 API.

2. **Configure Your Project**:
   - Open the `config.py` file in your project directory.
   - Replace the placeholder `"Your-Open-AI-Key"` with your actual OpenAI API key:
     ```python
     apikey = "Your-Open-AI-Key"
     ```

3. **Using GPT-3 in JarvisAI**:
   - With the API key in place, JarvisAI can now send queries to GPT-3.
   - When you ask JarvisAI a question that requires detailed information or natural language understanding, it will query the GPT-3 API and return the generated response.

#### Example Commands
Here are some examples of what you can ask JarvisAI with the OpenAI integration:

- **General Knowledge**: "Who is the president of the United States?"
- **Advice**: "Can you give me some advice on studying effectively?"
- **Explanations**: "Explain the theory of relativity."
- **Creative Writing**: "Write a short story about a space adventure."

This powerful integration enhances JarvisAI's capabilities, making it not just a voice assistant but a sophisticated conversational agent.

---

## Technologies Used 🛠️

- OpenAI API
- Python
- Pyttsx3
- SpeechRecognition
- Webbrowser
- Numpy Library

## Getting Started 🚀

Follow these steps to get a copy of the project up and running on your local machine.

### Prerequisites 📋

- Python 3.x
- Pip (Python package installer)

### Installation 🔧

1. **Clone the repository**:
   ```sh
   git clone https://github.com/CodeWithHarry/JarvisAI-YouTube.git
   cd JarvisAI-YouTube-CWH

2. **Install the required packages**:
   ```sh
   pip install -r requirements.txt
   ```

3. Invoke your ApiKey and use it.

## Contributing 🙌
Any contributions you make are greatly appreciated.

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## Acknowledgments
- Refer CodeWithHarry YouTube channel for more in-depth Knowledge of this tutorial and build your own from scratch.
  [J.A.R.V.I.S - AI Desktop Assistant Tutorial](https://youtu.be/s_8b5iq4Rvk?si=_E3HtUQJYAsaJYy-)
- OpenAI for the GPT-3 API.
