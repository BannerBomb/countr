[![Discord](https://img.shields.io/discord/449576301997588490.svg?label=Discord&logo=discord)](https://discord.gg/pfQz5Pq)
[![David](https://img.shields.io/david/Gleeny/Countr.svg?logo=javascript&logoColor=white)](https://david-dm.org/Gleeny/Countr)
[![GitHub Issues](https://img.shields.io/github/issues/Gleeny/Countr.svg?logo=github&logoColor=white)](https://github.com/Gleeny/Countr/issues)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/Gleeny/Countr.svg?logo=github&logoColor=white)](https://github.com/Gleeny/Countr/commit/master)
[![License](https://img.shields.io/github/license/Gleeny/Countr.svg?label=License&logo=github&logoColor=white)](./LICENSE)

# Countr

[Documentation](https://gleeny.github.io/countr/) - [Support Server](https://gleeny.page.link/discord)

## Self-Hosting

If you want to self-host Countr, follow these instructions:
1. Fork or download this repository.
2. Rename `config.json.example` to `config.json`.
3. Go to [https://discordapp.com/developers/applications/](https://discordapp.com/developers/applications/) to make an application. [Help Image](https://i.imgur.com/XkWuL18.png)
4. Go to the tab called Bot and make the application a bot. [Help Image](https://i.imgur.com/wfMSiEH.png)
5. Grab the token from the bot and put it in `config.json` [Help Image](https://i.imgur.com/NdXK1Po.png)
6. Go to [https://mlab.com](https://mlab.com) and create a new account if you don't have one. [Help Image](https://i.imgur.com/B4Omzty.png)
7. Create a new database, call it whatever you want. Pick the region closest to your host. [Help Image #1](https://i.imgur.com/rHe8A0o.png) [#2](https://i.imgur.com/9SSgvVy.gif)
8. Go to Users and add a new database user. Username and password can be whatever you want, just write them down somewhere. [Help Image #1](https://i.imgur.com/yAEhTgE.png) [#2](https://i.imgur.com/hTsf0A5.png)
9. Once created, combine it with the URI and put it in `config.json`. [Help Image](https://i.imgur.com/xlz7SYa.png)
10. Open a command prompt in the same folder as the files you've downloaded or forked, and type `npm i`.
11. Then run the bot using `node sharding.js`. Have fun!
If you have questions, come to our Support Server.