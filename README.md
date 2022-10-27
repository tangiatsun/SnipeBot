# SnipeBot

This was made for the club Assorted Aces at Cornell University by Tangia Sun.

Assorted Aces have a game where if someone sees someone else on campus, they can take of picture of them and send it in the Discord. If the target doesn't notice, it is considered that the target got "sniped." This bot keeps track of the score of how many times someone gets sniped or snipes someone. There is no leaderboard yet because it might become too competitive but can definitely be added. Scores are talied in an .xlsx file.

# Instructions for setup
This open source bot contains all the logic to make the bot. The code that actually runs the bot for Assorted Aces has the same logic, but uses a different file to avoid publicly releasing the Discord bot token.

Changes needed to run it on your own server after pulling:
- Change the "path" of where the excel sheet is (~line 28, ~line 58). It will create its own scoresheet if there isn't one.
- Create a Discord bot using their developer tool and insert the token at the end of the code.
  - The permissions it requires are:
    - Read Messages/View Channels
    - Send Messages
    - Send Messages in Threads
    - Read Message History
    - Add Reactions
- Create an invite link in their developer tool and invite the bot into the server.

