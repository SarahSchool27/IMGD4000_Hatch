
# Sarah Hatch - Portfolio of work on Rubbish Rumble

### Project

Rubbish Rumble is a two to four player couch coop game made by a team of eight students as 
a class project for WPI's class IMGD 4000/4500 (Technical Game Dev II).



### What I worked on

On Rubbish Rumble I built two post processing shaders, handled in engine organization of assets 
and materials, built level enviroment art, and acted as the project manager.
I also did a small amount of gameplay programming.

#### Shaders

##### Cell Shader
I built a simple three tone post processing cell shader, that works by taking a greyscale version of
the view and dividing it into flat shadow bands before mixing it back with the unlit color of the
object in the scene.
In building this shader I referenced [PrismaticaDev's video](https://www.youtube.com/watch?v=RkFwe7JI8R8)
which allowed me to add colored lighting back into the shader.
 
To limit jittering in cell shader caused by jittering shadows, I turned off Lumen for both Dynamic Global Illumination as well as Dynamic Reflections. This forced all the lighting to be built but removed the shadow fluctuations. Since our game's lighting was already planned to be a stationary skylight this was not an issue for us.
