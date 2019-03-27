---
title:  "Castle Arena"
subtitle: "Video Game Concept"
author: "Stuart Wilson"
avatar: "img/authors/author.png"
image: "img/Castle_Arena/Castle_Arena_post_icon_2.jpg"
date:   21st February 2019
permalink: "Castle Arena"
---

<p style="font-size:100%;">
My next video game project following after Pinball Roulette is Castle Arena. A wave-based survival arena style game about a castle ruins setting. My goals for this project was to learn about the landscaping tools in Unreal Engine as well as develop my video game design skills.
</p>

<p>
The goal for the player is to survive the oncoming waves of enemies for as long as they can. Enemies can be defeated by using melee or magic attacks. Enemies spawn inside the arena, where player and opponents can move about freely. Health pickups can be found around the map in various locations and can be acquired by either the player or the enemy characters.
</p>

<p>
This project was my adaptation of the last segment in the Udemy course by Christopher Murphy.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="https://vimeo.com/318697115"><img class="example-image" src="img/Castle_Arena/Video_Icon_2.jpg" alt="" height="370"/></a>
Gameplay Trailer
</i></p>

<p>
<b>Player Controls</b><br /><br />
Player movement is based on the AWSD system. Left click for melee combat swings, multiple clicks chain together combo swings. Right click for casting a ranged magic attack. Aiming of melee and magic attacks is based on cursor location. Spacebar allows for player jumping.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_1.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 1"><img class="example-image" src="img/Castle_Arena/Castle_Arena_1.jpg" alt="" height="370"/></a>
Final scene view 1
</i></p>

<p>
<b>Game Play</b><br /><br />
The player must survive as long as possible against waves of enemies, each wave spawning an increasing amount of enemies and enemy types. The next wave only begins once all enemies of the current wave have been defeated.
</p>

<p>
The player has two methods for killing enemies, melee combat or magic attacks. Melee combat is at close range and can deliver multiple blows in succession. This is most easily done by chaining melee attacks together, swinging left to right.
</p>
<p>
Magic is a ranged attack which will bounce around the arena until it hits a player or dissipates. Magic does have a longer casting time compared to melee combat. Both magic and melee combat deal the same damage.
</p>

<p>
Health pickups are available around the map which will instantly heal an amount of health for any character that walks over it. Health packs help with the survival nature of the game and also impacts player decision making.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_2.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 2"><img class="example-image" src="img/Castle_Arena/Castle_Arena_2.jpg" alt="" height="370"/></a>
Final scene view 2
</i></p>

<p>
<b>Landscaping</b><br /><br />
Learning about landscaping in Unreal filled in a lot of gaps in my game environment knowledge. It also completes the list of components used in crafting out the base of game environments in Unreal Engine 4. The list being; landscaping, BSP (binary space partitioning) geometry and static meshes.
</p>

<p>
I picked up on sculpting out my own landscaping quite quickly as the core concepts of its implementation are simple. Using the various sculpting tools were a lot of fun and I could see myself spending hours constructing out a scene. Though the concepts are easy to learn, I can see there is a lot of depth and practice needed to fully utilize these tools.
</p>

<p>
From here, it steps up a lot with landscape texturing. Some of the elements of texturing I learnt were; texture layers and blending, displacement mapping and level of detail.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_3.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 3"><img class="example-image" src="img/Castle_Arena/Castle_Arena_3.jpg" alt="" height="370"/></a>
Final scene view 3
</i></p>

<p>
I just covered two different texture layers, grass and dirt. Adding in more layers help enhance the detail in the scene as well as enrich the environmental setting (seasons, weather, geographical locations etc.).
</p>

<p>
Displacement mapping really impressed me, it really does have a huge impact on the perspective depth of the texture. I like the way it adds weight and detail to a scene without adding in more static meshes. It does have an associated cost however with the added/modified vertices of the landscape.
</p>

