# MemeBotDiscord

A minimal Discord bot that sends a random meme/GIF when a user sends the `$meme` command in a channel.

Features
- Responds to `$meme` — sends a random meme/GIF (via the public Meme API).
- Responds to `$hello` — simple hello message for testing.
- Implemented in [bot.py](bot.py) using the [`get_meme`](bot.py) helper and the [`MyClient`](bot.py) Discord client.

Requirements
- Python 3.8+
- Packages: `discord` (discord.py or a maintained fork/version that supports message content intents) and `requests`.

Quick setup
1. Install dependencies:
   ```sh
   pip install discord.py requests
