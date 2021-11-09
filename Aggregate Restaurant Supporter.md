# The Problem
Restaurants have been struggling hard due to the COVID-19 pandemic, and I want to support the good ones. When I go to a good restaurant that is struggling, I go out my way to support them by leaving a 5-star review on every online review platform I can.

The problem is that this process is currently manual. I need to individually sign on to Yelp, TripAdvisor, and Google Places and then copy-paste my positive review across all 3 platforms. I want a tool that lets me do this all in 1 go, making supporting my favorite restaurants online a breeze.

# MVP Requirements
- User can sign in to at least 3 review aggregation websites. If I were to choose, I would do Yelp, TripAdvisor, and Google Places. You can adjust this based on your region.
- User can write a review. This includes the rating out of 5 stars and a text box.
- When user submits their review, it gets posts to all the review platforms they have set up with this product.

# Best Platform
**Web, but mobile isn't too bad**

I absolutely hate typing on mobile, so I would really prefer web for this. This is a content creation tool, and the extra space and keyboard make this easier on web. However, a lot of people leave things like comments and reviews on the go, so I imagine mobile isn't too bad.

# Difficulty
**Hard**

I did some research on the APIs, and I actually don't think this is possible out of the box. You will probably have to hack together an API via scraping or ask the companies' support teams for special API access. You also need to juggle various API calls across auth and creating the review.

# Possible Extensions
- Globalizing this. The 3 services I mentioned are more American/Western friendly, I know that there's more regional websites for other places.
- Allowing the user to attach media like videos and photos
