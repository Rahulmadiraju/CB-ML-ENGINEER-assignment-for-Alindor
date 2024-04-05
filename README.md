
# Audio Sentiment Analysis

**Overview**

This project aims to provide a comprehensive solution for sentiment analysis and psychological insights derived from audio conversations between multiple speakers. It utilizes Deepgram API for accurate speech-to-text conversion and OpenAI API for advanced sentiment analysis. The system is integrated into a user-friendly web interface using Flask, allowing easy interaction and result visualization.


## Key Features

- **Speech-to-Text Conversion:** Utilizes Deepgram API to convert audio files into text transcripts.
- **Sentiment Analysis:** Employs OpenAI API to analyze sentiment and derive psychological insights from conversations.
- **Web Interface:** Provides a user-friendly interface for uploading audio files, initiating analysis, and viewing results.
- **Scalability:** Utilizes a cloud engine (e.g., Google Cloud Platform) for hosting the application and ensuring scalability.
- **Creative Analysis:** Implements creative prompts and methods to generate insightful and relevant outputs from the sentiment analysis.
## Installation and Setup

### Prerequisites ###

- Python 3.12.2 installed on your system.

- Flask and required Python packages installed (pip install -r requirements.txt).

- Deepgram API and OpenAI API credentials (obtainable from their respective websites).

### Steps ###

1. Clone the repository:
           
           git clone https://github.com/yourusername/audio-sentiment-analysis.git
           cd audio-sentiment-analysis
2. Install required Python packages:

            pip install -r requirements.txt
3. Configure API keys:

- Replace DEEPGRAM_API_KEY in speech_to_text.py and OPENAI_API_KEY in testlangchain.py with your actual API keys.
4. Start the Flask server:

            python app.py
5. Access the web interface in your browser


## Challenges Faced

- Ensuring accurate transcription of audio inputs, especially in noisy environments or with overlapping speech.
- Crafting creative prompts and methods to extract meaningful insights from the sentiment analysis.
- Designing an intuitive and responsive web interface for seamless user interaction.
## Future Enhancements
- Implement real-time audio processing for live conversations.
- Incorporate emotion detection for more nuanced sentiment analysis.
- Enhance user experience with additional features such as result history and user authentication.
