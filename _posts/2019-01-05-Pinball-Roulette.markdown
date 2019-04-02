---
title:  "Pinball Roulette"
subtitle: "Video Game"
subsubtitle: "Unreal Engine 4, Blueprint"
author: "Stuart Wilson"
avatar: "img/authors/author.png"
image: "img/Pinball_Roulette/Pinball_Roulette_Post_Icon_2.jpg"
date:   7th January 2019
permalink: "Pinball_Roulette"
---

<p style="font-size:100%;">
My first complete game in Unreal Engine 4, classic arcade pinball with a small roulette twist. Every thirty seconds the centre wheel lands on a random coloured triangle. Red results in inverted flippers, yellow provides a helping paddle centre stopper and green pops two fresh new balls into play.
</p>
<p>
The goal is for the player to achieve high scores by hitting as many objects as possible within the table by the ball. Rounds are over when the ball goes past the player's paddles, where each game contains three rounds. Each round starts anew with a fresh ball.
</p>
<p>
This project was my adaptation of the Pinball project as part of the Udemy course by Christopher Murphy.
</p>

Check out and play the game for free at:
<br /><br /><i><b>
<a class="linky" href="https://bloodragoon.itch.io/pinballroulette" target="_blank_">https://bloodragoon.itch.io/pinballroulette</a>
</b></i><br /><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="https://vimeo.com/309670547" target="_blank_"><img class="example-image" src="img/Pinball_Roulette/Video_Icon.jpg" alt="" width="100%"/></a>
Gameplay Trailer
</i></p>

<p>
<b>Player Controls</b><br /><br />
The control scheme consists of using Left and Right Ctrl keys for operating the respective Left and Right paddles. Hold and release controls on the Spacebar to launch a new ball into play at the start of each round. Left and Right arrow keys offer a way to tilt the table but are limited to three tilts per game.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Pinball_Roulette/Pinball_Roulette_Screenshot4.jpg" data-lightbox="pinball_site" data-title="Main Menu"><img class="example-image" src="img/Pinball_Roulette/Pinball_Roulette_Screenshot4.jpg" alt="" width="100%"/></a>
Main Menu
</i></p>

<p>
<b>Level Design</b><br /><br />
My primary focus for the design of the pinball table was to enable gameplay clarity. I did not want to overload the player from a visual perspective as pinball can be a reaction based game - having too much distracting content could negatively impact the overall experience for the player.
</p>
<p>
As a result, I kept the colours simple with high contrast. Maroon table top with cyan gameplay objects (maroon and cyan being complementary colours), greys and silvers for the metallic aspects of the game (mostly gameplay aspects)  and lastly whites for visual aesthetics (non-game play impacting elements). These colour choices are all used to differentiate the elements within the game cleanly and allows for easier readability of the systems in place.
</p>

<p>
Decals are used to help with spatial recognition and the flow of the ball space. Adding simple lines create outlines which group gameplay content as well as adding visual flair. Since the camera is fixed, the table decals also bring out a little bit of depth to the scene
</p>

<p>
Lights and neons are used to supplement additional information to the player. Information which is not necessarily needed to be exposed to the player, but is quite helpful for feedback (such as balls remaining). I also wanted a very clean HUD which means if I wanted to convey more information/data to the player it had to be visually done in the game. I am quite lucky since Pinball Tables are stationary and have a lot of real estate for adding in signs or visual cues on the non-gameplay parts of the table.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Pinball_Roulette/Pinball_Roulette_Screenshot1.jpg" data-lightbox="pinball_site" data-title="Gameplay Screenshot 1"><img class="example-image" src="img/Pinball_Roulette/Pinball_Roulette_Screenshot1.jpg" alt="" width="100%"/></a>
Gameplay Screenshot 1
</i></p>

<p>
<b>Game Mechanics</b><br /><br />
The idea behind adding in the roulette wheel was to help spice up the gameplay, granted it was at the cost of introducing some RNG to the game. The reason for this was because the pinball gameplay in itself is ok when you have stuff to do... which is not always the case.
</p>
<p>
Sometimes the ball can just bounce around endlessly without any need for input from the player, which is great for a high score, but not so much for engaging gameplay. There were other approaches I could have taken to combat this problem (more interactive objects on the table, adding gameplay depth with more player input etc) where I chose this method as it was a great way for me to learn and design a new system from scratch whilst relating to existing mechanics (results of the wheel supplementing exisitng mechanics).
</p>

