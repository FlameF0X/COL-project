# COL-project
The COL-project is a Discord chatbot powered by Jupyter Google Colab and `microsoft/DialoGPT-large`.

## Setting Up the Bot:

1. Visit the [Discord Developer Portal](https://discord.com/developers/applications) and either select or create a new bot. In the `SETTINGS` section, go to `Bot` and enable the `Message Content Intent` option.
2. Retrieve your Discord bot token.
3. Use [Google Colab](https://colab.research.google.com/) to run the code.
4. Create a new `.ipynb` file (e.g., `name.ipynb`), or use the default naming convention.
5. In the first code cell, add the following pip command: `pip install discord.py transformers torch`.
6. Open the `COL-Script.ipynb` file and switch the view from `preview` to `code`. Alternatively, you can directly copy the script and paste it into the next code cell in your `.ipynb` file, after the `!pip install...` command.
7. Replace the following placeholders in the script:
   - `YOUR_DISCORD_BOT_TOKEN`: Your Discord bot token.
8. Run the first code cell to install the necessary dependencies (`discord.py`, `transformers` and `torch`). Once installation is complete, run the second cell to execute the main code.

## Important Note
Google Colab will automatically shut down your code after approximately 1.5 hours of inactivity. To avoid this, consider using Jupyter Notebook on a computer that runs continuously if you need long-term availability.

### ⚠ DO NOT REMOVE THE SOURCE CODE LINK: `source_code_link = "-# [Source Code - GitHub](<https://github.com/FlameF0X/COL-project>)"` ⚠

## How to use the bot in Discord:
Type !chat YOUR_QUESTION

## Check our discord server to help us on our journey: [COL-Project](https://discord.gg/YpkVyg2Reu)
