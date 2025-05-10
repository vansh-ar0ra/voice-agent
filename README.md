# Voice AI Assistant

A voice-based AI assistant built using LiveKit and various AI services. The assistant can engage in natural conversations using speech-to-text and text-to-speech capabilities.

## Features

- Real-time voice interaction
- Speech-to-text using Deepgram
- Text-to-speech using Cartesia/Deepgram
- Voice activity detection using Silero VAD
- Powered by Google's Gemini LLM
- Enhanced noise cancellation

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install livekit-agents python-dotenv
```

3. Create a `.env` file with the following API keys:
```
DEEPGRAM_API_KEY=your_deepgram_api_key
GOOGLE_API_KEY=your_google_api_key
CARTESIA_API_KEY=your_cartesia_api_key
LIVEKIT_URL=your_livekit_url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
```

4. Run the assistant:
```bash
python main.py
```

## Development

You can also use the Jupyter notebook (`testing.ipynb`) for development and testing purposes.

## Requirements

- Python 3.13+
- LiveKit account and credentials
- API keys for:
  - Deepgram (for speech-to-text)
  - Google (for Gemini LLM)
  - Cartesia (for text-to-speech)
  - LiveKit (for real-time communication) 