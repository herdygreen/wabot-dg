# wabot-dg

Simple WhatsApp Bot

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/herdygreen/wabot-dg)

## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
apt install imagemagick -y
git clone https://github.com/herdygreen/wabot-dg
cd wabot-dg
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/herdygreen/wabot-dg
cd wabot-dg
npm install
npm update
```

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--self`

Activate self mode (Ignores other)

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://json-server.herdygreen.repl.co/`
Code: `https://repl.it/@herdygreen/json-server`

`node . --db 'https://json-server.herdygreen.repl.co/'`

The server should have like this specification

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--restrict`

Enables restricted plugins (which can lead your number to be **banned** if used too often)

* Group Administration `add, kick`

### `--img`

Enable image inspector through terminal

### `--autoread`

If enabled, all incoming messages will be marked as read

### `--nyimak`

No bot, just print received messages and add users to database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

<a href="https://api.xteam.xyz"><img src="https://i.ibb.co/7j0vtwz/xlogo.png" width="100" height="100"></a> | [![herdygreen](https://github.com/herdygreen.png?size=100)](https://github.com/herdygreen) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25) | [![Ftwrr](https://github.com/Ftwrr.png?size=100)](https://github.com/Ftwrr) 
----|----|----|----
[XTEAM](https://api.xteam.xyz/) | [herdygreen](https://github.com/herdygreen) | [Ariffb](https://github.com/ariffb25) | [Ftwrr](https://github.com/Ftwrr)
Powered by XTEAM | Author / Creator | Most Active Contributor | 2nd Most Active Contributor


NOTE: This project will not maintained after `27 June 2021`, that means no update. Feel free to anyone to continue this project :)