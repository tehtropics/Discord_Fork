# Adding your bot to the website
Thanks for choosing Discord_Fork for your preffered Discord Bots Service Provider (DBSP)

You will require some knowledge on `git` in order to add your bot.

- Fork the project

![How to fork](https://its-not-advertising-if-the-website-doesnt-exist-anymore.moustacheminer.com/1531011733.77.png)

- Inside the `_bots` folder, create a file called `[CLIENT_ID].md`, where `[CLIENT_ID]` is the ID of your bot.
- Copy the code below, and replace with your own details
```ini
---
client_id: [The client ID of your bot]
application_id: [OPTIONAL / The application ID of your bot. Delete this line, unless you have a pre-2016 bot]
botname: [The name of your bot]
prefix: [The prefix of your bot]
description: [The description of your bot, limited to 60 characters]
long_description: [OPTIONAL / A longer description which displays on your bot page]
avatar: [An avatar URL to a Discord website]
link: [A link to invite your bot - HTTPS only]
github: username/projectName [OPTIONAL / The location of the source for this bot]
nsfw: true | false [If your bot is "Not Safe For Work"]
---

# Markdown
This is an example of Markdown. [Here is a tutorial](https://guides.github.com/features/mastering-markdown/)

_thanks_ **alex**

```
- Create a commit
![Creating and editing a file](https://its-not-advertising-if-the-website-doesnt-exist-anymore.moustacheminer.com/1531012665.07.png)
- Go the pull requests page
![Going to the correct PR place](https://its-not-advertising-if-the-website-doesnt-exist-anymore.moustacheminer.com/1531012768.53.png)
- Create a pull request
![Creating a PR](https://its-not-advertising-if-the-website-doesnt-exist-anymore.moustacheminer.com/1531012827.26.png)
![Pressing the button to create a PR](https://its-not-advertising-if-the-website-doesnt-exist-anymore.moustacheminer.com/1531012912.81.png)
- Now wait from 3 to 10 business days.

<!-- ## Adding your server to the list
- Fork the project
- Add a new file in **\_servers** with `your_server_name.md` and add the following:
```md
---
servername: SERVER NAME
description: DESCRIPTION (limited to 60 characters)
long_description: LONG_DESCRIPTION (only viewable at bot page)
avatar: URL, must be the Discord Server icon in PNG format and no ?size query
link: URL to discord.gg invite only
nsfw: false
---
After this line, you can do any markdown code you want for custom page!
```
- make a PR and wait for answers -->
