𝐉𝐨𝐡𝐧 𝐃𝐮𝐫𝐚𝐢𝐫𝐚𝐣 

𝚅𝚎𝚛𝚢 𝚂𝚎𝚖𝚙𝚒𝚕 𝙱𝚘𝚝 𝙰𝚞𝚝𝚘 𝙵𝚒𝚕𝚝𝚎𝚛 𝚋𝚘𝚝
![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=𝐉𝐨𝐡𝐧+𝐃𝐮𝐫𝐚𝐢𝐫𝐚𝐣;𝗖𝗿𝗲𝗮𝘁𝗲𝗱+𝗕𝘆+𝗔𝗟𝗕𝗜𝗡+𝗧𝗞𝗢)
</p>
# 𝙲𝙻𝙸𝙲𝙺 𝙱𝙴𝙻𝙾𝚆 𝙸𝙼𝙰𝙶𝙴 𝚃𝙾 𝙳𝙴𝙿𝙻𝙾𝚈 👇


[![Deploy](https://telegra.ph/file/02c798ec0f655dcc3dd95.jpg)](https://heroku.com/deploy?template=https://github.com/Samantha-a/DEVIL-V2)

- [x] Auto Filter
- [x] Manuel Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Fun mode
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel



<h3 align="center">ℂ𝕆ℕ𝕋𝔸ℂ𝕋<img align="center" src="[(https://telegra.ph/file/dc5fcbab5296f19468abc.mp4)]" height="33px" /></h3>
<p align="center">
<a href="https://t.me/albintko"><img alt="Telegram" src="https://img.shields.io/badge/𝙳𝙴𝚅 1-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="https://t.me/albintko"><img alt="Telegram" src="https://img.shields.io/badge/𝙳𝙴𝚅 2-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
</p>



## 𝙸𝚗𝚜𝚝𝚊𝚕𝚕𝚊𝚝𝚒𝚘𝚗

















## 𝙳𝙴𝙿𝙻𝙾𝚈 𝙾𝙽 𝙷𝙴𝚁𝙾𝙺𝚄
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Samantha-a/DEVIL-V3)

## 𝙳𝙴𝙿𝙻𝙾𝚈 𝙾𝙽 𝚁𝙰𝙸𝙻𝚆𝙰𝚈[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/ZwVmjm?referralCode=Duw4MO)

#Hard Way

```bash
# 𝙲𝚛𝚎𝚊𝚝𝚎 𝚟𝚒𝚛𝚝𝚞𝚊𝚕 𝚎𝚗𝚟𝚒𝚛𝚘𝚗𝚖𝚎𝚗𝚝
python3 -m venv env

# 𝙰𝚌𝚝𝚒𝚟𝚊𝚝𝚎 𝚟𝚒𝚛𝚝𝚞𝚊𝚕 𝚎𝚗𝚟𝚒𝚛𝚘𝚗𝚖𝚎𝚗𝚝
env\Scripts\activate.bat # For Windows
source env/bin/activate # For Linux or MacOS

# 𝙸𝚗𝚜𝚝𝚊𝚕𝚕 𝙿𝚊𝚌𝚔𝚊𝚐𝚎𝚜
pip3 install -r requirements.txt

# Edit info.py with variables as given below then run bot
python3 bot.py
```
Check [`sample_info.py`](sample_info.py) before editing [`info.py`](info.py) file

## 𝚅𝚊𝚛𝚒𝚊𝚋𝚕𝚎𝚜

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more

## Note
* Currently the [API used](http://www.omdbapi.com) in this repo is allowing 1000 requests per day. [You may not get posters if its crossed](https://t.me/ThankTelegram/910168). 
Once a poster is fetched from OMDB , poster is saved to DB to reduce duplicate requests.

## Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
index - Index all files from channel.
logger - Get log file
```

## Tips
* You can use `|` to separate query and file type while searching for specific type of file. For example: `Avengers | video`
* If you don't want to create a channel or group, use your chat ID / username as the channel ID. When you send a file to a bot, it will be saved in the database.



## Thanks to 
* [Pyrogram](https://github.com/pyrogram/pyrogram)
* Original [Repo](https://github.com/Lallu-lallus/ALPHA_IMDB_BOT)


## Support
Contact Me On [Telegram](https://t.me/Pro_editor_tg)

[Update Channel](https://t.me/Team_annaben)

## License
Code released under [The GNU General Public License](LICENSE)

𝙲𝚁𝙴𝙰𝚃𝙾𝚁

<a href="https://t.me/albintko"><img alt="𝙰𝙻𝙱𝙸𝙽 𝚃𝙺𝙾" src="https://img.shields.io/badge/𝙰𝙻𝙱𝙸𝙽 𝚃𝙺𝙾-2CA5E0?style=for-the-badge&logo=telegram&logoColor=red"/></a>

