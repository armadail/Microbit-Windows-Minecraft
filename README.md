# Microbit-Windows-Minecraft
Tutorial on how to start coding with minecraft on windows. Additional tutorial to pair a bbc microbit with minecraft.

## Part1) Installing the mcpi mod on minecraft

### 1) Download minecraft though: https://tlauncher.org/en/

- To code on minecraft you require the mcpi mod (minecraft-pi is orignially developed to run minecraft on a rasberry-pi) 
- the mod is only available on versions 1.8/1.8.8/1.8.9/1.9 of forge

![tlauncher](/images/tlauncher.PNG)

- Create a world to see if everything is functional. 
    - Recommended settings: Creative and Superflat.
    
### 2) Download and run the RaspberryJamMod-Installer.exe file from https://github.com/arpruss/raspberryjammod/releases

- this includes 
    - the minecraft-pi mod
    - python installed in the correct directory so you can run python scripts in game
    - sample scripts, good for a hello world test
                
![tlauncher](/images/tlauncher.PNG)

if there are no errors, run minecraft through the tlauncher type **/py donut** and a donut made from glass and water should appear around you

![tlauncher](/images/tlauncher.PNG)

### 3) Navigate into your working directory press **Windows-R**, type **%appdata%\.minecraft**, press enter. 

- go to the **mcpipy** folder and you will see the sample code that has come along with RaspberryJamMod-Installer.exe 
- this is where all your programs will go if you want to run them inside minecraft by typing **/py myprogram**

### 4) Open VScode, it is free to download through https://code.visualstudio.com/

- Type out the follow code, it simply prints out "Hello World!" to the MC chat and places a diamond block in front of you

![tlauncher](/images/tlauncher.PNG)

- save it under the proper directory

![tlauncher](/images/tlauncher.PNG)

### 5) If minecraft is open in the background you can simply press **F5** in VScode to run your program.

![tlauncher](/images/tlauncher.PNG)

Now you're ready to start coding with minecraft. A more indept tutorial is avaiable: https://www.instructables.com/id/Python-coding-for-Minecraft/

## references:
Arpruss- Windows MCPI mod guide

https://www.instructables.com/id/Python-coding-for-Minecraft/ 

Arpruss - mcpi mod github

https://github.com/arpruss/raspberryjammod/releases

whaleygeek- bitio github 

https://github.com/whaleygeek/bitio 

ChrisPenn - bitio mcpi projects

http://warksjammy.blogspot.com/2017/07/bitio-blogs-in-one-place.html?view=timeslide

