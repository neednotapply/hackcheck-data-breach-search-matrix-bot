# HackCheck - Data Breach Search - Matrix Bot

HackCheck is a Matrix bot that enables users to search for data breaches by various criteria such as email, password, username, and more. This bot utilizes the HackCheck.io API to fetch breach data and presents it interactively within Matrix servers.

## Features

- Search for breaches by email, password, username, full name, IP address, phone number, and hash.
- Interactive Matrix buttons and modals for seamless user experience.
- Detailed logging of bot activity.
- Output results in both CSV and PDF report formats.

## Download

You can download the latest version of the bot from the GitHub repository:

```bash
git clone https://github.com/RocketGod-git/hackcheck-data-breach-search-Matrix-bot.git
```

## Installation

Before running the bot, install the necessary Python packages directly using pip:

```bash
cd hackcheck-data-breach-search-Matrix-bot
pip install Matrix aiohttp aiolimiter reportlab
```

## Configuration

1. Update the `config.json` file with your Matrix bot token and HackCheck API key:

```json
{
    "Matrix_bot_token": "YOUR-TOKEN",
    "hackcheck_api_key": "YOUR-KEY",
    "webhook_url": "Matrix-WEBHOOK-FOR-LOGGING"
}
```

You'll have to figure out Matrix Developer Portal. I'm not teaching these things here.

## Usage

Run the bot:

```bash
python hackcheckbot.py
```

The bot will connect to Matrix, and you can start using it by invoking the slash command `/hackcheck` in your server.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with your suggested changes.

## License

See `LICENSE` for more information.

![RocketGod](https://github.com/RocketGod-git/Flipper_Zero/assets/57732082/f5d67cfd-585d-4b23-905f-37151e3d6a7d)
