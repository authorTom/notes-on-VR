# Notes on VR
These are my notes on VR. A little unorganised and work in progress.
## Interactions
With VR interaction, it’s important to consider various factors that affect the user experience, including how movement and interaction are mapped to different parts of the body. It's crucial to avoid mapping movement to fingers or interactions to the head. <br />
* Mapping Movement to Fingers: Mapping movement to fingers can be problematic as it can cause discomfort or even pain in the user's hand and fingers over time. This is because prolonged use of hand and finger movements can cause fatigue and strain on the muscles and tendons. <br />
* Interaction with the Head: This can be problematic as excessive head movement can cause motion sickness and discomfort in the user. Additionally, it can be challenging to maintain a stable view of the environment when constantly moving the head. <br />
### Teleportation
Developing teleportation locomotion within VR can greatly enhance the user experience and reduce motion sickness. Here are some tips to improve teleportation: <br />
* **Cross Streams:** In teleportation, it is important to allow the user to point to where they want to travel, press a button and then have the screen fade to black, signaling the transition. Fading to black is commonly used as a blink effect which can help reduce motion sickness. <br />
* **Avoid Rotating:** Rotating can cause motion sickness and disorientation in VR. Hence, it's important to avoid rotational movements as much as possible. Instead, offer alternative ways for the user to view the environment. <br />
* **Use Frames of Reference:** Providing visual cues or frames of reference to the user can help them to orient themselves and reduce motion sickness. For example, providing a visual reference point in the environment can help the user understand their position and reduce disorientation. <br />
* **Avoid Acceleration:** Rapid acceleration or deceleration can cause motion sickness in VR. Therefore, it's important to avoid sudden changes in speed and maintain a consistent pace. <br />
* **Provide Hints to Outside of Field of View:** In teleportation, it's important to provide visual cues or hints that help the user understand the environment outside of their field of view. This can help prevent disorientation and provide a smoother transition between locations. <br />

### Motion sickness
* All users are different, some get sick some don’t. <br />
* Rapid movement will make people feel sick. <br />
* If you have a horizon line keep it steady. <br />  
* Avoid rapid or abrupt transitions. <br />
* Blink locomotion helps with motion sickness. <br />
* Bright scenes are fatiguing. <br />
* Decide on your locomotion method, test, test, and test again. <br />
### Input Taxonomy
1. **6 DOF Manipulation:** This approach involves using controllers or other input devices to manipulate objects or move within the virtual environment. It allows for more natural and precise interaction within the world. This approach is useful because it can increase the sense of presence and immersion for the user. <br />
2. **Pointing:** Pointing is a way to interact with objects in the environment, including those that are within and beyond reach. It allows the user to direct their attention and actions towards specific objects or locations. This approach is useful because it enables the user to interact with the environment in a more natural way. <br />
3. **Hand Controls:** Hand controls enable the user to interact with the environment through hand gestures and movements such as actuation and swiping. This approach allows for more nuanced and natural interaction. <br />
4. **Ambient Invocation:** involves interaction such as voice commands to interact with the environment, which tend to be infrequent and indirect. This approach can reduce the cognitive load on the user and provide a more seamless and natural interaction with the environment. <br />
5. **Subconscious:** Subconscious input is a background process that captures the user's movements and inputs without their conscious attention. This enables natural and intuitive interaction, without requiring the user to actively think about their inputs (reduces cognitive load). <br />
### Interfaces
* Interfaces need to exist within the game. Not just on top of he users vision <br />
* Menus and buttons will need to accommodate for the Field of View (FOV) of the headset. <br />
* Due to limited resolutions, buttons and text need to be obvious and easy to see. <br />
### Sound
* Sound design is very important; it needs to immerse your user and be spatial. <br />
### Affordances
Affordances refer to the properties of objects or elements that suggest how they can be interacted with by the user. Affordances are important because they help users to understand how to interact with the environment and its objects. <br />
* **Visual:** A button that appears raised or has a shadow under it suggests that it can be pressed. A door handle that is positioned at the height of the user's hand suggests that it can be grabbed and pulled. <br />
* **Auditory:** A sound effect that plays when the user's hand is near an object suggests that it can be interacted with. A different sound effect that plays when the user successfully interacts with an object suggests that the interaction was successful. <br />
* **Haptic:** The sensation of resistance when trying to push a heavy object suggests that it requires more force to move. The sensation of vibrations when touching an object suggests that it is interactive. <br />
* To effectively use affordances, tune them to serve the desired user experience and ensure that they align with expectations. This involves ensuring the affordances behave in a predictable and consistent manner. <br />
* Affordances can be either static or dynamic, depending on whether they remain the same or change over time based on user interactions or other factors. It's important to consider the context in which affordances are used, as this can impact their perceived usefulness and relevance. <br />
### Uncanny Valley
* The “Uncanny Valley” phenomenon occurs when representations of human-like or realistic characters cause a sense of discomfort or unease. This is due to the slight imperfections or deviations from reality, which can create a sense of eeriness or unsettling feeling. <br />
* Representing hands in VR is particularly tricky, as clunky or awkward hand movements can break immersion and distract from the experience. Alchemy Labs has solved this problem by using cartoon hands, which work better than more realistic representations. <br />
* Sometimes, non-realistic representations of items and actions can actually enhance the user's experience and keep them more immersed in the virtual environment. For example, abstract representations of objects or environments can create a more stylized or artistic feel, which can be more engaging than strictly realistic representations. <br />

## Graphics
### Normal Maps
A normal map is a type of texture map that adds detail to a model without increasing the polygon count. Normal maps simulate the effect of bumps and wrinkles on the surface of a model by encoding surface normals as RGB values. By encoding the surface normals in this way, the normal map can be used to create the illusion of depth and detail on a flat, low-poly surface. When a normal map is applied the graphics engine uses the encoded surface normals to calculate how light interacts with the surface of the object. This creates the illusion of depth and detail, even though the actual geometry of the model is relatively simple.
* Normal maps look different in VR <br />
* Due to stereoscopic vision, our eyes see normal maps as flat. <br />
* Normal maps don’t have the same impact you see on flat games. <br />
* They are generally fine for small details but are not recommended for larger deatils. <br />
* Normal maps may not be convincing enough. <br />
* You will need to use more geometry to give a sense of depth. More geometry = greater complexity = lower performance. <br />
### Cone of Focus
The "cone of focus" problem refers to the limited area within a VR headset where the image is in focus. This can cause eye strain and make it difficult to read or see certain details. The key is that you don’t want the user to focus on small details. There are ways we can help solve this. <br />
* Eye-tracking. <br />
* Foveated rendering. <br />
* Reduce the need for users to focus on small details or text that is difficult to read. This can involve using larger fonts or graphics, reducing clutter in the environment, and simplifying user interfaces. <br />
* Object placement - Ensure that important objects are placed within the user's central field of view, and that the user doesn't need to strain their eyes to see important details. <br />
## My Other Projects
[➡️ Notes on VR Performance](https://github.com/authorTom/notes-on-VR-performance) <br />
[➡️ Notes on VR Development](https://github.com/authorTom/notes-on-VR) <br />
<br />
**Like it? please give the repository a star ⭐** <br />
