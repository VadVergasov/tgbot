Telegram Bot Template
======

Template repository for creating Telegram Bots with template for systemd services and basic requirements.txt.

Install
------

Clone repository, install requirements:
```
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```
Write code of your bot, prepare systemd(service) files using templates and copy them to systemd directory
Enable service:
```
sudo systemctl daemon-reload
sudo systemctl enable bot.service
```
