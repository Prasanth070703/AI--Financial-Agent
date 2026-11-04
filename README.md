# Financial Agent with Phidata

This project is a multi-agent AI system that helps users understand the stock market by combining financial data with the latest information available on the web.

I built this project to explore how AI agents can simplify financial research. Instead of manually checking stock prices, company fundamentals, analyst opinions, and market news across different platforms, the system brings everything together in one place.

## How It Works

The project uses two AI agents that work together:

- **Web Search Agent:** Searches the web using DuckDuckGo to find relevant market news and information.
- **Financial Agent:** Uses Yahoo Finance (`yfinance`) to retrieve stock prices, company fundamentals, analyst recommendations, and financial news.

Together, these agents provide a more complete picture of a company and its market performance.

## Key Features

- **Stock Analysis:** Get financial information and key fundamentals for a company.
- **Analyst Recommendations:** Understand what market analysts think about a particular stock.
- **Latest Market News:** Find recent news and updates related to companies.
- **Multi-Agent Collaboration:** Combines web research and financial data to generate useful insights.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/financial-agent-with-phidata.git
cd financial-agent-with-phidata
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

```bash
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API credentials

Create a `.env` file in the project directory and add your API key:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 5. Run the project

Run the main Python file:

```bash
python main.py
```

## Technologies Used

- Python
- Phidata
- OpenAI API
- Yahoo Finance (`yfinance`)
- DuckDuckGo Search
- Python Dotenv
- FastAPI (optional)
- Uvicorn (optional)

## What I Learned

Working on this project helped me understand how multiple AI agents can collaborate, use external tools, retrieve financial information, and turn that information into meaningful insights.

It also gave me practical exposure to building AI-powered applications in the financial services domain.
