# GoogleCodeIn2017Notes
Title States it All.

# References
* Syntax Help
   * https://guides.github.com/features/mastering-markdown/
   * https://github.com/MovingBlocks/Terasology/wiki/Developing-Modules#fetch-an-existing-module

# Task: Develop a simple interface screen
* Objectives

  * A pull request containing a new interface screen, created using the NUI Quick Start Tutorial, is submitted to the Sample module's repository.

  * Modify info area to contain information from an in-game system of your choice. A static piece of text - like an interesting or inspiring quote - is fine too!

  * Screenshot of your new UI screen open in-game

# Notes
  * Use the base NUI via github as a starting point
  * After getting a new repo via ```git clone https://github.com/MovingBlocks/Terasology.git``` ./gradlew idea needed to be run to re initialize the terasology file for IntelliJ Idea to use Terasology.ipr
  * Attempted to get the sample directory by using the command ```git clone https://github.com/Terasology/Sample.git``` while in the Terasology. I decided to move the newly downloaded file into the 'Modules' directory.
  * A better way to get the sample directory is ```groovyw module get Sample``` the previous way gets the wrong directory.
  * When creating and editing the environmenInfoScreen.ui it asked me to direct the unkonwn 'ui' file extension, so i pointed it to the standard text file. as a result, now when opening these files, the icon has a small green 'Qt' on the bottom right. everything inside the ui files are now unexpected tokens. 
  * while editing the EnvironmentInfoScreen.java class i found that just copying and pasting from the website does not work at all and its best to just re type the code entirely. on top of that, i am not using a new module tutorialnui so i had to change the first like ```package org.terasology.tutorialnui``` to ```package org.terasology.nui```
