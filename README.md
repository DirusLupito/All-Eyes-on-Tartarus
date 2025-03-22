# 281TwineProject
All source code and assets related to our twine project for the CSC 281 team project.

To run, simply navigate to the twine folder and open the All Eyes on Tartarus.html file in any modern web browser.

Currently WIP. Sensor game is partially implemented, while the story is still being planned in google docs. 
The sensor game will be changed in the future so the player is no longer directly controlling where missiles are shot. Instead, they will report information to a basic AI that will handle combat.

There is one bug that you may encounter which pertains to probabilities and framerate. I developed the sensor game using plain old JavaScript, meaning I had to write the engine myself. I tied physics and other game state updates to deltatime, the time between frames. This was done to ensure that, regardless of physical hardware, the game would perform the same. But sadly, I think that I failed a bit when it came to certain AI probability calculations regarding missile launches. If you play the game on two separate computers, one with a very fast monitor refresh rate, and one with a slow monitor refresh rate, you will notice that the game played on fast monitor involves a lot more missiles. I am working on fixing this issue, and I hope it does not negatively affect your experience. - ABM
