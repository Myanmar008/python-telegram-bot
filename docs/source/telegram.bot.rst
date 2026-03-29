$ pip install pyTelegramBotAPI

import telebot

bot = "8263109474:AAFcN9QE-LeunSDcSfGhBUiVckNxff-30Pk", parse_mode=default)@bot.message_handler(commands=['start', 'help'])

@bot.message_handler(commands=['start', 'run'])
def send_welcome(message):
	bot.reply_to(message, "Started Running")