<p>
Level of detail (LOD) is something I knew of from playing video games, but I never really figured out how it was done. I am sure there are more sophisticated ways of implementing LOD, where here, in this case, the texture is scaled based on the distance from the camera.
</p>
<p>
Smaller texture tiling at closer distances to the camera (giving more detail), and larger scaling of the texture in the distance. Having additional texture map images of various sizes/detailing could be swapped in and out based on camera distance would be an improvement on this method.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_4.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 4"><img class="example-image" src="img/Castle_Arena/Castle_Arena_4.jpg" alt="" height="370"/></a>
Final scene view 4
</i></p>

<p>
<b>Foliage</b><br /><br />
Follow from landscaping comes using the foliage tool. Unreal's foliage tool is basically painting on a canvas, except for painting with paint, its 3D meshes. It is very easy to get carried away with because of how easy it to use and how effective it is at making the scene come alive.
</p>
<p>
Here I used it to place trees, grass, plants and various flowers. In some places, the foliage really stands out in the scene and in others, I have overused it.
</p>

<p>
It is very easy to decrease the performance of a build with excessive foliage usage, where finding the balance between landscaping, texturing and foliage is key. Figuring out the best usages across the three, and the cohesion between them all is something I would like to develop in the future.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_5.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 5"><img class="example-image" src="img/Castle_Arena/Castle_Arena_5.jpg" alt="" height="370"/></a>
Final scene view 5
</i></p>

<p>
<b>Lighting and Post-Processing</b><br /><br />
One of the keys focuses on lighting in this scene was casting interesting shadows, given the nature of a variety of wall heights and shapes. I could have pushed a bit and given the directional light more of an angle, but I held back not wanting to obscure gameplay areas.
</p>

<p>
I gave the scene an overall warm orange hue to align with the time of day. This does make it somewhat wash out the scene a bit with the static meshes largely being a light brown bronze colour.
</p>

<p>
As a result, I put a lot of effort into ambient occlusion to help make clearer distinctions between the various objects in the scene and help define gameplay areas easier. Overall I feel the lighting and post-processing unified the scene and enhanced the consistency of the design.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_6.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 6"><img class="example-image" src="img/Castle_Arena/Castle_Arena_6.jpg" alt="" height="370"/></a>
Final scene view 6
</i></p>

<p>
<b>Critique</b><br /><br />
Texture layering and blending could be improved. Some of the texture blending were not as smooth as I would have liked. Getting better with using the painting techniques as well as adding in more texture layers would help with this.
</p>

<p>
I overused the foliage tool and needed to add variation. Variation in the meshes used, but also more so in terms of consistency and scale. With experience, this is something I will get a better feel for.
</p>

<p>
Gameplay has a lot of areas for improvement. Some of the existing mechanics are a bit clunky. The animation notifies for melee combat are not as reactive or accurate as they need to be. Using a raytracing method would improve this. As a whole, this is a vertical slice for a game, a concept. So using these methods to just get the game working I am ok with.
</p>

<p>
Game balance is also something that would need to be revisited. Magic is much too strong to use verse melee. This is a combination of the fact that melee is underwhelming in general and needs a lot of quality of life improvements. Adding in more clarity and responsive feedback when dealing damage would vastly help with this.
</p>

<p>
The castle design does not really make any sense. Some of the wall structures do not explain what the castle once looked like before it began falling apart. I think the scene looks really good, but some of its elements do not make for a believable or logical layout.
</p>
<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/Castle_Arena/Castle_Arena_7.jpg" data-lightbox="the_Castle_Arena_set" data-title="Final scene view 7"><img class="example-image" src="img/Castle_Arena/Castle_Arena_7.jpg" alt="" height="370"/></a>
Final scene view 7
</i></p>

<p>
<b>Conclusion</b><br /><br />
This project was an excellent exercise into video game prototyping as well as introducing me into landscaping. Some of the methods going into designing the game are no way near production ready, where this was not the primary focus.
</p>

<p>
The idea is to bring something to life and iterate through the process and improve each element as we go. Test to see if the concept works in a barebones format in order to successfully figure out if its a workable design.
</p>
<p>
I think there is a lot of potential with a design like this with better implementation of the gameplay mechanics, however, I am happy to leave this as concept design and work on new game prototypes.
</p>
