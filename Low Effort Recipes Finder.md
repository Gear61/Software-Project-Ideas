# The Problem
I love to cook, because it's a great skill to have, saves money, and is healthy. The problem is that I don't have a lot of time, so I can't cook what is seemingly most of the recipes I find online: Beautiful and delicious but overly complicated with many steps, lots of ingredients, and tons of dish washing afterwards.

Right now, it is not easy to find low effort recipes; you need to go to a more generic platform, either an overall recipes app or something like YouTube, and do a heavily filtered search. Our goal here is classic "addition by subtraction"; we want to create a focused platform with *only* simple, low effort recipes.

# MVP Requirements
- Some sort of splash page with the logo, app name, maybe an explanation of the app, and a "Find Me A Recipe!" button
- When the user clicks the button, make an API call to fetch a random low effort recipe. Show the recipe in a full page detail view once it has been fetched
- The detail view should contain the following 
  - A picture of at least the finished dish
  - The recipe as a series of steps
  - 1 or more videos (if applicable)
  - Rating (if applicable)
- Here's my definition of low effort. Feel free to tweak it, but I don't recommend straying too far.
  - Uses 5 or less ingredients
  - Only uses common ingredients like chicken, potatoes, onions, and carrots. We want these recipes to be dishes people can put together with ingredients laying around the kitchen
  - 1 hour or less of cook time
  - Can make 3 or more servings
- A "Show me another recipe!" button on the recipe detail page

To keep things simple, I chose a single button experience for v1. I considered a feed, but the problem is how would you show a different feed upon each visit?

# Best Platform
**Mobile, Web**

Displaying a recipe could really use the extra space, but it's much more convenient to have your phone in the kitchen to reference the instructions as you go vs. your entire computer. This is why I think this app can easily live across both platforms.

# Difficulty
**Easy**

The v1 of this project is pretty simple as it's effectively a nice UI/UX wrapper around a single focused API call.

I haven't done a ton of research on recipe APIs, but it seems like finding a completely free one could be tricky. [Here's one](https://developer.edamam.com/edamam-recipe-api) that I found that gives 10,000 free API calls per month on the free tier, which should be enough to support a few thousand users. If you find yourself hitting the limit, congratulations, you have a great problem to have - Too many users!

TBD

# Possible Extensions
- Opening to some sort of feed or grid upon opening the app to save a click
- Sharing functionality for recipes
- Filters (cuisine types, ingredients, etc)
- Bookmarking/favoriting
- Accounts (will be necessary if you add features like favoriting)
- Allow users to rate recipes
- Personalization of recipe selection, either through basic rules or machine learning
