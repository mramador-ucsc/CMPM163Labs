# CMPM163Labs
# Lab2 #
VIDEO OF 3 CUBES: https://drive.google.com/file/d/18Uxsu6In5j6C4so3gbCtL7_3qi_tiCcu/view?usp=sharing

![](Screenshot%20(43).png)

# Lab3 #
Video of 4+ Cubes: https://drive.google.com/file/d/1TMGrKTod3hV03Ez9PT9Ud5ndI_evawUv/view?usp=sharing

How I made each cube:

Top Left: This is a Basic Material cube with a "WireFrame" boolean set to true.

Top Middle: This is the Mesh Phong Material cube we were shown how to do in the lab.

Top Right: This is the 'Cool Cube' we were shown how to make in the lab

Bottom Left: This is a Normal Material cube with a "FlatShading' boolean set to true.

Bottom Right This is a cube with a custom shader I replicated from three.js's examples.


# Lab4 #
Video of 5 cubes: https://drive.google.com/file/d/1IUZpSGQmlQ-0Frh-dWswYHBtayl2oqdU/view?usp=sharing

How I made Each cube: https://drive.google.com/file/d/1IUZpSGQmlQ-0Frh-dWswYHBtayl2oqdU/view?usp=sharing

Top Left: I took a texture from the google drive and tiled it by using the modulo operator on the x and y axis of the vec2 variable.

Top Right: Part 2 Texture C (load this texture with shaders, as we worked through in the lab together)

Bottom Left: Part 1 Texture A & Normal Map A (uses three.js built in texture functionality)

Bottom Middle: Part 1 Texture A (uses three.js built in texture functionality)

Bottom Right: Part 1 Texture B & Normal Map B (new texture/normal map combo using built in three.js functionality)

What is a formula to get the x coordinate of the texture given a u value of the uv coordinate (a value between 0 and 1)?
Answer: 

You take the u value and multiply it by 8 since the uv value is between 0 and 1 and the x coordinate of a texture is between 0 and 7. 

What is a formula to get the y coordinate of the texture given a v value of the uv coordinate (a value between 0 and 1)?
Answer:

You take the V value and multiply it by 8 since the uv value is between 0 and 1 and the y coordinate of a texture is between 0 and 7. 

What color is sampled from the texture at the uv coordinate (0.375, 0.25)? (sample from the image based on the number your formula gives you i.e. (1, 0) (x, y) is blue)

Answer: White

# Lab5 #
Video to Game Mods: https://drive.google.com/file/d/1QRvNvQ5SsFjtddSGidN6IkXbAOkUq21b/view?usp=sharing

Modifications I made:
I followed several tutorials to add particle effects to the wheels of the karts and anytime the kart collides into the walls green particles come flying out and bounces the player back. I also added a trigger on the start/end line where when the player crosses, confetti particle effects shoot out from both sides. Lastly, I added two boost pads in the beginning of the game that doubles the player's top speed and acceleration.


# Lab6 #
Screenshot of my texture with the corrected aspect ratio:
![](Screenshot%20(51).png)
Link to my Assignment: https://www.shadertoy.com/view/WsBfRR
Link to something cool I found: https://www.shadertoy.com/view/XdlSDs

# Lab7 #
Part 1: A screenshot of your terrain with the height map as the texture 
![](Screenshot%20(53).png)
Part 1b: A screenshot of your terrain with a different texture as the texture
![](Screenshot%20(52).png)
Part 2: Water Scene: https://drive.google.com/file/d/1fio3CRu5FhdnGozinvaaHGftcuWPeWSF/view?usp=sharing
Part 3: Mountain + Water Scene https://drive.google.com/file/d/1EGt9pfJHz_iiemwQauYeSNFnkjaNlrLv/view?usp=sharing

I made my mountains with a height map I found online and attached it to a plane with a rocky texture on it. I then took the water plane we made in part 2 and positioned it to run through the lowest part of my rocky plane to make it seem like water is flowing down a river.

My partner for lab 7 made a cool mountain landscape that had pillars separated by flowing water between them. It looked like a flooded collapsed mountainscape. My partner worked in Unity while I worked with Three.js. Therefore, we did not help each other with our work.

# Lab8 #
An image of a virtual/real city that inspired your generated city: 
![](Venice.jpg)
![](naruto.jpg)

A screenshot or video of your generated city: 
https://drive.google.com/file/d/1vDyo46l9Jc_j9ZFT2H8dyimIXr2USLqU/view?usp=sharing

An explanation of how the inspiration city affected your generated city’s design: 

I wanted to make a flooded city that is split down the middle kinda like the flooded Venice picture above. I also was inspired to put two giant statues on top of the city like the naruto statues above.

Which part did they do?: My partner did the Unity side of the lab.

Which part of a tutorial did your partner find most challenging?: "I found the Creative part the most challenging" is what my partner stated.

Which part of a tutorial did your partner find most interesting?: I found the explanation on seeding the most interesting

My partner and I did not help each other for this lab.

