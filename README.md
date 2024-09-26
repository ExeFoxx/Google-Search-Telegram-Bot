Google Search Telegram Bot
A Telegram bot built with Python and the aiogram library to perform Google searches and display the results.

License Python Version

# Features
* Interactive and user-friendly command-based interface.
* Supports both text and image searches.
* Pagination of search results.
* Cooldown mechanism to prevent spamming.
* Integration with the Google Custom Search API.

# Installation
1.  Clone the repository:

        git clone https://github.com/ExeFoxx/Google-Search-Telegram-Bot.git
      
2.  Navigate to the project directory:

        cd Google-Search-Telegram-Bot 

3. Install the required Python packages:

        pip install -r requirements.txt


# Usage

1.  Obtain a Telegram Bot token from the BotFather.

2.  Set your BOT_TOKEN, GOOGLE_API_KEY, and GOOGLE_CSE_ID as environment variables. You can use a .env file to manage these variables.

3.  Run the bot:

        python main.py

Configuration
RESULTS_PER_PAGE = 5 # Number of search results to display per page

user_cooldowns = {} # Dictionary to manage user cooldowns

admin_ids = [123456, 789012] # List of admin IDs who have access to certain commands

GOOGLE_API_KEY = os.getenv('GOOGLE_API_KEY') # Your Google API key GOOGLE_CSE_ID = os.getenv('GOOGLE_CSE_ID') # Your Google Custom Search Engine ID

📚 Usage
1. Start a chat with your bot on Telegram.
2. To search for text: /search <query>.
3. To search for images: /image <query>.
4. The bot will promptly display the results.
