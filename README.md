# Discord Advertisement Bot

## Background

One of the core functions of a community esports organization is to host tournaments. However, advertising those tournaments across multiple communities can be a bit of a hassle, especially figuring out which discord servers, channels, and roles the message is to be sent in. That is where this bot comes in. It is designed to automate the advertisement of a tournament event specific to one esports organization (alpine).

## Setup

1. Download this repository
2. Create a .env file, and type "DISCORD_TOKEN=" followed by your bot token
3. Copy and paste the relevant information into src/info.js
    this includes your main server ids, channels and roles, as well as partner server and channel ids
4. navigate a terminal to the repository folder
5. "npm install"
6. "npm start"

## Usage

Typing ".help" into a main server channel will prompt the bot to show the first page of commands.
".help 2" will show the 2nd, and ".help staff" will show staff commands.
.promo {w/a} {Date/Tonight} will send a trial announcement in the specified trial_announcement channel, and reacting with the green check mark will send the announcement to the main server announcement channel as well as all partner announcement channels.

## Credits

This project was started by Jarod Kafka and Schon Hale, resulting in the alpha version. Then, version 1.0 was developed by Jarod Kafka under the guidance of Corbin Fonville, and added file separation, best-practice styling and CI/CD
