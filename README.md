# **Daily Image Discord Bot**

<p align="center">
   <a href="https://discord.com/oauth2/authorize?client_id=806274731245436960&permissions=3072&scope=bot">
     <img width="150" height="150"src="https://i.imgur.com/gZgo0no.png">
   </a>

  <br>
  <a href="https://github.com/Josee9988/Daily-image-discord-bot/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/Josee9988/Daily-image-discord-bot?color=0088ff&style=for-the-badge&logo=github" />
  </a>
  <a href="https://github.com/josee9988/Daily-image-discord-bot/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/Josee9988/Daily-image-discord-bot?color=0088ff&style=for-the-badge&logo=github" />
  </a>
  <a href="https://top.gg/bot/806274731245436960">
    <img src="https://img.shields.io/badge/upvote%20-dimg-blue?logo=github-sponsors&style=for-the-badge&color=red">
  </a>

</p>

A simple bot that let you send **daily random images** from any *public google photos album*
. **[🤖](https://discord.com/oauth2/authorize?client_id=806274731245436960&scope=bot&permissions=52224)**
This bot was made for fun purposes, "*dimg*" does **not** collect unnecessary data or sell anything to third parties.
Feel safe🛡️.

**⚠️DISCLAIMER:** The bot could not be installed anymore on more than 100 servers. The discord staff claimed that: "*it's clear that you joined a number of servers inorganically in order to grow your bot and qualify for verification. Therefore, we cannot verify your bot*" so I decided to leave it as is, and stop its development until the discord team decides to change its mind, because, obviously that what they are claiming is completely wrong and inaccurate⚠️.

---

## **Installation** 🚥

1. **[Add the bot to your server🤖](https://discord.com/oauth2/authorize?client_id=806274731245436960&scope=bot&permissions=52224)**
2. Make sure the bot has permissions to write in the channel you selected or on the channel you are using to talk with
   the bot.
3. The only users that are allowed to use the installation commands are the **users** with **admin permissions**.
4. Use `!dimg channel nameOfYourChannel` to specify the channel where **dimg** will post the photos.
5. Use `!dimg albumlink linkOfYourPublicGooglePhotosAlbum` to let the bot know where to find your photos.
6. Enjoy. Every 12 hours a new random photo from your public GPhotos album will suddenly appear in your desired channel!

---

## **Commands** 🔬

*Daily Image Discord Bot* uses the **prefix** **`!dimg`**, so each command must be preceded by that prefix.

1. **`help`** -> Displays the command list and the prefix.
2. **`channel <nameOfYourChannel>`** -> This command tells the bot where to send the images. Make sure the bot has
   access and write permissions in that channel tho.
3. **`albumlink <linkOfYourPublicGooglePhotosAlbum>`** ->  This command tells the bot the link of your public Google
   Photos album.
4. **`now`** -> If `channel` and `albumlink` are set, and you are typing the message from the specified channel, then it
   will force a photo to appear just now (it will not break the cron schedule, just forces an extra photo to appear now)
5. **`sendmsg`** -> The message that will be sent when the image is sent.
6. **`info`** -> Useful links (documentation/ owner contact).
7. **`ping`** -> Displays bot latency and API latency.
8. **`pong`** -> Replies ping🤪.

- The commands `!dimg channel`, `!dimg albumlink` and `!dimg now` can only be executed by the server administrators (to
  avoid server trolls).

---

## **Built with** 🛠️🔧

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Discord.js](https://discord.js.org/#/)
- [Heroku](https://heroku.com/)

---

<p align="center">
   <a href="https://top.gg/bot/806274731245436960">
       <img src="https://top.gg/api/widget/806274731245436960.svg" alt="Daily Image Bot" />
   </a>
</p>

_Made with a lot of ❤️❤️ by **[@Josee9988](https://github.com/Josee9988)**_
