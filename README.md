# Tibia CrashGame Bot
The bot was supposed to receive the last result and then make a predetermined bet all automated. But unfortunately I noticed something in the game that broke the whole bot so I decided to post it here for practice purposes.

# How it works
- first it opens the game with selenium webdriver
- then collects the result of the last round with selenium and put it in a list
- after that it checks if it is time to place a bet seeing if the button "bet" is in color green(time to place a bet) or grey(not yet)
- if it is green, it will get the last element of the list and depending of the result it can put a certain quantity of coins(tibia coins/cripto) and bet
- after all that, it will erase the last bet and restart everything until you make it stop

