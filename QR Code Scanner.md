# The Problem
QR codes are taking off as a quick, simple, and intuitive way to transfer information. What I've been seeing recently, at least in the US, is the rise of QR codes in restaurants to encourage contactless ordering. Being able to conveniently scan QR codes is a bigger and bigger problem to solve with each and every day.

The problem is that people are capitalizing on this pertinent space by making QR code scanning apps that are riddled with ads. We want to make a clean QR code scanner that is also free and ad-free. This is easily one of the most effective "Power of free" spaces I have ever seen.

# MVP Requirements
- Open to live camera page
- When the live camera detects a QR code, automatically navigate to that link

QR code scanning is a very utility-style type of value, so we can keep it extremely simple for v1, making a lot of user assumptions to follow least clicks design.

# Best Platform
**Mobile**

QR codes are very much an "on the go" type thing, especially as it effectively needs camera. It makes very little sense to build this on web.

This is mainly inspired by Android, which doesn't seem to scan QR codes automatically from the native camera app and all the top app choices are riddled with ads and/or clunky. I heard that iOS has some native QR code integrations, so it may not be worth as much pursuing as much on iOS, but I'm sure there's still opportunity there.

# Difficulty
**Medium**

So there's a lot going on like the camera feed and QR code scanning of course, but I assume there's a lot of tutorials and libraries out there, which is why I'm having this at just a Medium. With just a bit of Google, I was able to find a good tutorial for Android [here](https://learntodroid.com/how-to-create-a-qr-code-scanner-app-in-android/).

# Possible Extensions
- Ability to pick up QR codes from images
  - You can add an image editor for users to crop out the code to make this go deeper
  - When it comes to image import, you can always extend by allowing additional sources like URL, Google Drive, etc
- Confirm the URL to navigate to before taking the user there
- An interstitial landing page vs. jumping to camera directly (this is what most QR code apps do)
- QR code/link history
- Bookmarking/favoriting
- User accounts if you decide to build persistent data sources like history and favorites
- Turning into a giant social/location-based platform where people can see what kinds of QR codes other people/places are scanning
