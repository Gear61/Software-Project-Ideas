# The Problem
I want an interactive way to practice speaking foreign languages; this means being able to have a mock conversation with an automated app instead of doing standard quizzes and tutorials. Language is primarily meant to be spoken (or at least that's the most fun part of using it).

I built a very basic version of [this app](https://play.google.com/store/apps/details?id=baby.seal.foreignconversationhelper) on Android a few years ago. I haven't done much research on the market recently, but back when I built it, the market definitely had a gap here.

# MVP Requirements
- The app supports at least 1 language with at least 10 conversation lessons per language
- A conversation lesson consists of a back-and-forth of at least 3 sayings on each side
- The goal of the app user is to mimic the simulated conversation as much as possible
- The user should be able to read a conversation lesson to see what they're supposed to say before jumping into the lesson
- The user should be able to tap on any foreign text to see how it is pronounced
- When the lesson starts, either the app or the user needs to say something. When the saying is done, alternate to the other party
- User can see how what they said is transcribed and compare it to what they were supposed to say

# Best Platform
**Mobile, but web could be okay**

On Android at least, text to speech and speech to text are fairly easy to use. I think the experience is far clunkier on web, but it could be done.

# Difficulty
**Hard**

There is a lot to unpack here. You need:
1. Lots of hard-coded, quality content
2. Several audio integrations
3. A good chat UI
4. Several fairly involved pages in general
5. Decent audio transcription - The Android one isn't great, and I'm unsure about other platforms. This may need to be outsourced.

# Possible Extensions
- Automatic grading 
- More languages
- More lessons
- Completion status
- Accounts
