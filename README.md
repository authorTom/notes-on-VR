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
## Cone of Focus
The "cone of focus" problem refers to the limited area within a VR headset where the image is in focus. This can cause eye strain and make it difficult to read or see certain details. The key is that you don’t want the user to focus on small details. There are ways we can help solve this. <br />
* Eye-tracking. <br />
* Foveated rendering. <br />
* Reduce the need for users to focus on small details or text that is difficult to read. This can involve using larger fonts or graphics, reducing clutter in the environment, and simplifying user interfaces. <br />
* Object placement - Ensure that important objects are placed within the user's central field of view, and that the user doesn't need to strain their eyes to see important details. <br />
## Affordances
Affordances refer to the properties of objects or elements that suggest how they can be interacted with by the user. Affordances are important because they help users to understand how to interact with the environment and its objects. <br />
* Visual: A button that appears raised or has a shadow under it suggests that it can be pressed. A door handle that is positioned at the height of the user's hand suggests that it can be grabbed and pulled. <br />
* Auditory: A sound effect that plays when the user's hand is near an object suggests that it can be interacted with. A different sound effect that plays when the user successfully interacts with an object suggests that the interaction was successful. <br />
* Haptic: The sensation of resistance when trying to push a heavy object suggests that it requires more force to move. The sensation of vibrations when touching an object suggests that it is interactive. <br />

