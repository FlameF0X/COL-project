# COL-project (LLaMa API & OpenAI Client)
The COL-project, also known as Colab LLaMa, is a Discord chatbot powered by Jupyter Notebook/Google Colab, the OpenAI Client, and the LLaMa API.

## Setting Up the Bot

1. Visit the [Discord Developer Portal](https://discord.com/developers/applications) and either select or create a new bot. In the `SETTINGS` section, go to `Bot` and enable the `Message Content Intent` option.
2. Retrieve your Discord bot token.
3. Use either [Jupyter Notebook](https://jupyter.org/install) (you'll need to install it) or [Google Colab](https://colab.research.google.com/) to run the code.
4. Create a new `.ipynb` file (e.g., `name.ipynb`), or use the default naming convention.
5. In the first code cell, add the following pip command: `!pip install discord.py transformers nest_asyncio openai`.
6. Open the `COL-Script.ipynb` file and switch the view from `preview` to `code`. Alternatively, you can directly copy the script and paste it into the next code cell in your `.ipynb` file, after the `!pip install...` command.
7. Replace the following placeholders in the script:
   - `<YOUR_DISCORD_TOKEN>`: Your Discord bot token.
   - `<YOUR_LLAMA_API_KEY>`: Your LLaMa API key. You can obtain this by creating an account at [LLaMa API Console](https://console.llama-api.com/account/api-token) and generating an API token.
8. Run the first code cell to install the necessary dependencies (`discord.py`, `transformers`, `nest_asyncio`, and `openai`). Once installation is complete, run the second cell to execute the main code.

## Important Note
Google Colab will automatically shut down your code after approximately 1.5 hours of inactivity. To avoid this, consider using Jupyter Notebook on a computer that runs continuously if you need long-term availability.
