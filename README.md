# Voting in Discord Bot using Python and Discord API

## Overview
This Python script enables a simple yet effective voting system within a Discord bot. By integrating with the Discord API, users can initiate and participate in votes directly within their Discord server channels. 

## Features
* Create and initiate votes using bot commands inside the server
* Real-time vote and updates
* Automatically tallies votes and displays results
  
## Technologies Used
* Python
* Discord API
   
## Installation
1. Clone or download the repository to your local machine.
2. Install the required dependencies
   ```bash
   pip install discord
4. Go to Discord Developer Portal, Sign in, Create App, and Generate your Token.
5. Configure the expired discord token in the **_config.json_** file and paste the new valid token.
6. Add the bot to your server:
  * Go to OAuth2 > URL Generator
  * Select the bot scope
  * Choose required permissions (e.g., Send Messages, Add Reactions)
  * Copy and open the generated URL in your browser
  * Invite the bot to your server
6. Run the **_main.py_** script.
