# Web2Bot

Web2Bot is a chatbot that scrapes a company's website, creates a knowledge graph, and uses GPT-3.5 to provide chat support on Telegram. It can answer any question about the company that can be found on the website it scraped.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Scrape a company's website to gather information
- Create a knowledge graph from the scraped data
- Integrate GPT-3.5 to create a chatbot using the knowledge graph
- Connect the chatbot to a Telegram bot for chat support

## Requirements

- Python 3.x
- Beautiful Soup or Scrapy (for web scraping)
- Neo4j or another graph database (for storing the knowledge graph)
- OpenAI API key (for GPT-3.5 integration)
- python-telegram-bot library (for Telegram bot integration)

## Installation

1. Clone the repository:
git clone https://github.com/mmshooreshi/web2bot.git
cd web2bot
Copy


2. Install the required dependencies:
pip install -r requirements.txt
Copy


3. Set up your environment variables:
export OPENAI_API_KEY="your_openai_api_key"
export TELEGRAM_BOT_TOKEN="your_telegram_bot_token"
Copy


## Usage

1. Run the web scraper to gather information from the company's website:
python scraper.py --url "https://example.com"
Copy


2. Create the knowledge graph from the scraped data:
python create_knowledge_graph.py
Copy


3. Start the Telegram bot:
python telegram_bot.py
Copy


4. Interact with the chatbot on Telegram by sending messages to your bot.

## Contributing

1. Fork the repository on GitHub.
2. Create a new branch for your changes.
3. Commit your changes and push them to your fork.
4. Create a pull request to merge your changes into the main repository.

## License

This project is licensed under the [MIT License](LICENSE).