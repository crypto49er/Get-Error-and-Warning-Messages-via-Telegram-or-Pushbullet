This modification will allow you to receive error or warning messages via Telegram or Pushbullet 
(and other plugins like Slack, Twitter, email, if you add the code to those plugins). This works in Gekko 0.5x and Gekko 0.63.
Here's how to install it.

1. Replace log.js in gekko/core with file in here.
2. Replace telegrambot.js and pushbullet.js (or just one if you don't use both) with files in this repo. 
3. Start up Gekko command line as you normally do. Any warning or error message will now show up in terminal and in Telegram/Pushbullet.
