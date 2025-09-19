# ClassExercise03
A 3D Unity Project containing a basic scene with fully imported assets.

GitHub Link: https://github.com/Valle94/ClassExercise03

This project was created by Max Valle as a brief exercise on importing and using assets in Unity3d. 

I decided to go with an indoor scene because I wanted to see if I could recreate my old apartment in Unity with assets from the asset store. As far as scenario, the two things that are possible within the scene are player movement and looking around, as well as opening and closing all the doors. Additionally, some of the doors for objects in the kitchen can also be opened and closed.

To open a door: walk near it, look at it, and press the left mouse button. Repeat to close the door. 

Asset Links:
Terrain or Ground (Floor), Walls, and all interior assets came from this "Apartment" kit asset pack: https://assetstore.unity.com/packages/3d/environments/apartment-kit-124055

Because I went overboard on everything else, I decided to choose a very simple character model. The cat that's on my bed in the scene can be found here: https://assetstore.unity.com/packages/3d/characters/animals/mammals/free-chibi-cat-165490

The audio that plays on scene start can be found here: https://www.youtube.com/watch?v=Yv_VxwT08T0

Scripts:
The movement script attached to the player allows for basic 2d movement throughout the scene. 
The mouse movement script that's attached to the camera within the player allows the user to control the direction of the camera using the mouse. 

The door scripts (which are not mine, but are very simple) plays an animation for opening or closing a door when the player is near enough and looking at the door. 
