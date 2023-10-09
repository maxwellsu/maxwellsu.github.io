### CFBD API

I recently created a vignette for the College Football Database: [https://maxwellsu.github.io/st558-project-2/](https://maxwellsu.github.io/st558-project-2/)

In this vignette I wrote functions to query various parts of the API, where the general structure is to build a URL from the user-specified parameters. The down side of this is that the value of certian parameters must be specific (for example, only certain abbreviations for athletic conferences are accepted), however, this reduces the amount of computations that must be done client-side by asking the server to do the majority of the filtering.

I then used the functions I wrote to perform a bit of exploratory data analysis into the College Football Database. One of the things that I looked at was the approach to recruiting for top teams. In the modern day of college football, it is just as important to recruit within ones backyard as it is to cast as wide a net when gathering recruits. As such, it was interesting to see that of Alabama's three most recent title-winning teams, the highest proportion of athletes from in-state in any team was a bit over one-third, whereas both of Georgia's national championship teams featured roughly 60% of their athletes coming from the state of Georgia. Being two of the most preeminent teams in college football, especially in the SEC, it is suprising to see them take such a different approach to recruiting. With the transfer portal and NIL being even bigger factors in college football roster construction, I'm interested to see how this changes going into the future.

A link to the github repository: [https://github.com/maxwellsu/st558-project-2/tree/main](https://github.com/maxwellsu/st558-project-2/tree/main)
