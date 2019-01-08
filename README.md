## Personal

### About Me
I am classically trained as electrical technologist and computer programmer. I am an avid fan of comic books, board games and DOTA. I write fantasy and science fiction short stories when I am inspired. I also draw and create video games when I am felling creative. I often undertake research projects that start off as a crazy ideas.

### Writing
A collection of my sci-fi short stories

### Artwork
A small sample of choral paintings and pencil drawings

## Research
My research projects are all done on my own time, general with the assistance from academia and are often not more then just crazy ideas I wish to explore farther.

* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Screeps AI`
* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `VR Bio Feedback`
* ![#FF9205](https://placehold.it/15/FF9205/000000?text=+) `Geo Adventures`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `ANTS`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `SPIDERS`

### Screeps AI

What is [Screeps](https://screeps.com/) you may ask?

> "It’s an open-source sandbox MMO RTS game for programmers, wherein the core mechanic is programming your units’ AI. You control your colony by writing JavaScript which operate 24/7 in the single persistent real-time world."

Why Screeps? The most interesting thing about AI deployment around screeps is the built-in GYMS. Also, the real time game loop creates a restriction not often seen other AI development where the Training and Execution must be done in a timely matter. This is often in very small time steps over a long period as the game operates in ticks with a fixed amount of CPU time. 

Check out the [Source Code](https://github.com/RGBKnights/screeps) for different version of static systems I have created that the AI is attempting the learn from / play against. 

NOTE: Some maybe incomplete or missing files required to compile. As I was using a local NPM package at one point.

Prior Work, Interesting Developments, and References:
* https://blog.openai.com/competitive-self-play/
* https://arxiv.org/abs/1810.08575
* https://arxiv.org/abs/1810.12894
* https://arxiv.org/pdf/1810.12282
* https://arxiv.org/abs/1807.04742
* https://github.com/sploreg/goap

### Geo Adventures
The crazy idea behind Geo Adventures came when I was first introduced to Pokemon GO before its release seeing and marveling at the AR functionality but after release seeing that most people turn it off as it was not more then a gimmick that drained their batteries faster. I was dreaming about kind of game could force to the player to use AR and what types of issues is AR having in a outdoor setting that are preventing good AR games.

The basic of game itself was an RPG fantasy settings overladed on real life. This forced the player to go outside to for collections to gather resources (battling against those whom protect it) needed to build defence for their own base, while also collecting keys to other bases (built by other players) to battle (now or later with key) to claim their loot.

After examining some of the previous work in the field it became clear what the major issues would be. Accurate geo-maping of the area was required to even get the basics up and running using the players location. This meant knowing the players coordinates (include their height above sea level, not just lat and long) to with in a 1 meter or less. Not only the positioning of the player was a challenge but understanding the dimensions of the virtual environment in relation with the physical one.

Although some really great work as been done in this field with the current technology in the mobile devices means there are lots of issues, these include:
* Moving virtual objects  dynamically in the scene (ie. NPCs that walk around the environment)
* Overlaying / Underlying virtual elements into the scene with moving real objects. (ie. a car drives in front of the virtual object)
* The time delay to update virtual elements to match the real world (ie. what happens when the physical and virtual world disagree)
* AR mobile devices battery drain (ie. constantly looking through the AR lens will drain the battery very fast)

As of late 2016 all work is on hold and the game is archived until better solutions to these and other technical challenges are worked out. Although upon another review of the issues in late 2018 things are making rapid progress with [ARCore](https://developers.google.com/ar/).

Keep and eye on [RPG.global](http://rpg.global/) as that is project's current home.

Prior Work, Interesting Developments, and References:
* https://pdfs.semanticscholar.org/33ae/e3df888e781a4d040f8691dff02878a8fd6a.pdf
* http://dbis.eprints.uni-ulm.de/1028/
* https://doi.org/10.1016/j.procs.2016.08.017
* https://developers.google.com/ar/

### Virtual Environment Bio Feedback
The crazy idea to combine these two different technologies came about after a 6 hour VR session when I thought to my self
> I wish the game know I was getting tried and would change the difficultly so I could have kept playing...

At that light bulb monument I was not drawn right away to Electroencephalogram (EEG) technologies exploring options to measure the bio feedback of the player as a result of this research the plans evolved into combing VR and EEG together to allow the VR environment BIO and Mental feedback about the player. VR seemed to be the best fit as you would need to wear a headset to capture the EEG readings so might as well wear a VR headset. Although this did have the unexpected benefit of EEG component offsetting weight of the VR component making the overall headset easier to wear for longer periods. After Successfully creating a proof of concept with a mobile device VR adaptor and home made EEG kit it time to upgrade to more industry standard technology and expand the original idea. I am currently waiting to acquire a Emotiv Epoc+ (EEG device) and Oculus Rift (VR device) to continue the research. Manly because Emotiv have create commercial headset and there [SDK](https://emotiv.github.io/cortex-docs/#met-event) can produce the basically the same set of states my models can.

Prior Work, Interesting Developments, and References:
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3990628/
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4957988/
* https://www.ncbi.nlm.nih.gov/pubmed/27547552

### ANTS
My ANTS (which is short for Autonomous Neural Training and Sharing.) research started shortly after my SPIDERS research. With out any knowledge of AI and various sub fields years ago I stumble into the beginnings of neutral network design without understanding what a neutral network was. After working on my SPIDERS research I wanted to expand upon the ability for the system to learn and this where ANTS was born. Its greatest achievement was the self assembly of a system that could analysis .Net assemblies for there type information and create an abstract syntax tree (AST) of the resulting flow of types from different functions and was able to predict and then test chains of these function calls. I even moved all code into Azure for some large scale tests of running through the default .Net library's, but in the end the cost of the project was too much to continue at scale so research was archive on 2013. 

### SPIDERS
In the early years of the internet there was no google. (I know hard to believe...) In these days where you got your site list from was really a dog's breakfast of different sources. It was not till the introduction of web crawlers that true search engines where created. When all this madness of who have the best web crawl was going on I was interested by the idea of crawling code the same way these crawlers where out there exploring the web. I create my own version of a crawler SPIDERS (which is short for Self Propagation for Identification of Data Equality and Relationships in Subsystems) In the end it helped me explore the C and Assembly languages. I also created a version that could explore the web the same way web crawlers do, and still use it to this day to do deep dives into the search engines.

## Projects
These project where born out of a personal or professional need or the want to productize a past research item. With most of my free time going to support the High Ground Vision project.

* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `High Ground Vision`
* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Boardgame.io`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `GenerationX`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Expeditio`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Rail Yard`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Bottalk`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `XSLT Templates`

### High Ground Vision

[HGV](http://highgroundvision.com/) started as a side project of a group of DOTA2 fans and it still operates that way. We have a number of niche tools for DOTA2. We’re also happy to share our knowledge with the community by open sourcing our stack. Development is done by volunteers contributing in their free time. Our primary focus is around [Ability Draft](http://abilitydrafter.com). We also volunteer our time to moderate AD [Reddit](https://www.reddit.com/r/Abilitydraft/) and Discord. I have a number of libraries created in C# for interact with Steam and DOTA2 for stat collection and analysis.
* [Basilius](https://github.com/HighGroundVision/Basilius) - .Net clients for download hero, ability, and items from daily cache provided by DotaBuff.
* [Daedalus](https://github.com/HighGroundVision/Daedalus) - .Net client for interacting with the STEAM api. This is focus around Dota 2 endpoints.
* [Crystalys](https://github.com/HighGroundVision/Crystalys) - .Net client for interacting with the STEAM Server and Dota Game Coordinator
* [Hyperstone](https://github.com/HighGroundVision/Hyperstone) - A repository of the images for Dota 2. This includes Heros's banner, profile and icon. Images for abilities, items, runes, wards, and some miscellaneous.
* [Desolator](https://github.com/HighGroundVision/Desolator) - The source code to the Ability Drafter web application.
* [Nullifier](https://github.com/HighGroundVision/Nullifier) - .Net desktop console application to collection stats from AD matches for the Desolator project.
* [Butterfly](https://github.com/HighGroundVision/Butterfly) - The source code to the Team Coordinator web application.
* [Tango](https://github.com/HighGroundVision/Tango) - The source code to the HGV web site.

### Boardgame.io
(Contributor)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Generation X
(The ability to correctly and consinently provision arifacts into a SharePoint environment)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Expeditio
(The Dungeon Master's toolkit)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Rail Yard
(A next generation MVC framework for PHP)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Bottalk
(Message walls for IoT before, since replaced with twitter)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

###  XSLT Templates
(Rendering client side by combing XML data streuctures with XSLT templats client side to produce the final web page)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

## Games
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Boundless`
* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Ur`
* ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `Lusus`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Trafic`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Fishbowl`
* ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Camthalion of Andrill`

