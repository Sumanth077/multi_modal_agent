# Multimodal AI Agent with Gemini and Reflex

An intelligent video analysis agent that also performs web searches. This application, built with Reflex and Google's Gemini Flash 2.0, enables users to upload videos and ask questions about them. By combining advanced video analysis with web research capabilities, it provides comprehensive, context-aware responses.

## Features
- **Video Upload**: Supports multiple formats, including MP4, MOV, and AVI.
- **Real-Time Video Analysis**: Utilizes Google's Gemini Flash 2.0 model.
- **Web Research Integration**: Powered by DuckDuckGo for enhanced context.
- **Interactive Q&A System**: Allows dynamic interaction for tailored responses.
- **Responsive UI**: Clean and user-friendly interface for seamless usage.

## Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/reflex-dev/reflex-llm-examples.git
   cd reflex-llm-examples/multi-modal-ai-agent
   ```

2. **Set up a virtual environment** (optional but recommended):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Obtain the Google Gemini API Key**:  
   - Sign up for a Google AI Studio account and generate an API key [here](https://aistudio.google.com/apikey). 
   - Set up your API key as an environment variable:  
     ```bash
     export GOOGLE_API_KEY=your_api_key_here
     ```

5. **Run the Reflex application**:  
   Start the Reflex server with:  
   ```bash
   reflex run
   ```

## Usage

1. **Upload a Video**: Use the drag-and-drop interface to upload your video.
2. **Ask a Question**: Enter your query about the video in the provided text area.
3. **Analyze & Research**: Click the "Analyze & Research" button to process the video and generate AI-driven insights.
4. **View Results**: Access detailed responses combining video analysis and web research.