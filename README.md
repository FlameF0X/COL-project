# COL-project LLaMa

The COL-project LLaMa is an open-source Discord chatbot powered by LLaMa API and Notebook/Python.

## Setting Up the Bot

1. **Create a Discord Bot**
   - Visit the [Discord Developer Portal](https://discord.com/developers/applications).
   - Select or create a new application.
   - In the `SETTINGS` section, go to `Bot` and enable the `Message Content Intent` option.
   - Retrieve your Discord bot token.

2. **Create a LLaMa API account**
   - Visit the [LLaMa API](https://console.llama-api.com/).
   - Create a account.
   - Create a API key.

4. **Prepare Your Environment**
   - Use either [Jupyter Notebook](https://jupyter.org/install) or [Google Colab](https://colab.research.google.com/) to run the code.

5. **Set Up the Project**
   - Create a new `.ipynb` file (e.g., `name.ipynb`) or use the provided file.
   - In the first code cell, add and run the following pip command:
     ```python
     !pip install discord.py llamaapi
     ```
   - Open the `COL-Script.ipynb` file and switch the view from `preview` to `code`. Alternatively, copy the script from `COL-Script.ipynb` and paste it into the next code cell in your `.ipynb` file, after the `!pip install` command.

4. **Configure the Bot**
   - Replace the placeholder `<YOUR_DISCORD_TOKEN>` in the script with your Discord bot token.
   - Replace the placeholder `<YOUR_LLaMa_API_KEY>` in the script with your LLaMa API key.

5. **Run the Code**
   - Run the first code cell to install the necessary dependencies. Once installation is complete, run the second cell to execute the main code.

## Important Note

Google Colab will automatically shut down your code after approximately 1.5 hours of inactivity. For long-term availability, consider using Jupyter Notebook on a continuously running computer.

## How to Use the Bot

In Discord, type `@BOT_NAME YOUR_QUESTION` to interact with the bot.

## Community

Join our [Discord server](https://discord.gg/YpkVyg2Reu) to collaborate and support the project.
