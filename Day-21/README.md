# Day-21 | You've done it!

This is the last day of the 21 Days Challenge.

### Contents 
- [A quick recap of what we learned](#a-quick-recap-of-what-we-learned)
- [Links to other resources](#links-to-other-resources)
- [Your Final Challenge](#your-final-challenge)

## A quick recap of what we learned : 

1. Websites are responsive before we write any CSS.

    - By default websites are responsive it's us who ruin the Respnosiveness.

    - When we write CSS we set the things & they become fixed and don't adapt themselves as per the devices. 

2. When our layouts run into issues, we're at fault.

3. Usually (though not always), a desktop-first approach is the culprit :

    - Usually, I'm not gonna say always but usually a desktop first approach is the culprit to these issues.

    - we do something for large screen sizes. And then when we shrink things down, those layout decisions that we made, they're the things that are getting in the way, and we have to start overwriting things.

4. Writing mobile-first CSS

    - it tends to be the easier way to approach it as well, even if you only have a desktop layout to base things off of.
    
    - we're often overwriting things in the desktop first approach. You know, we set everything up & then we go into our media query & the max width, & then we're stuck over writing things for the small screens.
    
    - Whereas if we only put in that `display:flex;` and the `widths` inside a media query for that exact same puropse, we wouldn't even have to write anything outside the media query because everything would just work anyway.
    
        ![desktop vs mobile-first code](img/desktop-vs-mobile-first-code.png)

    - In the example, on the left there everything that you see is just resetting things back to the default that they already were. And as we've seen a few times now, if we start just by writing things the general layout in term with your fonts, your colors and your spacing, and that's it outside of media query, the mobile layout does a lot of progress. We get really far with it. And then we can come into our media queries and start adding things like `display:flex;`, adding in `widths`, getting things into more complex modes. And that way we don't run into any issues. We add complexity as our screen gets bigger. 

5. We looked at the basics of flexbox, but there is a lot more to it that's not covered in this course

    - One of the things I really like about flexbox is that you can do that.
    
    - You can start by learning the very basics of it. You can get things working
    
    - And then as you run into more complex situtations, You can start learning a little bit more about flexbox and adding in the extra thing that it can do but you don't need to know everything flexbox to get it, to work.
    
    - Just like you don't need to know everything. There is about CSS to change the color of your text or something like that. 

6. And you might have heard about Grid as well.

7. Don't rush things. 

    - There's a lot more to Flexbox. here is grid. 

    - One of the reasons that Kevin decided not to touch on grid in this course is because there is so much to grid. it is massive. It's huge.

    - If you're not comfortable with what you already know, do not rush things.

8. Mastering anything isn't about learning as much as you possibly can. 

    - Especially as fast as you possibly can. The faster you try & learn everything the less you're actually going to retain. 

    - That's one of the reasons that this course is in a way where we went through everything slowly over 21 Days, 
    
    - The Lessons could have been crammed all super quickly.

    - Kevin could have tried to plow through it as fast as he could, and probably done it in a quarter of time, but people wouldn't be reataining what they were learning along the way.

    - You wouldn't be practicing as much. And you wouldn't just be taking a break and doing something else which really does help you retain the information. 

    - He wanted us to practice what you've learned here. Even if you feel comfortable with it, He wants you to practice what you've learned here before you do anything else. 

    - And then slowly add on top, learn something new, learn it really well, be comfortable with it and then go onto the next step. So what is that?

9. So What's next ? 

    - Well He's not gonna leave you empty handed. So he is giving you this :

        ![Final Challenge](img/next-challenge.png)

        [Final Challenge Full Design Specs](final-challenge-specs.pdf)

    - The Next, The final last challenge that you will be doing as part of this course. 

    - And once you finish this, you've got through it. You're confident with it. 

    - Ofcourse go over under the discord, going to the solutions and post it and, see what other people are up to there as well. So you can do with it. And how far you can get it, if you get stuck, the [discord](https://discord.gg/9Rc6WNhNGJ) is there for you. 

10. After that... well, that's up to you. But I do have some suggestions!

    If you like Kevin's style of things :

    - He has a Youtube channel
    - Free HTML & CSS Crash Course
    - Responsive Web Design Bootcamp

11. Other amazing resources : 

    - cssgrid.io
    - frontendmentor.io
    - Free Code Camp
    - Tons of other amazing Youtube educators


## Links to other resources

Here are all the links I mentioned in the previous lesson 😊

### My stuff

- [My Youtube channel](https://youtube.com/kevinpowell)
- [HTML & CSS Crash Course](https://scrimba.com/course/ghtmlcss)
- [Responsive Web Design Bootcamp (premium course)](https://scrimba.com/course/gresponsive/)
- Follow me on [Twitter](https://twitter.com/KevinJPowell) & [Instagram](https://www.instagram.com/kevinpowell.co/)

### Other stuff
- [Free CSS Course](https://cssgrid.io/) by Wes bos
- [FrontEndMentor.io](https://www.frontendmentor.io/)
- [FreeCodeCamp](https://www.freecodecamp.org/)

### Other fantastic YouTubers to learn from
- [Brad Traversy](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) - If you're going to sub to one dev related channel, Brad's probably the right one

- [Web Dev Simplified](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) - High quality content covering HTML & CSS, Vanilla JS, React, and more

- [DesignCourse](https://www.youtube.com/user/DesignCourse) - A nice mix of front-end and design content

- [Program with Erik](https://www.youtube.com/channel/UCshZ3rdoCLjDYuTR_RBubzw) - Awesome Vue content

- [Florin Pop](https://www.youtube.com/c/florinpop) - If you enjoy live streams and incredible amounts of high-quality content

- [DevEd](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q) - Humour and high-quality dev content in one channel!

- [Weibenfalk](https://www.youtube.com/user/Weibenfalk) - High quality JS and React content

- [Coder Coder](https://www.youtube.com/channel/UCzNf0liwUzMN6_pixbQlMhQ) - Nice, high quality front-end videos

- [James Q Quick](https://www.youtube.com/channel/UC-T8W79DN6PBnzomelvqJYw) - HTML, CSS, JS and more

- [Flavio](https://www.youtube.com/user/copesc) - Good quality JS content

- [Colt Steele](https://www.youtube.com/channel/UCrqAGUPPMOdo0jfQ6grikZw/videos) - HTML, CSS, JS 

And there are so many I'm forgetting! This list could be incredibly long, so please let me know over on Discord if you have any recommendations of people that I've forgotten (including yourself if you have a channel, and sorry! lol).

## Your Final Challenge 

This challenge reinforces everything we've looked at.

Many parts of it are similar to what we've already seen, but there are a few sections that have some new twists. That said, everything in this challenge can be completed with what you've learned so far, and if you can make this page responsive, you're rocking it!

#### A few considerations
I've only provided a desktop version of the design (except for one section). Despite this, I want you to **take a mobile-first approach.**

One of the most common reasons I hear as an excuse for writing desktop-first is that's what the design gives them. We've seen why we can still tackle things mobile-first despite that, so let's put it into practice!

**The black box around the design is the viewport.** The content inside should be limited to the max-width given in the design specs, but the backgrounds should extend to the edges of the viewport no matter the size.

**The PDF outlines 2 specific breakpoints to use.** You can modify them a little if you feel that it's appropriate, but you should aim for those ballparks.

**Don't feel any shame in going back over previous lessons if you get stuck.** The only rule is if you do have to go back, do not copy any paste any code that you've already written, or that you downloaded from my finished versions. You just spend 3-weeks at this, don't cheat yourself! Go and watch the video, and then code it yourself. Reinforce what you learned by writing it out again!

Have fun with this, and be proud of the progress that you've made!

(you'll get access to the solution eventually, but it's going to be awhile. I want to make sure you take a shot at it first)