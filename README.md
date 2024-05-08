<h1>MTX-BOT🤖<sub><sub>v1.7.2🚀</sub><br><sub><sub><h6>- A Simple MTX-BOT for starting a Messenger chatbot.</h6></sub></sub></sub></h1>

<img align="center" src="https://i.postimg.cc/8kKq5btw/images-2.jpg"></a>

<h3>About</h3>

Hello there! Thank you for using MTX-BOT! Join us at [MrTomXxX Helping Zone](https://www.facebook.com/groups/tomxxx)🍪 if you wish to share and discover Mirai/MTX-BOT commands created by other command creators!


### Highlighted Feature
```js
  const { messageID } = await box.reply(`Hello!`);
  setTimeout(() => {
    box.edit(`5 seconds later..`, measageID);
  }, 5000);
```
  

<details>
  <summary>What's New?</summary>

### UPDATE!
  - New Box Feature for sending response using the bot.
  - New Env Credentials feature to hide your credentials.
</details>

<details>
  <summary>Languages</summary>
  
> - en = English-US 
> - vi = Vietnamese 
> - tl = Tagalog 
> - cb = Bisaya/Cebuano
> - bd = Bengali 
> - ar = Arabic

Go to your config.json and set it in the language property:
```json
{
  "language": "en",
}
```

Looking for a French language translation done by a local French! Your contribution would be greatly appreciated, and credits will be provided!
</details>

<details>
  <summary>Appstate Encryption</summary>
  
  Are you having an issue about getting your account stolen or hacked? This might due to your appstate provided which is stolen by other users. If you feel unsecure, try setting up *"encryptSt"* to *true* in the **config.json**.
  
  ```json
  {
    "encrpytSt": true
  }
  ```

  Encrypting won't affect the bot process and will only make the appstate harder to be used by thiefs and hackers. Furthermore, it may get laggy when opening the appstate.json after being encrypted but still it is worth a shot.
  
</details>

---
### Render Hosting
__=>__ Host your botfile on [render.com](https://dashboard.render.com) to make your file always active.
- If you have some issues related to render hosting! Try our newly created facebook group with render hosting discussions!
- Im currently looking for companions and conversation starters who have some knowledge about hosting in render to become moderators.
- Feel free to join us at [Render Community](https://www.facebook.com/groups/7389392131128817/?ref=share) on Facebook! See you there!
[<img align="center" src="https://i.ibb.co/DMXyLm3/Picsart-24-02-14-12-25-06-014.jpg">](https://www.facebook.com/groups/tomxxx)
</h1>

---

- Welcome to the [MTX-BOT](https://github.com/MrT0mX/MTX-BOT)🌀 repository. This project is an unofficial bot file from the [Mirai](https://github.com/m1raibot/miraiv2) Repository, initially developed and maintained by [Free Bot](https://github.com/MrT0mX/Free-Bot), better known as [MrTomXxX](https://github.com/MrT0mX). The base file for this project is sourced from the [Free-Bot](https://github.com/MrT0mX/Free-Bot.git) GitHub project.

- [MTX-BOT](https://github.com/MrT0mX/MTX-BOT)🌀 is a modified messenger bot file by [MrTomXxX](https://replit.com/Cat0Tom)🇵🇭. It is a refined version of the Mirai messenger bot, with some unique enhancements. 

- A key feature is the `usePrefix` function integrated within every command. This function removes the need for prefixes, providing a more streamlined user experience. Alongside ready-made commands and free-to-edit codes, this bot file encourages users to learn and explore freely.
<img align="center" src="https://i.postimg.cc/1RqMhqB7/Capture.png"/>

- Further, [MTX-BOT](https://github.com/MrT0mX/MTX-BOT)🌀 comes with a user-friendly feature that allows easy customization of your console design via the `theme` option in the config.json file. This makes it highly accessible, especially for beginners.
<img align="center" src="https://i.postimg.cc/NMmv3nSd/1690528355723-removebg-preview.png"/>

<details>
  <summary>Available Themes</summary>
  
> - Blue
> - Aqua
> - Fiery
> - Orange
> - Pink
> - Red
> - Retro
> - Sunlight
> - Teen
> - Summer
> - Flower
> - Ghost
> - Purple
> - Rainbow
> - Hacker

Go to your `config.json` and set it in the language property:
```json
{
  "DESIGN": {
    "Title": "MTX-BOT",
    "Theme": "Blue",
    "Admin": "YOUR_NAME"
  }
}
```
</details>

- Embrace the world of possibilities with [MTX-BOT](https://github.com/MrT0mX/MTX-BOT)🌀 - a facebook Messenger file designed to make your interaction with messenger bots smoother and more efficient.
---
<div align="center">
      <h3>My Replit Account:
      <a href="https://replit.com/Cat0Tom" style="color: green;"><br>MrTomXxX🔥</a>
        <br>
        My Facebook Account:<a href="https://www.facebook.com/MrTomXxX" style="color: green;"><br>Ratul Hassan🚀</a></h3></div>

- If you encounter any issues or have questions related to this REPL, please don't hesitate to reach out to me on Facebook. I'm here to assist you!

<img align="center" src="https://i.ibb.co/xCzgpG6/Snapchat-1365555982.jpg"/>

### **How to Start Using MTX-BOT?**

1. Begin by navigating to [Replit](https://replit.com).
2. Log in to your existing account or sign up for a new one.
3. Utilize the search bar to find [MTX-BOT](https://github.com/MrT0mX/MTX-BOT).
4. Click on `templates`.
5. Upon searching, select the most popular MTX-BOT template from the results.
6. Afterwards, click `Use Template`.
7. After forking the template, setup your PREFIX, BOTNAME and other properties in your `config.json`.
8. Open your `Facebook Account` that you want to turn into a chatbot.
9. After logging in, get your appstate using [C3C fbstate](https://github.com/c3cbot/c3c-fbstate/archive/refs/tags/1.5.zip) extension.
10. Copy the appstate, return to the repository, and paste it into your appstate.json.
11. Now, run it, and there you have your bot!

> [!WARNING]
> *There is a risk of your account being banned after running the code, so please ensure proper account management and handling. If it happens, please try logging in again and retrieve your app state.*

### Another simple login method:
1. Go to config.json and put your email and password.
   ```json
   {
     "email": "<sample@gmail.com",
     "password": "<fb_password>",
     "useEnvForCredentials": false
   }
   ```
   Or use process.env keys if you have configured a secret.
   ```json
   {
     "email": "exampleEmailKey",
     "password": "examplePassKey",
     "useEnvForCredentials" true
   }
   ```
3. Run your file and you have your bot!

> [!WARNING]
> *It's up to you if you want to login using your facebook credentials. Make sure your file is private and cannot be easily stolen. Any issues about having your account getting hacked is not my problem.*

---

### Credits
> [!IMPORTANT]
> - Special thanks to the following fellows for their amazing projects making this modified project possible:
> - 🔴SpermLord
> - 🟡CatalizCS
> - 🟢MrTomXxX
> - 🟠NTKhang03
> - 🟣KhangGia1810
> - 🔵XaviaTeam
>
>   ### In collaboration with (https://github.com/MrT0mX)
>   
> _Updated on: May 6, 2024 (PST)<br>Creation Date: June 11, 2023_

Copyright © 2024 MrTomXxX (MrT0mX), Bangladesh.<br>
