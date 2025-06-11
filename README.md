# Notes Bot 🤖📝

![Untitled-1](https://github.com/mishalshanavas/notes-bot/assets/70484516/cdd408dd-fae2-43e5-aa51-b6f61c8c0ffa)


# Notes Bot

An automated Instagram engagement tool that dynamically sets the current time as an Instagram Note to keep followers engaged.

## Features

- **Automated Notes**: Dynamically sets Instagram Notes with current time
- **Time-Based Content**: Notes display current time using clock emojis
- **Interactive Elements**: Includes engaging questions to boost follower engagement
- **Customizable Intervals**: Configurable update frequency
- **Authentication Management**: Handles Instagram login and session cookies automatically

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mishalshanavas/notes-bot
   cd notes-bot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

1. Open `main.py`
2. Set your Instagram credentials:
   ```python
   USERNAME = "your_username"
   PASSWORD = "your_password"
   ```
3. Customize the `BASE_MINUTE_INTERVAL` for note update frequency

## Usage

Run the bot:
```bash
python main.py
```

The bot will:
- Authenticate with Instagram (creates session cookies on first run)
- Automatically update your Instagram Note with the current time at configured intervals
- Display countdown timer for next note update

## Requirements

- Python 3.x
- instagrapi library
- Valid Instagram account

## Note

This project may require updates to maintain compatibility with Instagram API changes. Use responsibly and in accordance with Instagram's terms of service.
