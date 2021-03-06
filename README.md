[![Issues](https://img.shields.io/github/issues/reoccurdevs/autumncord.svg?colorB=5e03fc)](https://github.com/reoccurdevs/reoccurcord/issues)
[![Site Status](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=purple&up_message=online&url=https%3A%2F%2Fautumncord.xyz)](https://autumncord.xyz)
[![Stars](https://img.shields.io/github/stars/reoccurdevs/autumncord?style=social)](https://github.com/reoccurdevs/autumncord/stargazers)
[![Discord](https://canary.discord.com/api/guilds/883472120083005441/widget.png?style=shield)](https://discord.gg/yATc4DJ69R)
[![License](https://img.shields.io/github/license/reoccurdevs/autumncord)](https://github.com/reoccurdevs/autumncord/blob/main/LICENSE)
[![Commits](https://img.shields.io/github/commit-activity/m/reoccurdevs/autumncord)](https://github.com/reoccurdevs/autumncord/commits/main)
![Maintained](https://img.shields.io/maintenance/yes/2021)

# AutumnCord 

## Welcome to the official GitHub page of the AutumnCord bot!
AutumnCord is a Discord bot made formerly by the reoccurdevs team but taken over by the last dev that worked on it that you can edit and self host. If you want to fork it and make a new bot, that's fine, but please give us credit. :)
If you find an issue, or have a feature suggestion, please let us know by opening an issue [here](https://github.com/reoccurdevs/autumncord/issues).

## Documentation
### NOTICE
I as a developer did not intend for this bot to be self hosted. Things may be broken or may break. Support may not be given for arbitrary issues. Proceed with risk.
### Starting the bot
#### Make sure you have [Python 3](https://www.python.org/downloads/) installed and put in your path!
^^^ Linux users: this step shouldn't be necessary ^^^
1. Clone the repository: `git clone https://github.com/reoccurdevs/autumncord.git` and go to step 2. An alternative is to download the ZIP file, unzip it, shift + right click in the `autumncord-main` folder, click on `Open Powershell window here`, and continue with step 3.
2. `cd` to the repository folder: `cd autumncord`.
3. Make sure all the dependencies are installed: `python -m pip install discord.py requests asyncio gitpython psutil datetime bs4 jishaku nudenet tensorflow-cpu` If there are any other errors with importing dependencies, install them as necessary.
4. Run `python setup.py` for a configuration creator. If you fail to do this, the bot will not run.
5. Before starting, make sure the Server Members Intent is enabled in your bot settings in the Discord Developer Portal.
6. To make sure the `mute` and `unmute` commands work, please make a role called `muted` in your server. The bot will not (yet) do this for you. After you create the role, make sure to create overrides for the channels you don't want a muted user speaking in.
7. Run the main bot file: `python start.py` (or see the commands with `python start.py --help`).

### Features

There are many features of the bot. These features include:

- VirusTotal file scanning
- Message encryption
- Moderation
- Fun commands
- Utility commands
- Custom playing status that you can customize per instance
- Self updating feature
- Lots more commands, and more commands being added regularly!

Like earlier said, if you have any feature requests or issues with the bot, open an issue [here](https://github.com/reoccurdevs/autumncord/issues)!
Enjoy the bot! We hope you have as much fun with it as I have programming it! :)

Made with PyCord.
