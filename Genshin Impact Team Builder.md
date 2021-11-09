# The Problem
I play a lot of Genshin Impact, which is an extremely popular video game. One of the core aspects of the game is taking your many characters and figuring out how to make effective teams with them.

Right now, there is no low-effort tool to help you do this. The process is currently very manual. You either need to watch a bunch of YouTube videos or go to a website like [this one](https://www.genshinlab.com/team/), where they just list out every possible team and you need to go through the cognitive load of checking whether you can buid each one.

I want to build a tool where I can input what I have in-game and get suggested teams automatically.

# MVP Requirements
- User can input the characters they have
- The homepage is a list of suggested teams that are possible for the player and has guides on how to play these teams and why they work

# Best Platform
**Web, but mobile isn't too bad**

This is a content display app, so 

# Difficulty
**Hard**

I did some research on the APIs, and I actually don't think this is possible out of the box. You will probably have to hack together an API via scraping or ask the companies' support teams for special API access. You also need to juggle various API calls across auth and creating the review.

# Possible Extensions
- Accounts
