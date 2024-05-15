# Mood-To-Music-Discord-Bot

Mood-To-Music-Discord-Bot is a Discord bot that uses the Spotify API and machine learning to recommend songs based on the user's mood. Enhance your Discord experience by getting personalized music recommendations that match your current mood or activity.

## Features

- **Mood-based Music Recommendations**: Get song recommendations based on your current mood.
- **Spotify Integration**: Utilizes the Spotify API to fetch song data.
- **Easy to Use**: Simple commands to interact with the bot.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/bramsubic/Mood-To-Music-Discord-Bot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Mood-To-Music-Discord-Bot
    ```
3. Set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Set up your environment variables:
    - Create a `.env` file in the project root with your Discord bot token and Spotify API credentials.

    ```env
    DISCORD_TOKEN=your_discord_bot_token
    SPOTIFY_CLIENT_ID=your_spotify_client_id
    SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
    ```

## Usage

1. Run the bot:
    ```bash
    python bot.py
    ```

2. Invite the bot to your Discord server using the OAuth2 URL.

## Commands

- `!mood <mood>`: Get a song recommendation based on the specified mood.
- `!help`: Display a list of available commands.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request.
