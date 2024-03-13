# -Exploring-ESO-s-Rocket-Tech
 Exploring ESO's Rocket Tech: Dive into the PCBs I Crafted!
### PCB Descriptions:
1. **Timer PCB:**
   - Dimensions: 2 layers, Arduino Nano-based digital timer with optocoupler LEDs and MOSFETs.
   - Functionality: Triggers linear actuators for parachute deployment (drogue chute and main).
   
2. **Communication PCB:**
   - Dimensions: 2 layers, integrates Waveshare SX1262 LoRa radio and SIM800L V2 breakout board.
   - Functionality: Facilitates communication with the main avionics computer via two 8-pin JST connectors. And sends data to the ground station.

### PCB Visuals and Design guidelines:
Ever wondered how those tiny green boards make your gadgets tick? Let's take a simple stroll through the world of Printed Circuit Boards (PCBs). These small but mighty boards are the unsung heroes behind your electronic devices. Today, we'll dig into the basics: schematics, layouts, copper traces, vias, ground planes, and pads.

- **PCB 3D:**
  - Here is a 3D visual of the board available on Altium!
    
  ![COMface](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/e9e99f71-82b4-4efa-b843-8220862eb645)
  
  ![Timer PCB Image](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/d052a6b7-96b6-4555-a3ae-9907d2e9598c)
  
- **PCB Schematic: Where Ideas Take Shape**
  - Picture a Map of Circuits
    Think of schematics as a treasure map, but for engineers. Instead of X marking the spot, symbols represent electronic parts like resistors and chips.          Lines show how these parts        connect, forming a roadmap for electrons to follow and the relationships between components.
   - Here is the simple schematic for the Timer Board:

  ![minuterie_sch](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/7e60ca0e-22a4-4c2c-b0bc-c84f25289a40)
  
  - Here is the even simpler schematic for the Communicationc board:

  ![COM_sch](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/98f389e9-222b-4856-bf7c-5e7dab516c87)
  
-**PCB Layout:Putting Pieces in Place**
 - Like a Puzzle, but Better
    Once the map is ready, it's time to put things on the board. Imagine it's a puzzle where each piece (component) has its place. Engineers carefully arrange them, considering space, heat, and making sure everything works smoothly.

 - Copper Traces: 
  Think of Them as Electron Roads, Copper traces are like roads on our PCB. They guide electrons to where they need to go. Engineers need to plan these paths carefully, thinking about size, thickness, and where the roads lead, so the signals don't get stuck in traffic.
 - Vias: Secret Tunnels Between Layers

 In fancy multi-layer PCBs, vias are like secret tunnels connecting different layers. They help signals travel up and down, making sure everything stays connected and works like a charm.
 
 - Ground Planes: The Steady Supporters
  Ground planes act like the solid ground beneath our feet. They help stabilize the signals, making sure everything runs smoothly. Think of them as the glue holding everything together.
  Pads: Where Components Meet
 - Connection Points
  Pads are where electronic components shake hands with the copper traces. They come in different shapes and sizes, and how they're designed makes sure everything connects well and stays that way.
- Here are the insides of the Timer PCB:
  
![Minuteriededans](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/2fabacaf-7f56-481e-bc5f-82ec20e9e9c9)

 ### Ordering PCB's with JLCPCB:  https://jlcpcb.com/HAR
  ![image](https://github.com/DANY12345678910/-Exploring-ESO-s-Rocket-Tech/assets/107304619/4ee9833c-288d-443a-81d9-4e6ec579e143)
  
Now that we've finalized our PCB design, it's time to bring it to life. 
Ordering your PCBs is a straightforward process with our trusted partner, JLCPCB.
JLCPCB, a proud sponsor of our project, is a renowned name in the field of PCB manufacturing.

Here's how it works: You can order a minimum of 5 PCBs for an incredibly low price of just $2. 
To start the manufacturing process, simply visit JLCPCB's website (https://jlcpcb.com/HAR) and click on 
the "QUOTE NOW" button. 
Then, upload the Gerber file that you generated in the previous step. 
You can either upload the .zip file or simply drag and drop your Gerber files. 
Once your files are uploaded, a success message will confirm that your design has been received.

For peace of mind, you can review your PCB design using JLCPCB's Gerber viewer to ensure everything is in order.
You'll have the opportunity to inspect both the top and bottom layers of your PCB, making sure it
matches your specifications.

Now, here's the best part: You can order 5 PCBs for just $2, and if this is your first order with JLCPCB, 
you'll receive a fantastic offer of 10 PCBs for the same price of $2.
To proceed, click on the "SAVE TO CART" button, and you're on your way to having your PCBs manufactured.

Our experience with JLCPCB has been exceptional. 
Within just 2 days, our PCBs were expertly manufactured and dispatched.
Thanks to the efficient DHL delivery option, they arrived at our doorstep within a week.
Not only were the PCBs well-packaged, but the quality also exceeded our expectations, 
ensuring that our avionics system operates flawlessly in our rocket project.
Go to https://jlcpcb.com/HAR , and Follow them at JLC FB & PM to get coupon: https://www.facebook.com/jlcpcb.
  

 
 