<p>
All the objects in the table are designed to add gameplay in some shape. The most simple form for this is to impact the movement of the ball in some form. Bumpers are great for flinging the ball in sporadic fashion at high speeds. Sling Bands temper the ball speed and direction. Booster Pads for re-direction and lastly lane Kickout Hole for predictable repositioning.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Pinball_Roulette/Pinball_Roulette_Screenshot2.jpg" data-lightbox="pinball_site" data-title="Gameplay Screenshot 2"><img class="example-image" src="img/Pinball_Roulette/Pinball_Roulette_Screenshot2.jpg" alt="" width="100%"/></a>
Gameplay Screenshot 2
</i></p>

<p>
<b>Player Feedback</b><br /><br />
One aspect of game development which I really like exploring is adding in 'juiciness' that improves the player's satisfaction, feel and feedback for the game. Mostly these details go unnoticed as they just exist to enhance the player's experience and have little to no impact on gameplay.
</p>

<p>
One detail I wanted to add very early in development was a glass shattering effect when the ball hits the table top. This has no gameplay merit (granted it could) and is purely for visual effect. It increases player satisfaction by reinforcing that making the ball fling off at high speeds is a good thing - destroying the table implies you are playing really well and you are able to project the ball beyond what is meant for the table. This is unrealistic in a real-life pinball machine, which also helps with the 'wow factor'.
</p>

<p>
Bumper activation had a lot of components for which I could add juiciness. Activation lights identify the bumper has been activated and the explosive sparks particle system conveys the metal on metal interaction between the bumper and ball.  
</p>

<p>
Other smaller examples include the adding in a small smoke particle system to the Kickout Hole. This does a nice job of enhancing the feeling that the ball has been shot out with great force like a rocket. There are numerous sound effects identifying the different gameplay elements, from bonks to dings. The most satisfying is the sound of the ball rolling sound against the table. I added in pitch and adjustments with ball speed, this really improves the perception of the speed of the ball. Making it sound faster than it really is.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Pinball_Roulette/Pinball_Roulette_Screenshot3.jpg" data-lightbox="pinball_site" data-title="Gameplay Screenshot 3"><img class="example-image" src="img/Pinball_Roulette/Pinball_Roulette_Screenshot3.jpg" alt="" width="100%"/></a>
Gameplay Screenshot 3
</i></p>

<p>
<b>Critique</b><br /><br />
I personally think I implemented some really nice mechanics and design elements. However, the game is definitely not without its flaws. I had the right idea about some of the concepts I implemented but could have been executed better or explored in different ways.
</p>
<p>
The roulette wheel is an example of this, as the wheel itself is somewhat interesting, its outcomes can be lacklustre. Getting the centre stopper multiple times in a row is pretty uninteresting. Adding in more outcomes with more interesting or gameplay impacting events would help a lot. Maybe even add in new game elements which the player has control over that impact on the roulette wheel itself.
</p>
<p>
The table could have had more interesting objects added to it as the table feels a bit too bare in places. The core gameplay is not really satisfying as there are still moments of uninteresting moments where the player is not engaged in gameplay. This is due to table design and there not being many channels/paths or interesting sub-goals within the table. Adding reasons for the player to direct the ball in particular locations at a given time would help introduce skill and timing to the game.
<p>
</p>
Visually some of the decals designs look out of place with each other. Some use thicker lines than others, some being curvy in nature distracts from the straight lines. This was partly due to the limitation in my ability to design decals that matched alongside the decals in the asset pack.
</p><br />

<p>
<b>Conclusion</b><br /><br />
I am happy with the completion of the project and the overall design (granted its more pinball that roulette). My goal was not to make the most engaging pinball game ever or the prettiest. It was to complete a full video game and to learn more about the full game development process. I feel like I completed that goal successfully as well as having a lot of fun along the way.
</p>
