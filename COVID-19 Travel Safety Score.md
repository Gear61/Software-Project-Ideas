# The Problem
I want to know how safe it is to travel to a certain place from a COVID-19 perspective, and if it's not that safe there, what I should do to protect myself.

As the world opens up again with the advent of the COVID-19 vaccine, there's a lot of pent-up travel energy that is now being unleashed. Unfortunately, COVID-19 is still a major problem, especially with the Delta variant. We want to create a tool that lets travelers know in a simple, clean, and easy-to-understand way what the "COVID-19 landscape" is like for their travel destinations and what concrete actions they should take to stay safe if necessary.

# MVP Requirements
- User can input a location, aided by a location auto-suggest. You almost certainly want to use the Google Places API for this.
- Once the user submits the location, you show a COVID-19 safety report for that location. This includes:
  - A qualitive safety rating or recommendation, ideally color coded. Something like "No Precautions Needed", "Few Precautions Needed", "Some Precautions Needed", etc.
  - Average daily case rate per 100,000 over the past 7 days. If you can show a graph instead of a raw number, even better.
  - Infection rate
  - Hospitalization capacity
  - Recommended safety measures. For example, if the case rate is very low, you can just suggest nothing. If case rate is sort of low, maybe just recommend wearing a mask in crowded indoor venues. If the case rate is very high, probably recommend leaning heavily towards outdoor activities.

# Best Platform
**Web**

This would actually be great on mobile, especially as travel and location are very "on-the-go" type things, but you aren't allowed to publish apps related to COVID-19 on the Google Play Store or Apple App Store unless you are an official medical/government entity. So we have to do this on web; the extra space is helpful for web though as this is an information-display app.

# Difficulty
**Medium**

This project has some nice complexity as you will need to make 2 API calls:
1. Location suggestions, probably through Google Places as mentioned before
2. COVID-19 data fetch for a certain location

Aside from that, this is a fairly straight-forward local utility app with a big emphasis on clean UI/UX. I consider this on the upper end of easy and the lower-end of medium.

As an American, I don't know much about outside the US, but the US has a lot of good COVID-19 APIs and websites. My favorite one is [covidactnow.org](https://covidactnow.org/).

# Possible Extensions
- Make the tool global. I don't think there's a good API for COVID-19 data with global coverage; it seems like every region has its own API. You will need to stitch APIs together to make this truly global most likely.
- Working off of the above point, make an aggregate API to create that global COVID-19 data API. So you can turn this into both a back-end project and a front-end project!
- Travel recommendations based on places that are both popular and relatively low in cases and spread
- Data and analytics to see where people are looking to go with your app, which you can then use to show "Most popular destinations" or something
- Safety report sharing
- MapView so the user can browse locations vs. having to input a specific one
- Safety report customization so users can see variations of statistics like daily case load over 3 days instead of 7 and stuff like that
- Different safety recommendations for vaccinated people vs. unvaccinated people (though asking for this information may be... tricky compliance-wise)
