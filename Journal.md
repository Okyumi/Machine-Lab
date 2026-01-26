> If you fail, Congratulations! Most people don't even try.

### Jan 22 Lecture

- **Notes on the whiteboard:**

  <p align="center">
    <img src="media/JAN22_notes_girds.jpeg" alt="Whiteboard notes (grids)" width="560" />
  </p>

- **Additional notes:**

  - For soldering, we need three hands, but as human beings we only have two. That’s why we use a third hand tool (a stand that holds the wire in place). Adjust the helping hands so you can solder comfortably.
  - Wires are usually made of copper. Stranded wire is better for long term use, and solid wire is better for short term use.
  - To strip a wire, clamp at the right gauge (which match the diameter of the wire), then squeeze and pull to remove the insulation.
  - Do not inhale the white smoke/ hold your breath.
  - Do not jab the tip into the brass cleaner aggressively.
  - An actuator is the opposite of a sensor.
  - A DC motor uses voltage or PWM to control speed and torque, while a servo motor is a motor plus a gearbox, a sensor (usually a potentiometer or encoder), and control electronics in one package. Servos are good at precise positioning and holding a position against a load.
  - The black part of the iron tip is oxidized; use the shiny part for soldering.

### Jan 22 Practice Soldering 1

- Practice soldering some wires and some header pins to a circuit board from
  the "practice" bin. Bring the board to class and show us your five best
  wires and five best pins.

  <p align="center">
    <img src="media/JAN22_solderingworkstation.jpeg" alt="Soldering workstation" width="560" />
  </p>

**Preparation:**

  <figure align="center" style="margin: 1em 0;">
    <img src="media/JAN22_practice_prep.JPG" alt="Practice prep: wire stripping, perfboard, helping hands" width="560" style="border-radius: 8px; max-width: 100%;" />
  </figure>

  - Strip the wire -> grab header pins and a perfboard -> Use the helping hands to hold the header pins and perfboard in place, then of course use your amazing clamping skills and a steady hand to keep everything perfectly aligned -> how about a PCB?

---

### Jan 25 Studying

- **Reading resources:** 
    - Read and watch [Soldering
    Resources](https://github.com/michaelshiloh/resourcesForClasses?tab=readme-ov-file#soldering-resources), [Debugging
    Resources](https://github.com/michaelshiloh/resourcesForClasses?tab=readme-ov-file#debugging-resources), [Digital Multimeter (DMM)
    resources](https://github.com/michaelshiloh/resourcesForClasses?tab=readme-ov-file#digital-multimeter-dmm-resources)


**Soldering Resources**

1. Adafruit [guide](https://learn.adafruit.com/adafruit-guide-excellent-soldering?view=all) to excellent soldering
2. Sparkfun Through Hole Soldering [tutorial](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering)


**Debugging**

1. Clay Shirky's 4 part [video series](https://vimeo.com/channels/debugging) on debugging

**Digital Multimeter (DMM) resources**

1. Adafruit Digital Multimeter [tutorial](https://learn.adafruit.com/multimeters?view=all)
2. Sparkfun Digital Multimeter [tutorial](https://learn.sparkfun.com/tutorials/how-to-use-a-multimeter)

**Notes taken:**
- Soldering iron, wonderful tool to bond metals at molecular level.
- do it quick, less than 2s, so that it doesn't damage any other components
- flux removes the oxidation, leaving the surface clean and ready to fuse to the solder alloy
- lead-based is easier than lead-free, but lead-free is more common nowadays.
- We solder with solder XD!
- As you solder, your tip will tend to oxidize, which means it will turn black and not want to accept solder.
- Brass sponges pull the excess solder from your tip while allowing the tip to maintain its current heat level.
- a rule of thumb of debugging (which by the way i highly agree): make it works first, then make it clean, then make it fast. Do no change more than one variables during the debugging. Do tests all the time.
- multimeter was first made in 1820s.
- Continuity: whether two points are elecrically connected to one another -> great to check solder bridges
- Resistance: keep increasing the range setting until the meter displays multiple digits appear. (you can also use smart tweezer rather than multimeter)
- Voltage: you can also use probe meter.

---
### Jan 26 Practice Soldering 2
- Let’s take a look at what an unremarkable little genius solderer(?) did for her soldering practice. Shall we?

  <figure align="center" style="margin: 1em 0;">
    <img src="media/JAN26_practice_headerpins.jpg" alt="Header pins soldering practice, 1st to 5th" width="560" style="border-radius: 8px; max-width: 100%;" />
  </figure>

- Header pins, from left to right 1st -> 5th. The first one looks ugly, both in shape and because I awfully bridged pin 3 and pin 4. but look at the 5th one, well, it looks decent.

- Some of the difficulties I encountered : we need a forth hand for the first pin.
- A takeaway: for a cleaner joint, feed the solder on one side of the donut, and place the iron tip on the opposite side so the solder flows toward the heat.

  <figure align="center" style="margin: 1em 0;">
    <img src="media/JAN26_practice_wire1.jpg" alt="Helping hands and wire stripping" width="560" style="border-radius: 8px; max-width: 100%;" />
  </figure>

- Soldering for wires: If you always twist wire A onto wire B, wire A gradually ends up shorter. It works better if you start by twisting A around the middle of B, then twist B around A.

- Some wires I soldered.

  <figure align="center" style="margin: 1em 0;">
    <img src="media/JAN26_practice_wire2.jpg" alt="Wire soldering: twisting and joint stages" width="560" style="border-radius: 8px; max-width: 100%;" />
  </figure>


- Oh another takeaway: pick a good soldering iron in IM lab. As some makes you feel quite incompetent, others make you feel like you were born to be an engineer.

