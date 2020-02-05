# TinderBot
TinderBot is a bot that constantly swipes **LIke** on tinder profiles so that you can focus on doing other things and find a romantic match

### How to use the application
- *You must have a tinder account already with the initial setup before going further.*
- Using your terminal run the command *brew cask install chromedriver* to download chromedriver to control chrome from terminal
- If above doesnt work maybe you do not have brew. If thats the case download brew on your mac.
- Make sure you have pip installed. If not check out https://pip.pypa.io/en/stable/installing/
- Using pip run **pip install virtualenv**
- run virtualenv venv on your tinderbot root directory
- run **source venv/bin/activate**
- *Important* Open secret.py and fill in your username and password for your facebook account
- Once the python environment is loaded run **python -i tinderbot.py**
- An interactive prompt should open up followed by a chrome window with tinder login details filled for you by the bot
- Once bot is finished logging in run the command **bot.auto_swipe()**
- Tinder bot should start swiping likes for each profile pic.
