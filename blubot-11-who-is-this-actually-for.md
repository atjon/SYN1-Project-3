---

layout: default
title: "Blubot 11: Who Is This Actually For?"
---
This is the eleventh post in the series about my project, Blubot, a robot that takes care of your raised bed for you. With Blubot, I'm on a mission to make gardening easy, space efficient, and low cost, so anyone, anywhere can start a garden. Check out the [table of contents here](https://codehobbits.com/bluebot-by-aidan-tjon-2025/).

This post is a little different from the others. For the last ten posts, I've shown you how I built Blubot, from the first measurements to building a team to the week I spent calibrating the z-axis. In this one, I want to step back and talk about why I built it, and be honest about what it actually does and doesn't do.

![A green plant growing in the Blubot raised bed]({{ site.baseurl }}/images/green-plant-on-robot.png)

It's been almost a full two years since I started Blubot. Across those two years, my voice, outlook, and experiences have changed drastically. I've tried to emulate my past voice here in this post, to keep it consistent with what you are used to hearing. 

**Why growing your own food matters**

One thing I've learned is about water. Farming uses a huge chunk of the world's freshwater, [around 70%](https://ourworldindata.org/water-use-stress), and a lot of it gets wasted through evaporation, runoff, and watering soil that didn't need it. Big farms deal with this using precision irrigation, which means giving each plant exactly the water it needs and nothing extra. Systems like that can [cut water use by 30 to 70%](https://news.mit.edu/2017/design-cuts-costs-energy-drip-irrigation-0420). When I think about it, that's basically what Blubot does, just in a backyard. It checks the soil and waters one spot at a time instead of soaking the whole bed. It's a tiny version of something farms spend a lot of money on.

The second thing is about access, and this is the part I care about most. About [39 million people in the US](https://www.aecf.org/blog/food-deserts-in-america) live in areas where the nearest grocery store is really far away. Growing food at home doesn't fix that by itself, but it helps more than I expected. One [study in San Jose](https://californiaagriculture.org/article/108832-community-and-home-gardens-increase-vegetable-intake-and-food-security-of-residents-in-san-jose-california) found that people with a home or community garden roughly doubled how many vegetables they ate. A lot of them grew vegetables they couldn't find nearby, like bok choy and bitter melon. Growing up in a Chinese household, the right ingredients weren't always easy to find at the store. Home gardens also give people a [backup when food prices jump or supply chains get disrupted](https://www.frontiersin.org/journals/sustainable-food-systems/articles/10.3389/fsufs.2023.1138558/full), which is something that keeps getting more common.

So the argument I actually believe is pretty simple. Most home gardens don't fail because people don't care. They fail because people forget to water, or overwater, or go on a trip, or just don't know what a plant needs. If you can automate that part and make it cheap, you take away the main reason gardens die. This is what Blubot solves.

![Picking strawberries with my grandmother]({{ site.baseurl }}/images/picking-strawberries.jpeg)

**The part I need to be honest about**

"Anyone, anywhere can start a garden" is a great line, but it isn't true yet, and I don't want to pretend it is. Think about everything I needed just to get Blubot running. I needed a yard, or at least a raised bed I could rent through a community garden. I needed enough money that robot, which costs around a thousand dollars before you change anything, was a fundraising goal instead of something impossible. And I needed internet so badly that when the WiFi wouldn't hold, I ran an ethernet cable from the router inside my house, through the wall, all the way out to the backyard.

Someone who has a yard, the money, and the patience to run a cable through a wall is not the person who gets hit hardest by food deserts. Not to mention, $1000 is a steep starting price. I built Blubot to discover what nuances it took to build a robot of this magnitude from scratch. However, it's still a gap that would be dishonest to skip over.

In addition, I also read that [community gardens, and even new grocery stores, don't really solve food deserts on their own](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2015.0667). The real causes are bigger things like income, transportation, and land. A robot in a backyard doesn't change any of that. I think it's important to say that out loud instead of acting like Blubot fixes problems it can't touch.

With all that being said, I know where I'm positioned while I write this. I'm a first-generation college student from the Bay Area building robots. I'm close enough to this problem to feel it in my own family, but I also have enough resources to spend a year and a whole crowdfunding campaign trying to solve it. Both of those things are true at the same time.

![Tightening some screws on the z-axis]({{ site.baseurl }}/images/working-on-z-axis.jpeg)

**So why keep going?**

Here's what I keep coming back to: How do I stay hopeful and keep building this project, without pretending it is a substitute for the bigger changes that food and climate problems really need?

The best answer I have right now is this. Building Blubot isn't enough on its own. But not building it because it isn't enough would be its own way of giving up.

So I try to think of Blubot as three things at once. It's a proof that precision watering can work in a backyard and not just on a research farm. It's something people can learn from, which is why I wrote about every WiFi problem, every belt that wouldn't tension, and the whole week I lost on the z-axis, so the next person can start ahead of where I did. And it's an invitation, because the whole point of doing this cheaply and out in the open is to make it easier for someone with fewer resources than me to pick it up and take it further.

A robot isn't going to fix the food system. But making good food a little easier to grow, and sharing exactly how I did it, is one real thing I can do about a problem this big. I'm going to keep honestly documenting the wins and losses.

Keep Growing!

---

**Works Cited**

Algert, Susan, et al. "Community and Home Gardens Increase Vegetable Intake and Food Security of Residents in San Jose, California." *California Agriculture: The Journal of UC Agriculture and Natural Resources*, 1 Apr. 2016, [californiaagriculture.org/article/108832-community-and-home-gardens-increase-vegetable-intake-and-food-security-of-residents-in-san-jose-california](https://californiaagriculture.org/article/108832-community-and-home-gardens-increase-vegetable-intake-and-food-security-of-residents-in-san-jose-california).

Baliki, Ghassan, et al. "Home Garden Interventions in Crisis and Emergency Settings." *Frontiers in Sustainable Food Systems*, 25 May 2023, [frontiersin.org/journals/sustainable-food-systems/articles/10.3389/fsufs.2023.1138558/full](https://www.frontiersin.org/journals/sustainable-food-systems/articles/10.3389/fsufs.2023.1138558/full).

Chu, Jennifer. "Watering the World." *MIT News*, Massachusetts Institute of Technology, 19 Apr. 2017, [news.mit.edu/2017/design-cuts-costs-energy-drip-irrigation-0420](https://news.mit.edu/2017/design-cuts-costs-energy-drip-irrigation-0420).

Dubowitz, Tamara, et al. "Diet and Perceptions Change with Supermarket Introduction in a Food Desert, but Not Because of Supermarket Use." *Health Affairs*, Nov. 2015, [healthaffairs.org/doi/full/10.1377/hlthaff.2015.0667](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2015.0667).

Ritchie, Hannah, and Max Roser. "Water Use and Stress." *Our World in Data*, 1 July 2018, [ourworldindata.org/water-use-stress](https://ourworldindata.org/water-use-stress).

The Annie E. Casey Foundation. "Food Deserts in America: Understanding the Impact on Communities with Limited Food Access." *The Annie E. Casey Foundation*, 14 Feb. 2021, [aecf.org/blog/food-deserts-in-america](https://www.aecf.org/blog/food-deserts-in-america).