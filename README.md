# GPT-3.5 Research Assistant 🧠

Leverage the power of OpenAI's GPT-3.5, Browserless, Beautiful Soup 4, Serper API, Streamlit, and LangChain to conduct in-depth research on any given topic. Dive deep into a sea of information, and come out with valuable insights!

## Features

- **GPT-3.5 Integration**: Uses OpenAI's model for natural language understanding and generation.
- **Browser Automation**: With Browserless, perform actions just like you would in a real browser.
- **Web Scraping**: Beautiful Soup 4 extracts crucial information from web pages.
- **Search Engine API**: Serper API to fetch relevant websites for any given query.
- **Language Translation**: LangChain aids in translating content for diverse language support.
- **Streamlit**: to provide live feedback from the console into the browser as the app functions are running.

## Setup & Installation

1. **Clone the Repository**:
```bash
git clone https://github.com/timbeaulac/ai-researcher.git
cd ai-researcher
```

2. **Create a Python Virtual Environment** (recommended):
```bash
python -m venv venv
```

3. **Activate Virtual Environment**:
```bash
source venv/bin/activate
```

4. **Install Dependencies**:
```bash
pip install -r requirements.txt
```

5. **Create Environment File**:
```bash
touch .env
vi .env
```

6. **Add API Keys to '.env' File**:
```bash
OPENAI_API_KEY = "YOUR_OPENAI_KEY"
SERP_API_KEY = "YOUR_SERPER_KEY"
BROWSERLESS_API_KEY = "YOUR_LANGCHAIN_KEY"
```

## Usage

1. **Run the Assistant**:
```bash
streamlit run app.py
```

The tool will scrape relevant web pages, analyze content, and provide a comprehensive summary on the given topic.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## Credits

Powered by OpenAI, Browserless, Beautiful Soup 4, Serper API, Streamlit, and LangChain.
