---
layout: default
title: 4-Create a Push Pin
nav_order: 5
parent: Workshop Activities
---

<img src="images/act-4/0.png" alt="modelled pushpin" style="float:right;width:360px;margin-left:10px;">

# **Create a Push Pin**

If you or your group have any questions or get stuck as you work through this in-class exercise, please ask the instructor for assistance.  Have fun!

1.  **Download** and **install** Fusion 360:
    -   Check your laptop specs to ensure it’s able to run Fusion 360. System requirements are listed here: [https://autode.sk/2qg8ryB](https://autode.sk/2qg8ryB])
    -   Follow this link to make an Autodesk account and download Fusion 360: [https://autode.sk/3DW7TRB](https://autode.sk/3DW7TRB)

    <img src="images/act-4/2.png" alt="menu to design" style="float:right;width:240px;margin-left:10px;">

2.  Create a new part:
    -   **Open Fusion 360**
    -   **Click** on your **name** in the top-right of the screen, then **click** on **Preferences.**
    
    <img src="images/act-4/2-2.png" alt="planes" style="float:right;width:180px;margin-left:10px;">
    -   On the top-right menu, **select File,** and then **New Design.**

3.  Make the plastic part of the push pin:
    -   **Select** the **Create Sketch** <img src="images/act-4/3.png" alt="create sketch tool" style="width:25px;"> feature. **Select** the **Top** plane.
    -   **Select** the **Line** tool <img src="images/act-4/3-3.png" alt="line tool" style="width:25px;">. Make a “U” shape with lines by clicking on the green axis, then on the origin, then on the red axis, then straight up from that point. **Click** the **Esc** key to exit the Line tool.
    
    
    
    -   **Select** the **Sketch Dimension** tool <img src="images/act-4/3-4.png" alt="sketch dimension tool" style="width:25px;">. **Click** on the **right line, move your mouse slightly** to the left the line and **click** again. **Enter 4.5** as the dimension. **Repeat** with the other two lines and follow the dimensions in the picture to the right. **Click** the **Esc** key to exit the Sketch Dimension tool.
    
    <img src="images/act-4/3-2.png" alt="initial lines" style="width:620px;margin-left:10px;">
    
    -   **Click** on the **Center Diameter Circle** tool <img src="images/act-4/3-6.png" alt="center diameter circle tool" style="width:25px;">. First, **click** somewhere on the 4.5 mm line, then on the **endpoint** of the line. **Repeat** with the 3.5 mm line.
    -   **Select** the **Line** tool <img src="images/act-4/3-7.png" alt="line tool" style="width:25px;">. **Click** on one **circle,** then **click** on the **second circle.**
    
    <img src="images/act-4/3-5.png" alt="circles" style="width:720px;">
    
    -   **Select** the **Sketch Dimension** tool <img src="images/act-4/3-8.png" alt="sketch dimension tool" style="width:25px;">. The 2.25 mm dimension can be added by hovering over where the line meets the circle until a point appears, clicking on the point, then clicking on the horizontal 12.5 mm line. Following the same method, add the dimensions highlighted in the picture above.
    
    <img src="images/act-4/3-9.png" alt="push pin cross section 1" style="width:620px;">
    
    <img src="images/act-4/3-92.png" alt="revolved pushpin" style="float:right;width:240px;margin-left:10px;">
    
    -   **Select** the **Trim** tool <img src="images/act-4/3-91.png" alt="trim tool" style="width:25px;">. This tool allows you to remove sketch entities that are not needed. **Click and drag** over part of a circle, then **release** the mouse. **Delete** parts of the circles until it looks like the diagram to the right.

    <img src="images/act-4/3-10.gif" alt="trimming a sketch" style="float:right;width:720px;">

    -   **Click** over to the **SOLID** tab on the top menu, and click on the **Revolve** feature <img src="images/act-4/3-93.png" alt="revolve tool" style="width:25px;">. It will automatically select the interior area of the sketch to revolve. **Select** the 12.5 mm line as the **Axis. Click OK** in the **Revolve** pop-up box.
    
    <img src="images/act-4/3-11.gif" alt="revolving a sketch" style="float:right;width:720px;">
    <img src="images/act-4/4.png" alt="hole tool pop up" style="float:right;width:240px;margin-left:10px;">

4.  Add a hole for the metal pin:
    -   **Click** on the **Left** face of the object. **Select** the **Hole** feature <img src="images/act-4/4-2.png" alt="hole tool" style="width:25px;">.
    -   **Drag** the hole so it’s snapped to the origin.
    -   In the Hole Feature window, change the **Drill Point** end condition to **Flat,** change the depth to 5 mm and the width to 1 mm.
    -   **Click OK** in the **Hole Feature** window.
  
    <img src="images/act-4/4-3.gif" alt="making a hole" style="float:right;width:720px;">

5.  Make it into a component:
    -   **Click** on the arrow next to **Bodies** in the **Browser.**
    <img src="images/act-4/5.png" alt="create components" style="float:right;width:360px;margin-left:10px;">
    -   **Right-Click** on **Body1** and select **Create Components from Bodies.** This has converted the pushpin body into a component. Components are the individual parts needed in an assembly, while bodies are just building blocks for components.
    -   Another way to make a component is to specify it before building any bodies. At the top of the screen, **click** on the **New Component** feature <img src="images/act-4/5-3.png" alt="new component icon" style="width:25px;">. **Click OK** in the pop-up box.

    <img src="images/act-4/6.png" alt="chamfer pop up" style="float:right;width:340px;margin-left:10px;">

6.  Make the metal pin:
    -   **Orient** the push pin so you can look down the hole. **Select** the bottom face of the hole.
    -   **Click** on the **Extrude** feature <img src="images/act-4/6-2.png" alt="extrude feature" style="width:25px;">. In the Extrude pop-up box, **enter 15 mm** as the **Distance.** Select **New Component** from the Operation drop-down. **Click OK.**
    -   **Click** on the **Modify** drop-down menu and select the **Chamfer** tool <img src="images/act-1/4-5.png" alt="chamfer tool" style="width:25px;">. **Select** the edge of the metal pin that isn’t in the plastic. Change the **Chamfer Type** to **Two distances,** change the first distance to 0.5 mm and the second to 2.5 mm.  **Click OK.**
    -   To activate both components at once, hover over the file name in the browser and **click the small circle** that appears next to the name. <img src="images/act-4/6-4.png" alt="small circle" style="width:200px;">

    <img src="images/act-4/6-5.gif" alt="making the metal pin" style="float:right;width:700px;">
    
    **Congratulations! You have modelled an assembly of two components in Fusion!**


7.  **OPTIONAL:** Add appearances to the components of the push pin.
    -   **Click** on the **Modify** drop-down menu and select **Appearance.** Scroll down to the bottom of the window. 
    -   **Click** on the **Metal** folder, then on the **Steel** folder, drag the **Steel-Cast** block and drop it onto the pin. 
    -   **Click** on the **Plastic** folder, drag and drop the **ABS(White)** block onto the plastic part of the pushpin. If you want, you can try to make a render of the pushpin by clicking on **Design** in the top-left corner and selecting **Render.**
    <img src="images/act-4/7.png" alt="rendered pin" style="float:right;width:240px;margin-left:10px;">

[NEXT STEP: Splitting an Object Found Online](act-5.html){: .btn .btn-blue }

