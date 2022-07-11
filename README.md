# Robo4earth
Web application and Micro:bit program to wirelessly control a Micro:bit robot platform.

<img src="Dokumentation/sdg_empty.jpg" style="width:311px;"/>   <img src="Dokumentation/robot1.jpg" style="width:400px;"/><br/>

## About the project
Robo4earth builds on the project Robo4girls, a project funded by [netidee](https://www.netidee.at/Robo4girls) in 2018.
The [ZIMD](www.zimd.at) (Center for Interaction, Media & Social Diversity) offers a workshop format, where girls build and program robots. The workshops are offered for girls in fifth grade. The aim of the workshops is to inspire the 10- to 11-year old girls in technology and especially robotics.

This repository hosts the R4E web application, which can be reached at [robo4earth.zimd.at](https://robo4earth.zimd.at). The housing and base of the robots are build from wood and are personalized by the kids participating in the workshop. If you want to build your own robot you find a shopping list as well as an instruction manual on our [robo4earth website](https://www.robo4earth.at/#roboter).

## Instructions

### Testing the setup 
You can test our R4E App with a computer, a Micro:bit and an USB cable.
#### List of materials
+ a [Micro:bit](https://microbit.org) with usb cable
+ a computer with internet access

#### Prepare the Micro:bit
Connect your Micro:bit to your computer via USB and load the R4E_MICROBIT.hex files on to your Micro:bit. You can download the universal hex file (for micro:bit version 1 and 2) from the web app. Click on the <i>Menu</i> button and choose <i>Hex Datei herunterladen</i>. If you do not know how to upload a program to your Micro:bit you can look it up [here](https://makecode.microbit.org/device/usb).
This app is supposed to be used with the Micro:bit V2, with the Micro:bit V1 better use the [R4G web application](https://robo4girls.zimd.at/).

#### Connect and program the Micro:bit with the R4E web app
Open the google chrome browser on your mobile device and navigate to the [R4E web application](https://zimdvienna.github.io/Robo4earth/). Don't forget to activate Bluetooth on your device! 
On the R4E website click the <i>Verbinden</i> button, choose your micro:bit from the list and click <i>Koppeln</i>. Wait a few seconds until a confirmation message pops up. If the connection is not established quickly, disconnect the Micro:bit from its power source (computer or battery) and wait for one minute, then try again. If you still cannot establish a connection restart your mobile device. If the Micro:bit is successfully connected, it scrolls a "C" over its LED display.

Now you can program the R4E robot by selecting blocks from the Blockly toolbox and dragging them into the workspace. If you click on one of the 6 sections in the toolbox it will list all blocks available in this section.

![blockly toolbox](media/blockly_toolbox_foto.png)

You can drag & drop the blocks you want in the workspace. To create a program connect the individual blocks to a chain. To connect the blocks drag a block close to another block until the background between them turns gray and then release it. The blocks snap in place and you should hear a clicking sound when they connect. To start the program click <i>Start</i>. Melodies and Movements will only work if you have a buzzer and motors connected to your Micro:bit.

Have Fun!
