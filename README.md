# Stella's Control Center  // [@stellaSysbot](https://t.me/stellasysbot)
>is a telegram bot that uses Heroku API and helps manage heroku app from telegram.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Available commands
* `/start:` for start message.
* `/help:` for get this message.
* `/admins:` get user ID's list of who have power over me.
* `/restart:` to restart @MissStella_bot.
* `/dynos:` to check Stella's dyno usage.
* `/log:` get latest console log in .txt

## Available veriables 
* `BOT_TOKEN`: Your bot token.
* `SUDO_USERS`: List of id's -  (not usernames) for users. eg. `[604968079, 802002142]`
* `SUPPORT_USERS`: List of id's (not usernames) for users which are allowed to do almost everything except using some sudo and owner only commands like `/restart`.
* `TG_CHARACTER_LIMIT`: keep default value.
* `HEROKU_API_KEY`: You heroku api key get it from [here](https://dashboard.heroku.com/account)
* `HEROKU_APP_NAME`: Your created heroku app name, which heroku app that you want to manage.


