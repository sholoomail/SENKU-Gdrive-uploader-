# Senku Google Drive Uploader Telegram Bot
**An asyncio Telegram bot to upload files from Telegram or Direct links to Google Drive.**
- Find it on Telegram as [ Senku Google Drive Uploader](https://t.me/senku_gdrive_bot)

## Features
- [X] Telegram files support.
- [X] Direct Links support.
- [X] Custom Upload Folder.
- [X] TeamDrive Support.
- [X] Clone/Copy Google Drive Files.

## ToDo 
- [ ] Handle more exceptions.
- [ ] LOGGER support.
- [ ] Service account support.

## Deploying

### Installation
- Clone this git repository.
```sh 
git clone https://github.com/Devilharsha/SENKU-Gdrive-uploader-
```
- Change Directory
```sh 
cd gdrive-uploader-telegram-bot
```
- Install requirements with pip3
```sh 
pip3 install -r requirements.txt
```

### Configuration
**There are two Ways for configuring this bot.**
- Add [APP_ID](https://my.telegram.org/apps), [API_HASH](https://my.telegram.org/apps), [BOT_TOKEN](https://t.me/BotFather), DATABASE_URL, ENV in Environment Variables.
- Add [APP_ID](https://my.telegram.org/apps), [API_HASH](https://my.telegram.org/apps), [BOT_TOKEN](https://t.me/BotFather), DATABASE_URL in [config.py](./config.py)

## Deploy 
- Deploy on VPS.
```sh 
python3 bot.py
```
## Deploy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Devilharsha/SENKU-Gdrive-uploader-)

- Note: Bot is in beta stage. Maybe it throw some errors.

## Credits
- [harsha](https://github.com/Devilharsha) owner
- [yeswi](https://GitHub.com/Yesawini12345) owner
- [Dan](https://github.com/delivrance) base
- [Spechide](https://github.com/Spechide) base
- [Shivam Jha](https://github.com/lzzy12) base
- [gdrive](https://github.com/cdfxscrq/GDrive-Uploader-TG-Bot)

