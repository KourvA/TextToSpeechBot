<p>
  <img align="left" src="https://user-images.githubusercontent.com/118578799/218861497-1cea9c68-dba7-4ac0-9834-4191070aeaf6.png" width=200 heigth=200/>
  <h1> TextToSpeechBot </h1>
  <p> Text To Speech Telegram Bot with Brian voice that converts all your messages into voice.</p>
  <p> It uses <a href="streamelements.com">streamelements</a> API for TTS. </p>
</p>
<br>

# Installation
+ clone
```bash
git clone https://github.com/Kourva/TextToSpeechBot && cd TextToSpeechBot
```
+ requirements
```bash
pip install -r requirements.txt
```
+ run
```bash
python3 bot.py
```

# Config
###### You need to open **token.env** file and put your Token inside the file.
###### You can get one from [Bot father](https://t.me/botfather).
```python
bot_token=your-bot-token-here
```

# Note (**Fixed**)
###### This bot will not works on groups (It will send the voice to your private message).
###### The reason is that i wrote `user.usrid` when sending voice. so it will send it to user chat-ID, not other chat-ID's
###### For fixing this. just change `user.usrid` to `message.chat.id`
###### Update: Fixed! now bot can send voices to groups.


# Thanks
###### Start the bot and enjoy - Dont forget to star :)
