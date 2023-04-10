# Notes on VR
## User Experience in VR
## Motion sickness
* All users are different, some get sick some don’t. <br />
* Rapid movement will make people feel sick. <br />
* If you have a horizon line keep it steady. <br />  
* Avoid rapid or abrupt transitions. <br />
* Blink locomotion helps with motion sickness. <br />
* Bright scenes are fatiguing. <br />
* Decide on your locomotion method, test, test, and test again. <br />
## Interfaces
* Interfaces need to exist within the game. Not just on top of he users vision <br />
* Menus and buttons will need to accommodate for the Field of View (FOV) of the headset. <br />
* Due to limited resolutions, buttons and text need to be obvious and easy to see. <br />
## Sound
* Sound design is very important; it needs to immerse your user and be spatial. <br />
## Normal Maps
A normal map is a type of texture map that adds detail to a model without increasing the polygon count. Normal maps simulate the effect of bumps and wrinkles on the surface of a model by encoding surface normals as RGB values. By encoding the surface normals in this way, the normal map can be used to create the illusion of depth and detail on a flat, low-poly surface. When a normal map is applied the graphics engine uses the encoded surface normals to calculate how light interacts with the surface of the object. This creates the illusion of depth and detail, even though the actual geometry of the model is relatively simple.
* Normal maps look different in VR <br />
* Due to stereoscopic vision, our eyes see normal maps as flat. <br />
* Normal maps don’t have the same impact you see on flat games. <br />
* They are generally fine for small details but are not recommended for larger deatils. <br />
* Normal maps may not be convincing enough. <br />
* You will need to use more geometry to give a sense of depth. More geometry = greater complexity = lower performance. <br />
