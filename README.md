# Reddit Video Maker Bot - Waffle Hacker Custom Fork 🎥

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.

WaffleHacker Custom Fork. Bot originally created by Lewis Menelaws & [TMRRW](https://tmrrwinc.ca)

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort.
The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Custom features that I added

- Fully loaded GUI with the ability to configure background audio, toggle story mode, and start bot from GUI
- Add opacity to the screenshots 

## Features Out the Box

- Add background video and background audio
- Regular Mode and Story Mode (Regular mode shows screenshots of the reddit post title and comments, story mode just shows the text of the story from the reddit post
- Auto generate videos by grabbing top reddit threads or create  from a specific reddit thread of your chosing
- Choose a narrator voice
- Toggle Randomize Voice for each reddit comment

## Disclaimers 🚨

- **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that
  you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

- Python 3.10
- Playwright (this should install automatically in installation)

## Installation 👩‍💻

1. Clone this repository
2. Run `pip install -r requirements.txt`
3. Run `python -m playwright install` and `python -m playwright install-deps`

**EXPERIMENTAL!!!!**

On macOS and Linux (debian, arch, fedora and centos, and based on those), you can run an install script that will automatically install steps 1 to 3. (requires bash)

`bash <(curl -sL https://raw.githubusercontent.com/elebumm/RedditVideoMakerBot/master/install.sh)`

This can also be used to update the installation

4. Run `python main.py`
5. Visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps), and set up an app that is a "script". Paste any URL in redirect URL. Ex:google.com
6. The bot will ask you to fill in your details to connect to the Reddit API, and configure the bot to your liking
7. From now on, to run your bot, simply run `python GUI.py` and enter the Thread ID and/or other configs, as soon as you Save Changes, the bot will run. No need to manually edit config.toml every time! (WaffleHacker Feature Add)
8. Enjoy 😎

(Note if you got an error installing or running the bot try first rerunning the command with a three after the name e.g. python3 or pip3)

If you want to read more detailed guide about the bot, please refer to the [documentation](https://reddit-video-maker-bot.netlify.app/)


## Developers and maintainers.

Elebumm (Lewis#6305) - https://github.com/elebumm (Founder)

Josh Holly (WaffleHacker#1480) - https://github.com/joshholly (Bug Fixer and Feature Adder)

Jason (JasonLovesDoggo#1904) - https://github.com/JasonLovesDoggo (Maintainer)

Simon (OpenSourceSimon) - https://github.com/OpenSourceSimon

CallumIO (c.#6837) - https://github.com/CallumIO

Verq (Verq#2338) - https://github.com/CordlessCoder

LukaHietala (Pix.#0001) - https://github.com/LukaHietala

Freebiell (Freebie#3263) - https://github.com/FreebieII

Aman Raza (electro199#8130) - https://github.com/electro199


## LICENSE
[Roboto Fonts](https://fonts.google.com/specimen/Roboto/about) are licensed under [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)
