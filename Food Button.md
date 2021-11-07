# The Problem
TBD

# MVP Requirements
TBD

# Best Platform
**Mobile, but web is also solid**

Mobile is the best for this as this is a more "on-the-go" type thing, and it has the best "hero flow" where you can just tap a navigate button and start heading there in Google Maps. However, if you have access to your computer (e.g. you are hosting an event), you can do this on your computer as well. Restaurant APIs provide a lot of information so the extra space that web gives you is useful.

# Difficulty
**Easy**

Getting a base version of this is extremely easy, especially if you use the very open and straightforward Yelp API. It's just a GET, and from there, it's primarily a UI problem instead of a gnarly technical problem.

# Possible Extensions
- Use a better API. In particular, Google Places is probably the best, but I'm unsure how much you can do for free
- Do API aggregation or routing. So instead of just using 1, use Yelp, TripAdvisor, Google, etc to really get the best results. If you are aggregating though, you will need to de-dupe. Routing means that you detect which region the user is in and use the best API accordingly
- Build your own API that wraps the restaurant APIs, either doing the routing/aggregation logic
- Use machine learning or some basic logic to learn the tastes of the user over time, refining your choice algorithm
- Customizable filters, so the user can refine their tastes manually
- Automatic push notifications suggesting places the user might like
- Bookmarks/favorites
