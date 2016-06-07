# Hubot docker

hubot is a chat bot built on the [Hubot][hubot] framework. It was
initially generated by [generator-hubot][generator-hubot], and configured to be
deployed on [Heroku][heroku] to get you up and running as quick as possible.

## Configuration Env Variables

| Env variable | Example |
|:-------------|:------------|
| HUBOT_JANKY_URL | https://user:password@janky.example.com/_hubot/ |
| REDIS_URL | redis://passwd@192.168.0.1:16379/prefix |
| TELEGRAM_WEBHOOK | https://hubot.radiofx.co |
| TELEGRAM_TOKEN  | 221932505:*********************************** |
| HUBOT_RBAC_POWER_USERS | 51661165 |
| HUBOT_NAME | hubot |

Generate secret: `dd if=/dev/urandom bs=32 count=1 2>/dev/null | openssl base64`
