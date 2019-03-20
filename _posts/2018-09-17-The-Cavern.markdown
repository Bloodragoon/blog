---
title:  "The Cavern"
subtitle: "Game Environment"
author: "Stuart Wilson"
avatar: "img/authors/author.png"
image: "img/The_Cavern/thecavern_post_icon_2.jpg"
date:   "18th September 2018"
permalink: "The Cavern"
---

<p style="font-size:100%;">
Having explored the world of architectural design with the 'The Room' project, I decided to move on to something more fitting as a game environment. The purpose of this project was to practise and develop the skills and knowledge I have learnt so far about environment creation. </p>
<p>
Browsing through the Epic Marketplace for assets, I came across an asset pack which piqued my interest and gave me the idea of making an underground cavern themed game environment. The assets used are from Epic Games 'Soul: Cave' market place asset pack.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_9.jpg" data-lightbox="the_cavern_set" data-title="Final Preview"><img class="example-image" src="img/The_Cavern/thecavern_9.jpg" alt="" height="370"/></a>
Final Preview
</i></p>

<p><br />
Like with my previous project, I started with scoping out the design space and defining core visual elements. I really liked one of the statue meshes in the asset pack and wanted to make it the centrepiece of the design. With the statue and caverns theme, I felt it could make an interesting composition, blending a balance of outside lighting with the internal atmosphere of the cavern.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_1.jpg" data-lightbox="the_cavern_set" data-title="Defining the workspace"><img class="example-image" src="img/The_Cavern/thecavern_1.jpg" alt="" height="370"/></a>
Defining the workspace
</i></p>

<p><br />
I knew I wanted this project to be larger than the last, but not too big - I am still learning and needed something to not be too overwhelming. I was happy with the sizing at this stage, I felt it was manageable, but not too restrictive in terms of the vision had for the space.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_2.jpg" data-lightbox="the_cavern_set" data-title="Re-defining the workspace"><img class="example-image" src="img/The_Cavern/thecavern_2.jpg" alt="" height="370"/></a>
Re-defining the workspace
</i></p>

<p><br />
With the sizing and proportions being roughly in check I started to explore upon the ideas I had. I planned out the initial base layout of the scene. My plan was to have the statue hanging from old ruin pillars, foreshadowed by a waterfall in the background. Then have the water flowing through the centre of the space underneath the statue.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_3.jpg" data-lightbox="the_cavern_set" data-title="Initial base scene construction"><img class="example-image" src="img/The_Cavern/thecavern_3.jpg" alt="" height="370"/></a>
Initial base scene construction
</i></p>

<p><br />
I really liked the direction that the scene was taking, however, I quickly found my approach for constructing the scene was causing me issues with the cohesion of the various static mesh elements. I needed a new method for constructing the scene that made the scene feel more natural. At this stage, identified that using BSP surfaces was the cause of the issues I was facing.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_4.jpg" data-lightbox="the_cavern_set" data-title="More base construction"><img class="example-image" src="img/The_Cavern/thecavern_4.jpg" alt="" height="370"/></a>
More base construction
</i></p>

<p><br />
I reapproached the design by using entirely static meshes. This worked out extremely well and it completely changed the feel for the design. The objects all meshed well and came together naturally, both in how I built up the scene as well as its overall feel. It was a bit tricky in places, not wanting to always duplicate assets too much. I found myself trying out various techniques in order to help design something unique despite using a relatively small asset set.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_5.jpg" data-lightbox="the_cavern_set" data-title="Scene reconstruction with static meshes"><img class="example-image" src="img/The_Cavern/thecavern_5.jpg" alt="" height="370"/></a>
Scene reconstruction with static meshes
</i></p>

<p><br />
The scene was really starting to come together at the point, where I was really happy with how some of the core elements were having such a strong impact so early in the design. It was time to start filling out the scene with finer details. Adding leaves, rumble, wall sconces and stalactites/stalagmites. I was quite impressed at how well it added depth to the design and enriched the earthy elements.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_6.jpg" data-lightbox="the_cavern_set" data-title="Final static mesh detailing"><img class="example-image" src="img/The_Cavern/thecavern_6.jpg" alt="" height="370"/></a>
Final static mesh detailing
</i></p>

<p><br />
Next came lighting. Throughout the project, to this point, I had been playing around with some general lighting to help define the sunlight projection. Once I removed the construction lights and did an initial lighting pass, it became quite apparent how important the contrast was between the natural sunlight and the luminous effects coming from the fire sconces. I did a decent job overall, where I definitely could improve the space with more experience.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_7.jpg" data-lightbox="the_cavern_set" data-title="Completed lighting pass"><img class="example-image" src="img/The_Cavern/thecavern_7.jpg" alt="" height="370"/></a>
Completed lighting pass
</i></p>

<p><br />
Though I know I was not fully comfortable with the lighting, I knew it was something I would be modifying forever. So I jumped into post-processing knowing that it might be able to help with smoothing out the lighting. Turns out post-processing massively helped with the lighting problems I was having. It helped bring the saturation levels in check, as well as reducing the sharpness to the contrast. Adding in some global warming hues complimented the fire effects as well as helped add lighting depth project throughout the darkness of the scene.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_8.jpg" data-lightbox="the_cavern_set" data-title="Post processing pass"><img class="example-image" src="img/The_Cavern/thecavern_8.jpg" alt="" height="370"/></a>
Post processing pass
</i></p>

<p><br />
Lastly was particles and effects. I did however cheat and do some of this earlier in the project with the water and fire sconces. I built upon this with dust particle system as well as adding more waterfall steam effects. Looking back upon it now, having a leaf particle system could have been a nice touch. Could have maybe even explored a wind effect channelling through on the water and open flames.
</p><br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_9.jpg" data-lightbox="the_cavern_set" data-title="Final scene view 1"><img class="example-image" src="img/The_Cavern/thecavern_9.jpg" alt="" height="370"/></a>
Final scene view 1
</i></p>

<br />

<p style="text-align: center; font-size:85%;"><i>
<a class="example-image-link" href="img/The_Cavern/thecavern_10.jpg" data-lightbox="the_cavern_set" data-title="Final scene view 2"><img class="example-image" src="img/The_Cavern/thecavern_10.jpg" alt="" height="370"/></a>
Final scene view 2
</i></p>

<p><br />
The project started out a bit rough with some learning difficulties, where it really came together in the end. I am not sure how appropriate it would be as a scene in a video game (performance wise and such), where it is a great start in developing my skills. The overall composition I like, individually some components could be improved. As a whole, I really liked how this project turned out, especially the scenes atmosphere.
</p><br />
