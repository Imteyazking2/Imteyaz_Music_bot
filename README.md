# Imteyaz_Music_bot
from pyrogram import Client as Bot

from tgcalls import run
from config import API_ID, API_HASH, BOT_TOKEN


bot = Bot(@Imteyaz_ROBOT
    ":memory:",64
    API_ID,2483152
    API_HASH,6b0cca767a188ac5fa032665b67e4773
    bot_token=BOT_TOKEN,1769776517:AAF258aZ87WRB23PbDsfvjyoncQh735n5IE
    plugins=dict(root="handlers")
)

bot.start()
run()
