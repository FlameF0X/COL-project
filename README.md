# COL-project (LLaMa API & OpenAI Client)
COL-project aka Colab LLaMa is a Discrod chatbot powered by Jupyter Notebook/Google Colab, OpenAI Client and LLaMa API.

# HOW TO SET UP THE BOT

1. Open https://discord.com/developers/applications , select / create a bot. In the ```SETTING```, go to ```Bod``` and enable ```Message Content Intent```.
2. Grab your discord bot token.
4. Use Jupyter Notebook (You have to install it.) or Google Colab (https://colab.research.google.com/) to run the code.
5. Create a ```.ipynb``` file like ```name.ipynb``` or just leave like a ```.ipynb```.
6. Add in the first code section the pip command ```!pip install discord.py transformers nest_asyncio openai```.
7. Then go to ```COL-Script.ipynb``` and set the view from ```preview``` to ```code``` or just copy it directly and then add it under the ```!pip install...``` add another code section, there is going to be the place where you add the ```COL-Script.ipynb``` script.
8. Replace the ```<YOUR_DISCORD_TOKEN>``` with your own discord bot token, ```<YOUR_LLAMA_API_KEY>``` with your own LLaMa API (To get your LLaMa API go to https://console.llama-api.com/account/api-token, create a account and grab your API), ```<YOUR_SERVER_ID>```with your discord server ID, ```<YOUR_CHANNEL_ID>``` with the ID of the channel where you want othe bot to work only and ```<YOUR_CHANNEL_LINK>``` to show where the bot can be use in case of someone using it outsite of your seated cahnnel. 
9. To run the  ```.ipynb``` run the first code section to install ```discord.py transformers nest_asyncio openai```, wait for everything to be installed and thne run the second section where the main code is.

# IMPORTANT NOTE:
Google Colab shuts your code down after ~1.5 hours after you leave the tab. So if you have a laptop/pc that runs 24/7, use Jupyter.
