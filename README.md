# Telegram-Notify

![Build](https://github.com/rexdivakar/Telegram-Notifly/workflows/Python%20application/badge.svg)
![Upload Python Package](https://github.com/rexdivakar/Telegram-Notifly/workflows/Upload%20Python%20Package/badge.svg)

![GitHub issues](https://img.shields.io/github/issues-raw/rexdivakar/telegram-notifly?logo=github&style=for-the-badge)
![Discord](https://img.shields.io/discord/760088481224851476?label=DISCORD&logo=discord&logoColor=green&style=for-the-badge)
![PyPI](https://img.shields.io/pypi/v/notifly?logo=github&style=for-the-badge)
![PyPI - Downloads](https://img.shields.io/pypi/dm/notifly?color=green&style=for-the-badge&logo=github)


<p align="center">
<img src="others\bot.png" width="200" alt="Logo">

# what is the purpose of this bot ?

This bot was created to push notifications during an event trigger !!
*Stay tuned for library updates*

## How to install and get started 

Termux :
pkg install python3 
pip3 install notifly

Ubuntu/Debian
sudo apt install python3-pip
pip3 install notifly

Arch

sudo pacman -S python3-pip
pip3 install notifly

# Be aware this may take a while depending on your network speed

# Documentation
from telegram import notifly

bot=notifly.BotHandler('BOT TOKEN')

bot.send_message('your message')

