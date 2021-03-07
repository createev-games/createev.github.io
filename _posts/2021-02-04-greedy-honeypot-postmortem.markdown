---
layout: post
title:  "Greedy Honeypot in Rock - Postmortem"
date:   2021-02-04 12:50:11 +0300
categories: games devlog
---
Hi all! Following advice from Noa's video [29 game jam tips](https://www.youtube.com/watch?v=BnuJ2EItJDY) i would like to share my experience of participating in the first ever jam of mine - Blackhtornprod #3.

## Executive) summary / TL;DR
I released a game! It is the first ever finished game of mine, thanks to Noa and all of you!
### What went well:

* First 2.5 days were spent to find addictive fun game loop. Brackeys, Noa and all other gurus were right - you first need to use cubes and polygons but find addictive loop and only AFTER that you enrich it with theme, art etc. 
* Being brutal on scope and my abilities and skills. Even with me cutting everything which was more than beginner level from the scope - i still had to do many things for the first time: like animations, adding audio and music, editing sprites, creating builds, submitting to itch to name a few) And each of these involved research, trial & error etc. 
* Using source control - there were times when i moved back to previous versions and/or forked some different ideas. And now it is the source of truth for this Devlog!
* Adding my original music and using my non-beginner music skills to make game unique (that's why it is "In Rock"). 
* Having fun and involving my kids in the process. Even that some of their help did not make it to final product it was a fun and great creative experience. Some of collaboration you can hear in "N-yah-m" sounds...)
* Somehow i managed to squeeze couple of hours on weekdays (besides empty Thursday) by either pushing forward or delegating most of creative and/or time-consuming work from my dayjob. I am still paying it back though... this week is tough...

### What went not so well:

* You need art, music, sounds, animations, code, prefabs, scenes, and a lot more to complete even the simpliest of all games like the one i created. 
* And if coding and basic game development in Unity was kind of okeish, image editing and art was complete pain. And not just from aesthetic point of view but from tool usage skills point of view! I spent some time (few months) to learn Unity but zero(0!) hours to even learn GIMP or Inkscape or PS... I literally downloaded those for the first time during game jam...

Below I will describe Final result, process and finish with Lessons learnt in the end.

## Final result
I would start from the end - i released a game! yes, it is tiny, little, with clunky graphics and googled art, but it is a completed game with unique experience and addictive game loop. 

The game is about one Greedy Honeypot who loves honey and Rock'n'Roll. But is scared to death by bees...) You collect honey and dodge from ever growing army of bees. Nice.)

I am sincerely interested in your feedback and ratings: [Greedy Honeypot in Rock](https://itch.io/jam/blackthornprod-game-jam-3/rate/897546)

## Process
### Find FUN game loop:
I guess it was a wise decision to spend both Saturday and Sunday on trying to find a fun game loop. From commit history you can say I quickly went from:

* Player movement - of course)
* Crystals (then - Honey) to collect and score
* Crystal to spawn enemies after they are collected

Then I experimented with different types of enemies:

* A box which moves to player, hits when approaching, take away crystal, puts it back on place and attacks again... pretty complex, i know...
* A Kamikaze box which moves to player and hits and destroy itself. It was actually the first time i felt there is a fun loop in the prototype. In fact this is what i wrote in commit description: FUN with kamikazes!!! good sign. 

![FUN with kamikaze](/assets/posts/2020-02-04-greedy-pot/greedy-pot-image1.png)

From then i still spent rest of Sunday and Monday morning on different experiments: 

* Returner who just hits, picks up crystal and place it back
* Bullets and turrets which appear on crystal place
* Carousel appearing on crystal place which rotates and hits on touch
* Random direction straightly firing cannon. 
* And of course back to FUN with Kamikazes 

Below is commit history of that stage (newer commits at the top)
![After 1](/assets/posts/2020-02-04-greedy-pot/greedy-pot-image2.png)
![After 2](/assets/posts/2020-02-04-greedy-pot/greedy-pot-image3.png)

### Playtesting
At this point I invited my kids (and wife) to do some play testing. Watching how it was going gave my a confidence we are on something addictive and fun. And also provided some (constructive) input)

### Theme for game loop
You can see that as soon as i was back to "FUN with kamikazes" I started to think of theme and what real life behaviour this prototype could represent... and voila - next commit was already "Bee and animations". Unfortunately I can not recall now how Bee-theme came to be but thinking process was: here is prototype, what real life situation could represent it. 

Since then actual production started - i was adding sprites and animations, tweaking images and also created UI. 

### Music and audio
My another hobby is music. In fact coincidentally my band released a new Single right on Friday, Jan 29, the day of game submission)) Not to plug myself but rather to share my creative work in full transparency this page contains links to Apple Music, Spotify etc. for this single: https://band.link/Lypmd

So I had a little rock'n'roll theme in my head during that week and i decided to use it for the game music. And so I went on and recorded the theme using my Fender Stratocaster guitar and Logic Pro X. It was Wednesday, 27th.

Then sounds were recorded, including ZZZ sounds of bees, Nyam sounds (when pot "eats" honey) with my son - it was of course absolute fun to mess with different sound ideas with my 6yo old). 

### Bug fixes, art and submission
There are zero commits on Thursday - indeed i was totally busy and did nothing besides reading itch.io and unity manuals on how to create builds and submit to itch.io. 

And then real pain started... 

* Icon for the game? i opened GIMP and started to do some awful moves... 
* Splash screen? 
* Image manipulation? 
* Better background? 
* Smoother edges? 

So i found i lack any GIMP skills whatsoever => and they are required even if all your graphics is vector based and/or imported. 

I spent whole Friday building, fixing bugs and rebuilding a game. I guess game was submitted at least 7-8 times before i decided it is clean enough to be published. Every time some little bug was found (by me).

## Lessons learned

### New game development skills I tried for the first time in this Game jam:
There is a tremendous benefit from this game jam for me trying (and applying!!) new skills. To name a few below are areas i never touched before in gamedev:

* Animations - never done any of this
* Audio and music
* Sprite editing, GIMP, Inkscape
* Creating builds for different platforms in Unity
* Preparing game page in itch.io and submitting a game

### Process

* Empty calendar before game jam starts. I can not imagine having any success without deliberate focus on making sure there are time blocks every day for this
* Find the fun first! I strongly suspect if there was a fun in prototype i would not finish it at all.
* Play test early and often - my kids were play testing the game and i gained so much insight just by observing them (and interviewing).

### Skills

* Even if you work in a team and/or use 3rd party assets and art - you still need some basic skills of image manipulation etc. 
* So you have to have some basic skills across different areas (that's why gamedev is hard).
* Use your strengths to make game unique - I guess programming and music are what i know best that's why i plan to use those skills to bigger extent next time to shine through not so great other areas and make games unique. 

And, finally, as First Tree maker said: Finish the f...g game!))

Thank you all and i hope you find my thoughts valuable and useful for your gamedev journey. 

Of course i will appreciate if you check my tiny little game and provide feedback and rate it too: [Greedy Honeypot in Rock](https://createev.itch.io/greedy-honeypot-in-rock).

All the best,  
Andrey "Createev"