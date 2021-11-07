# The Problem
The Tech Career Growth community has 6,600+ members as of 11/7/2021, and it's constantly growing. What's important is that a lot of folks haven't used Slack before and aren't aware of how to find channels besides the default ones (finding a channel is not very intuitive in the Slack UI). We want to make this process far easier and far more automated.

In a nutshell, we want to create a bot where the user takes a quiz and gets automatically added to all the proper channels.

# MVP Requirements
- When the user opens a chat with the bot, the bot automatically has a prompt of "Would you like to take a quiz to figure out what channels to join?"
- If the user opts into the quiz, they get a series of questions about them
- After answering all the questions, they get automatically added to fitting channels and are told which ones they are. The copy can be something like, "Thanks for telling me about yourself! I have added you to the following channels: #channel1, #channel2, etc."

Questions and channel links:
- Are you job seeking right now? (yes/no)
  - Yes: Add them to #interview-prep and #resume-sharing-and-reviews
- Are you interviewing with Big Tech (yes/no)?
  - Yes: Add them to #interviewing-facebook, #interviewing-google, #interviewing-microsoft, #interviewing-apple, #interviewing-amazon
- What is your most recent educational background in tech? (single-choice)
  - High school: Add to #high-schoolers
  - University: No-op, we don't have a channel for university students yet. We should probably make one...
  - Bootcamp: Add to #bootcampers
- What tech stacks do you work with? (multi-select)
  - Android: Add to #android
  - iOS: Add to #ios
  - Web: Add to #web
  - Backend: Add to #backend
  - Flutter: Add to #flutter
- Do you need help understanding your compensation and maximizing your pay? (yes/no)
  - Yes: Add to #compensation-discussion

# Best Platform
**Slack**

This is specifically for Slack, so... yeah.

# Difficulty
**Medium**

There's a decent amount of manual content to work in, and you'll need to learn how to work with various Slack UIs (yes/no, single-choice, multiple choice).

# Possible Extensions
- Make this customizable so any Slack admin can create whatever quiz they want for their workspace
- Give the user the ability to remove themselves from a channel they were added to in case the bot got it wrong. I am envisioning a list view of all the channels they got added to with a "Leave" button on the right side
- Logging and analytics to see how many people used the bot, which channels they're added to, etc
- Have the bot just return a list of all the possible channels if the user types in "all" or something
