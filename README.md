# News Agent

This project leverages CrewAI and Google's Gemini-1.5-Flash model to create a crew of two agents: a Researcher and a Writer. The Researcher agent surfs the internet to gather all the details about a particular topic and passes these details to the Writer agent, who then composes a detailed and concise article and provides the result in a .md file.

## Features

- **Researcher Agent**: Gathers detailed information on a specified topic by looking it up on the internet using serper.
- **Writer Agent**: Writes a comprehensive and concise article based on the information provided by the Researcher.
- **Output**: Generates a markdown (.md) file with the article.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Python 3.7 or higher
- Git

### Installation

1. **Clone the repository**:

```bash
git clone https://github.com/ayushtiwari134/News_article_crewai.git
cd News_article_crewai
```

2. **Install the required dependencies**:
```bash
pip install -r requirements.txt
```

### Usage
1. **Configure the project**:

Before running the project, ensure you have configured the necessary API keys and environment variables for CrewAI and Gemini-1.5-Flash. You can set these in a .env file at the root of your project:
```plaintext
CREWAI_API_KEY=your_crewai_api_key
GEMINI_API_KEY=your_gemini_api_key
```
2. **Run the script**:

Use the following command to run the script and generate an article:
```bash
cd crew_news
python crew.py
```
### Acknowledgements
- <a href="https://www.crewai.com/">CrewAI</a> for the AI agent framework.
- Google's Gemini-1.5-Flash for the language model.
