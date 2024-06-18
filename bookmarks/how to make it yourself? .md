# How to make it yourself?

In this guide, I will explain the steps to recreate this bookmark.

## 1. Design

First, you need to modify the design according to your needs. To do this, open Insckape and adjust the design (that you can found on bookmark file) and adjust the design to your liking by adding SVG images, which you will convert into vectors. You can also add or remove text, but always remember to convert the object into a path afterward. Then, save the file in .svg format.

If you want to cut or engrave certain parts differently, you will need to use different colors for the various sections.

## 2. Preparation of the G-code

For this part, you will need to download Visicut. In Visicut, open the .svg file. Then select the laser cutter that you are using. If you want to cut or engrave different parts taht you've colored differently, go to configuration, then choose advanced configuration, and select the parts by colors. Next, go to laser settings and choose the power and speed thanks to the following advice.

If you want to cut paper:

\- P: 8 / S: 2 --\> to cut everything

\- P: 8 / S: 3 --\> the paper is marked and it can be cut with a little force

\- P: 8 / S: 4---\> to engrave

We don't recommend to engrave on paper.

If you want to cut wood of 5 mm:

\- P: 60 / S: 2 --\> the wood is marked and it can be cut with a little force

\- P: 80 / S: 3 --\> to cut everything

After go to Export the G-code and name the file "name".nc. 

## 3. Use of UGS platefrome

Turn On your laser cutting and put the USB cable in your computer.
After download it, you can open UGSplateform and connect your laser cutting. Them, open the Gcode file, reset the zero and push play. 

Thank you for your attention, I hope your project went well.

Made by Lucie LAQUIEZE for Open.make