### Boundless
(procedurally generated model of the galaxy)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Ur
(based on the royal Game of UR)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Lusus
(Chess with hidden infomation)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus viverra massa at tempor. Nulla ullamcorper semper augue id semper. Praesent eget urna tellus. Nam eleifend lectus commodo cursus rutrum. Vivamus pulvinar molestie sem, vel posuere arcu tincidunt vitae. Vivamus quis hendrerit nunc. Nulla id lorem ac velit finibus posuere. Curabitur laoreet massa vitae maximus finibus. Maecenas ac egestas tortor, et pulvinar erat. Pellentesque venenatis eros lectus, ac facilisis sapien maximus eu.

### Trafic
Traffic was created in late 2010. With the release of XNA 4 and now being able to publish a game on Windows Phone 7 as well as Xbox 360 we find ourselves building another simple game to publish on both Xbox 360 and Windows Phone 7. The game consists of a player controlling traffic lights of a pre populated city to get the average commute time below the goal. This requires using the tools of a game to figure out bottle necks, open roads, and flow patterns. The game starts off with towns and ends in a metropolis.

### Fishbowl
Fishbowl was created in one week over my Christmas break in 2008. With the release of XNA networking and the 360 deployment system we were very interested in getting a simpler game together to publish. Fishbowl was born! based on a Nut Harvest a very addicting XNA game that was also very simple. The goal of this project was to figure out and test XNA networking. It was very interesting to deal with network prediction to get the game to work correctly. The game consists of a player controlling a fish to eat the most shrimp before the other fish. Look out for power ups and bombs! Fishbowl has accumulated over 20,000 trail downloads since January 2009. As well as covering the cost of the original assets.

### Camthalion of Andrill
Camthalion of Andrill was created in early 2005. It was created with RMXP an engine used by hobbits developers. I have created many RGSS scripts for the community over the years including the standard development kit (SDK) and my famed squad based action battle system (SBABS), but this is my first game created with this engine. The game consist of an RPG adventure to find a sword your father left in a temple when he was kill there. The sword belonged to the King and he asked you to return it to him. The game included many of my own scripts and was more of a test bed then a real game.

---

© 2019 - Venatio Studios