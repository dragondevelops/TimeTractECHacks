# TimeTract

As humans, we are terrible at keeping track of time and are often unaware of how our time is spent. RescueTime is a passive time-tracking app that allows you to quickly view the breakdown of your time, providing detailed statistics and eye-opening truths that motivate you to start using your time in a more efficient way.

However, RescueTime largely relies on internal motivation (motivation coming from yourself), which may not be enough for many people. Our hack aims to incorporate external motivation to RescueTime, resulting in a very powerful time-tracking tool that will help many to reclaim their time.

Inspiration
The idea for this project started when Leon created a daily recurring Google Script that would format RescueTime information into a Google Sheets, allowing for a quick overview of how he spent his time over the past few days. Being a productivity geek, he used this script as part of a precommitment, telling his friends to shame him when they would see a log of a time-wasting activity. It worked well, and he would often think twice about wasting time and ended up using his time a lot more productively. Later, some of his friends wished to implement their own, but the setup process was lengthy and frustrating when new bugs were discovered. As such, after finding out about ECHacks, he came up with the idea of an app that would extend upon his Google Script: an app that have users keeping each other accountable, and perhaps even adding a competitive element that builds a powerful commitment among friends.

What it does
We named our app TimeTract because it reflects the properties of a contract, binding users to particular rules and regulations. Even though our app doesn't necessarily use explicit binding (where breaking the contract would have dire consequences), we believe that implicit binding through external motivators can be just as powerful.

Our app uses the RescueTime API to build a ranking system where users compete to become the most productive. We also plan to further gamify the experience to provide even more motivation (e.g. adding levels, achievements, etc.).

How we built it
Due to our limitations in app-development knowledge, we were limited to building our app as a web application. We used HTML, CSS and Javascript for the front-end, and we used PHP and SQL for the back-end.

The lack of time forced us to focus mostly on the front-end (which was especially difficult because neither of us was skilled at front-end development).

Challenges we ran into
Building such an app with PHP wasn't the most enjoyable experience for us. We spent a lot of our time debugging weird PHP behaviours and struggling with databases. We made the mistake of spending way too much time on the back-end, which inevitably led to a time deficiency when it came to the need to focus on the front-end.

We also were a bit too ambitious with our project considering the short amount of time at our arsenal and the lack of skills we possessed.

What's next for TimeTract
Many people associate Hack-a-thons with creating an app that never gets updated again. In contrast, we tried to build an app that we would genuinely be interested in using if one did exist. As such, we hope that we can either continue to maintain and develop a potentially powerful app (or at least inspire somebody more skilled to create a similar app of their own).
