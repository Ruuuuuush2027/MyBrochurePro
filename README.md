## MyBrochureBro
Utilizes LLM API to build a product that could create Brochure for a company to be used for prospective clients, investors and potential recruits.

### main technical features
1. for using local ollama: serving in windows WSL, configure corresponding environment if needed (open ports, expand, etc.)
2. uses Selenium for scraping dynamic web
3. OpenAI api with gpt-mini, with beta completions api integrated with pydantic for structured output enforcement
4. In-notebook application
5. Uses openai response streaming api and update_display to return results in real time to improve user experience and interactivity