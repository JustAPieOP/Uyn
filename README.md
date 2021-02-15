![Uyn logo](https://i.imgur.com/1UHPT0e.png)

# [Invite this BOT](https://discord.com/oauth2/authorize?client_id=770981744165519390&scope=bot&permissions=271707254)

<span style="color:#ba3f38">This BOT is still in development so it still lacks many important features. I will add more later so please sympathize for me.</span>

# Welcome to the GitHub Source Code page of the Uyn BOT!

"Uyn" is a BOT that does many miscellaneous things like fun things, moderation things, and so on.

## How to run this BOT yourself?

* **Step 1:** Download [UynServer](https://www.github.com/LilShieru/UynServer) and config the PHP and the MySQL server.
* **Step 2:** Download the Uyn source code.
* **Step 3:** Configure the BOT prefix in the `config.json` file.
* **Step 4:** Config the Environment Variables: `BOT_TOKEN` with your BOT token, `php_server_url` with the URL of your PHP server, `php_server_token` with the token you configured in your PHP server, and `tenor_api_key` with your Tenor API Key.
* **Step 5:** Install the dependencies with the `npm install` command. You needn't to do it if you're using Heroku.
* **Step 6:** Run the BOT with the `node index.js` command. If you're in Heroku, make sure that you've enabled the `web` dyno in the `Resources` tab. If you prefer the `worker` dyno, change the `web: node index.js` into `worker: node index.js` in the `Procfile` file.
* **Step 7:** ENJOY!!! xD

By the way, I'm currently using THIS repository to deploy the code into my Heroku BOT app, so you don't worry about the vulnerability :D

![Uyn repo screenshot](https://i.ibb.co/pbfbtGv/Screenshot-20210215-163514-2.png)

## List of commands

You can use the `u!help (command)` command to get information about a specific command!

### 👥 User information:

account, avatar, developer, owner

### 😊 Just for fun:

arrest, cert, coffindance, covid19, gay, img, les, lolicon, number, poll, quote, reverse, roll, say, trap, trash

### 👋 Interactions:

baka, bite, boop, bully, cry, dance, greet, grin, highfive, hold, hug, hungry, kill, kiss, lewd, lick, love, muda, nom, pat, poke, pout, punch, shrug, slap, sleep, smile, smug, snuggle, stare, thinking, thumbsup, tickle, wag, wait, wave

### ⚙️ Moderations:

ban, kick, mute, setnickname, unmute, warn

### 🚩 Server information:

channels, guild, role

### 📜 Roles managing:

createrole, giverole, setcolor, setname, takerole

### 💬 Ping-responsing:

deletequote, setquote, showquote

<span style="color:#ba3f38">This ping-responsing message will only be sent if the pinging message meets these requirements:</span>

 * The mentioned user has set the ping-responsing message by the setquote command

 * There's only one user mention in the message

 * The message content length is less than 125

 * The message author isn't a BOT

 * The message channel isn't a BOT channel (doesn't have the "bot" word in the channel name)

 * The time that the message was sent isn't between 8 PM and 12 PM (UTC).

<span style="color:#ba3f38">This responsing message will be deleted in 5 seconds. Also, it only send 1 ping-responsing message each 1 minute. If the 1-minute timer isn't up, it will react the ❌ emoji, and then unreact it in the next 2 seconds.</span>

I will add the ping-responsing toggle command for each server in the future.

### 🤖 BOT information:

invite, ping, stats

### 👋 Config:

prefix

## More informations about this BOT

This BOT is being ran using Heroku, Node.JS, PHP and MySQL. I made it without any cost so I am not sure about the BOT security very much.

[Invite this BOT](https://discord.com/oauth2/authorize?client_id=770981744165519390&scope=bot&permissions=271707254)

[Support Server](https://discord.gg/v9c27j9CQ6)

## Developer information

You can contact the developer by using these social networks:

Discord: Nico Levianth#6958

[Facebook](https://www.facebook.com/Yonaka12)

[Twitter](https://www.twitter.com/reallynotciel) (now inactive)

[Instagram](https://www.instagram.com/reallynotciel)

[GitHub](https://www.github.com/LilShieru)

[YouTube](https://www.youtube.com/c/yutorimegami)
