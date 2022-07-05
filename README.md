# Encourage Bot
The encouraging Discord bot

## Usage
**Setup**
* Paste the following link into your web browser and select a server to invite the bot: 
  ``` sh
  https://discord.com/api/oauth2/authorize?client_id=891924875080503306&permissions=519232&scope=bot
  ```
* Note: You can only add bots if you are the server owner or have "Manage Server" privileges.

**Bot Commands**
- Get a random inspiring message from the ZenQuotes.io API
  ``` sh
  $inspire
  ```
- Add a new encouraging message to the database (in response to the trigger words: "sad", "depress", "disappoint", and "upset")
  ``` sh
  $new [message]
  ```
- Remove a user-created encouraging message (in response to the trigger words)
  ``` sh
  $del [number]
  ```
- Get a list of user-created inspiring messages currently in the database
  ``` sh
  $list
  ```
