<h1> What is Motion? </h1>

The traditional why in which we animate is with a set duration that mimics a set  of movements over that set time. While this way of animating works but is very hard to control if you want fluid UI. For example, if I want a gui element to tween to where the player is holding his mouse I would need to have a very small duration but that would leave artifacts where the mouse is curently moving to the old position instead of the new one. This is only a small issue in the example I mentioned but can effect larger and more crucial animations if not dealt with. What is the solution? Motion based UI! This is fundamentally different as we give parameters of physical motion instead of duration. The most common and best form of motion is springs!

<h1> What are springs?</h1>

Springs are the best way to show motion based UI as they have a very natural feel and look by default. Springs are used all around us in our daily lives such as jumping up and down or waving to a friend so having them be used in UI motion is naturally very clean. They also can be configured to mimic common time based easing styles which can be viewed in the API reference under springs.