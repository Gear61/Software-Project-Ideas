# The Problem
WhatsApp released stickers a while ago, and it's very interesting how they work. Unlike Messenger where it's a central hub built into the app in-house, WhatsApp decided to platformize it. The WhatsApp app will provide a few core sticker packs, but if you want more specific stickers, you need to download 3rd party apps which have those assets and plug into the WhatsApp mobile apps to "upload" those specific stickers in.

The problem is that these 3rd party WhatsApp sticker adding apps are almost entirely all ad-ridden garbage with clunky UI/UX. This is one of those apps where if you make a polished, free/ad-free version, you automatically have a huge leg up in the market.

# MVP Requirements
This MVP is what I've personally seen from Android sticker apps for WhatsApp, primarily with the design. Feel free to play around with the UI; this is not a complex app.

- Homepage is a list of popular sticker packs
- Each sticker pack row has some stickers as a preview alongside the pack name
- When a sticker pack row is tapped, it opens up a detailed view where it shows all the relevant stickers in a grid
- "Add stickers to WhatsApp" button at the bottom of the detail page

# Best Platform
**Mobile**

The sticker sharing protocol doesn't exist on web, at least to the best of my knowledge. This means that you have no choice - This has to live in a mobile app.

# Difficulty
**Medium**

How WhatsApp sticker apps work is that you fork their [sample app](https://github.com/WhatsApp/stickers) and then tweak the UI and content to your liking. [I did this](https://github.com/Gear61/stickers) a few years ago in about a day, and it wasn't that hard. The code is a bit messy, but it's readable and the overall protocol is there.

# Possible Extensions
- Log metrics, primarily download count
- Add a rating or favorite option and log that as well
- Ability to sort on popularity (combination of rating/favorite + download count)
- Search bar
- Ability to download individual stickers instead of entire packs
- Quick download button at the homepage row level in addition to the detail view
