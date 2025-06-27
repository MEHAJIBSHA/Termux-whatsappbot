### (Termux WhatsApp Bot)


<p align="center">
<img src="https://d.top4top.io/p_1837luigd0.gif" alt="GIF" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="X BOT" src="https://img.shields.io/badge/Dark-Bot-blue?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/MEHAJIBSHA"><img title="Author" src="https://img.shields.io/badge/Author-MrDevils-orange.svg?style=for-the-badge&logo=github"></a>
<p align="center">
<a href="RAVANA-SL/Termux-whatsappbot"><img title="Author" src="https://img.shields.io/badge/Author-MrDevils-orange.svg?style=for-the-badge&logo=github"></a>
</p>





### (Install Termux)
 
 
````bash
pkg update
pkg upgrade
pkg install git -y
pkg install nodejs -y
pkg install ffmpeg -y
pkg install imagemagick -y 
````


 ### (Install The Dependencies)

 
````bash
git clone https://github.com/MEHAJIBSHA/Termux-whatsappbot
cd Termux-whatsappbot
npm install
````

````bash
node .
````* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Nurutomo/wabot-aq
cd wabot-aq
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

### `--pconly`

If that chat not from private bot, bot will ignore

### `--gconly`

If that chat not from group, bot will ignore

### `--swonly`

If that chat not from status, bot will ignore

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

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

<a href="https://api.xteam.xyz"><img src="https://i.ibb.co/7j0vtwz/xlogo.png" width="100" height="100"></a> | [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25) | [![Ftwrr](https://github.com/Ftwrr.png?size=100)](https://github.com/Ftwrr) 
----|----|----|----
[XTEAM](https://api.xteam.xyz/) | [Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25) | [Ftwrr](https://github.com/Ftwrr)
Powered by XTEAM | Author / Creator | Most Active Contributor | 2nd Most Active Contributor


NOTE: This project will not maintained after `27 June 2021`, that means no update. Feel free to anyone to continue this project :)
