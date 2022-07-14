# toorcamp-pcb-workshop
Rapid prototyping is all the rage, but if that still involves too much foresight and planning for you, there's always reckless prototyping!

Never made a PCB before? This is the quickest way to learn. First, we'll give you a complete KiCAD schematic for a simple flashy light circuit. Next, we'll walk you through the process of laying out your first board. Finally, we'll show you how to fab it in minutes on a PCB milling machine! Made a mistake? No problem, fix it and you'll have V0.0.2 in your hands in a few more minutes.

# Disclaimer
This is a quick-and-dirty workshop. We're here to get your a little bit of experience in a short time. If you continue to make pcbs this way - it's well worth taking the time to focus on each of these steps in much more detail and understand *why* we do everyhing instead of just how.

# Customizing your board
1. [Install KiCad 6.0](https://www.kicad.org/download/)
2. Clone this repository, and open toorcamp-workshop.kicad_pro
3. From the KiCad project manager, open toorcamp-workshop.kicad_sch to look at the schematic. The schematic is already complete - What do you see?
4. From the KiCad project manager, open toorcamp-workshop.kicad_brd to look at the board layout. It is not complete - you need to customize it!
5. What shape do you want your board? You can adjust the outer border to change the shape. You can also make fancy shapes and curves with the line and curve too. Just make sure you have a closed shape - no leaks!
6. What layout do you want your LEDs? You can move them around for artistic intent.
7. Now - it's time to wire things up. Use the "Route Tracks (X)" tool to connect the light lines into actual copper lines. Make sure not to cross the streams!!!
8. Ready to mill the board? Choose File->Plot, and click 'PLOT' with all the default settings to generate the traces and edges. 
9. Click 'Generate Drill Files' to tell the mill where to make holes.


# Milling your board
1. Copy all your files to a USB stick, and go to the Milling PC
2. Open the Bantam Tools software if not already opened, and import your gerber file - it wants the f_cu file (front copper)
3. Make sure it also has your outline and drill file
4. Place the design on an empty spot on the blank board. 
5. Click 'mill' and cross your fingers!!
