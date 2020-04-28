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
Video of 5 cubes:

How I made Each cube:
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