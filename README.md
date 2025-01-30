# 🔍 CrewAI Research Assistant

A powerful research assistant built with CrewAI, Exa, and Streamlit that helps you research any topic using AI Agents.

![CrewAI Logo](https://cdn.prod.website-files.com/66cf2bfc3ed15b02da0ca770/66d07240057721394308addd_Logo%20(1).svg)

![App Screenshot](app.png)

## 🌟 Features

- 🤖 Multiple LLM Support (OpenAI and GROQ)
- 🔍 Advanced answering capabilities using Exa
- 📊 Real-time research process visualization
- 📝 Structured research reports
- 🎯 Topic-focused research and analysis
- 🔒 Secure API key management
- 📱 Responsive and modern UI

## 🛠️ Project Structure

```
.
├── streamlit_app.py          # Main application file
└── src/
    ├── components/           # UI and functional components
    │   ├── researcher.py     # Research agent implementation
    │   └── sidebar.py        # Sidebar configuration
    └── utils/
        └── output_handler.py # Process output management
```

## 📋 Requirements

- Python >=3.10 and <3.13
- OpenAI API key or GROQ API key
- Exa API key
- Streamlit

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/crewai-research-assistant.git
cd crewai-research-assistant
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
streamlit run streamlit_app.py
```

## 🔑 API Keys Setup

The application requires the following API keys:

1. **OpenAI API Key** or **GROQ API Key**
   - For OpenAI: Get it from [OpenAI Platform](https://platform.openai.com/)
   - For GROQ: Get it from [GROQ Console](https://console.groq.com/)

2. **Exa API Key**
   - Get it from [Exa](https://exa.ai)

Enter these keys in the sidebar of the application when prompted.

## 🎯 Usage

1. Open the application in your web browser
2. Select your preferred LLM provider (OpenAI or GROQ)
3. Enter your API keys in the sidebar
4. Type your research query in the text area
5. Click "Start Research" to begin the research process
6. View the real-time research process and final results

## 💡 Features in Detail

### Research Agent
The research agent (`src/components/researcher.py`) is powered by CrewAI and configured to:
- Conduct thorough research on given topics
- Analyze and summarize information
- Provide structured reports with key findings

### Process Output
The output handler (`src/utils/output_handler.py`) provides:
- Real-time process visualization
- Clean, formatted output
- Progress tracking

### User Interface
The application features a modern, responsive UI with:
- Intuitive sidebar configuration
- Clear process visualization
- Organized research results
- Professional styling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [CrewAI](https://crewai.com) for the AI agent framework
- [Exa](https://exa.ai) for advanced search capabilities
- [Streamlit](https://streamlit.io) for the web interface

---
Made with ❤️ using CrewAI, Exa, and Streamlit
