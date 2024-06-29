## 🛠️ Installation

1. Clone this repository:
   ```
   git clone https://github.com/Doriandarko/claude-engineer.git
   cd claude-engineer
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Add your Anthropic and Tavily API keys at the start of the file:
     ```python
     client = Anthropic(api_key="YOUR API KEY")
     tavily = TavilyClient(api_key="YOUR API KEY")
