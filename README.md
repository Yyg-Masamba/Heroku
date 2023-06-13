**Important Note**

**UPLOAD ANYTHING HERE: Accounts, Token, Button, Terabox, rcl.conf, shorteners.txt, etc**





**Mandatory Veriables in Config**

- `UPSTREAM_REPO`: Your github repository link, if your repo is private add `https://GitHubusername:git_token@github.com/GitHubusername/reponame
recommended).
- `UPSTREAM_BRANCH`: Upstream branch for update. Default is `zh_run`. `Str`

- `BOT_TOKEN`: The Telegram Bot Token that you got from [BotFather](https://t.me/BotFather). `Str`
- `OWNER_ID`: The Telegram User ID (not username) of the Owner of the bot. `Int`
- `TELEGRAM_API`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from <https://my.telegram.org>. `Int`
- `TELEGRAM_HASH`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from <https://my.telegram.org>. `Str`

- `BASE_URL`: Valid BASE URL where the bot is deployed to use torrent web files selection. Format of URL should be `https://app-name.herokuapp.com/`, where `app-name` is the name of your heroku app. `Str`
- `TORRENT_TIMEOUT`: Timeout of dead torrents downloading with qBittorrent and Aria2c in seconds. `Int`

------

## DO NOT UPLOAD ANYTHING HERE

