# Real Estate Agents Chatbot

A Streamlit-based chatbot application for real estate agents that can handle property issues, tenancy questions, and image analysis.

## Features

- **Property Issue Assessment**: Analyze and diagnose property-related issues
- **Tenancy FAQ**: Answer questions about tenancy agreements, rights, and responsibilities
- **Image Analysis**: Upload property images for analysis
- **Location-Aware Responses**: Provide region-specific information based on user location
- **Multi-Agent System**: Uses a graph-based multi-agent system for intelligent responses

## Installation

1. Clone the repository:
```
git clone https://github.com/Anujh23/real_state_agents.git
cd real_state_agents
```

2. Create a virtual environment and activate it:
```
python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Create a `.env` file with your API keys:
```
GOOGLE_API_KEY=your_google_api_key_here
```

## Usage

Run the Streamlit application:
```
streamlit run Chatbot/app.py
```

The application will be available at http://localhost:8501

## Project Structure

- `Chatbot/`: Contains the Streamlit application
  - `app.py`: Main application file
  - `graph.py`: Multi-agent graph implementation
  - `schemas.py`: Data models for responses
- `requirements.txt`: List of Python dependencies

