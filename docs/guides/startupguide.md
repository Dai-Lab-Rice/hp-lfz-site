# Startup guide
**Purpose**: A reference to be used *each and every time* by experienced users of the furnace.

---

## Section I: Turning on equipment
1. Create a new Growth Log in the "[Growth Logs](https://drive.google.com/drive/folders/1A3_43n8ItInI4Z7pf4uCt52mfkHWRzl-?usp=drive_link)" folder in the [LOKII Google Drive](https://drive.google.com/drive/folders/1-5bD7GNJCqUvJMFQOrpgeaQlDUMaeCdf?usp=drive_link).    

1. On the front of each of the seven laser units, turn the key clockwise to the "ON" position.
    ![laser_unit_front_cartoon.png](../img/laser_unit_front_cartoon.png){width=400}

1. On the front of the translator control unit, flip the power switch on the top right.
   ![translator_unit_front.png](translator_unit_front.png)

1. On Computer 1, open the camera software, Pylon Viewer ([more info]())
   ![pylon.png](../img/pylon.png)

1. On Computer 1, open the pyrometer software, DataTemp MultiDrop ([more info]())
   ![dtmd.png](../img/dtmd.png)

1. On Computer 2, open the thermocouple software, DP1001 AM ([more info]())
   ![tc.png](../img/tc.png)

1. On Computer 2, open the Laser Controller Software ([more info]())
   ![laser_software.png](../img/laser_software.png)

1. On Computer 2, open the webcam software to monitor the pressure gauge, Logitech Camera Settings ([more info]())
   ![webcam.png](../img/webcam.png)

1. On Computer 2, open the mass flow controller software, FlowDDE and FlowPlot ([more info]())
   ![mfc_software.png](../img/mfc_software.png)

---

## Section II: Loading your sample
1. Slide the bottom translator housing downward.

1. Clean all four sealing surfaces (top translator, top of chamber, bottom of chamber, and bottom translator) using a Kimwipe and IPA/EtOH. ([more info]())

1. Use an air duster to blow away the Kimwipe fibers off the sealing surfaces.

1. Place one seal ring on the top of the chamber, and one seal ring on the bottom translator. ([more info]())

1. Gently drop the shroud cup into the bottom translator, followed by a shaft collar (without set screw). ([more info]())

1. Position a collar on the bottom translator shaft, about 2 cm below the tip, and secure using the set screw.

1. Add an alumina washer on top of the collar.

1. Mount the seed rod in the seed rod holder and minimize precession. ([more info]())

1. Place the seed rod holder on the bottom translator shaft, and secure using the set screw.

1. Carefully slide the lower shroud piece over the seed rod (it may be necessary to translate the shaft downward at this point) and down into the translator to mate with the shroud cup. Rotate the lower shroud piece until the hole on the side is facing the gas outlet.

1. Place the shroud window on top of the lower shroud.

1. Carefully raise the lower translator housing upward until it is flush with the bottom of the chamber.

1. Carefully lower the top shroud piece into the chamber until it rests on the shroud window.

1. Mount the feed rod in the feed rod holder. ([more info]())

1. Measure the length of the mounted feed rod and record it in the Growth Log.

1. Attach an alumina washer and shaft collar to the upper translator shaft, about 2 cm above the tip.

1. Attach another alumina washer and the upper half of the feed rod holder to the upper translator shaft.

1. Slide the upper translator down until it is flush with the top of the chamber. Be careful not to collide the feed and seed rods!

1. Install the lower and upper clamps, and torque the bolts to 23 ft-lbs. ([more info]())

---

## Section III: Pressurizing the chamber

### If using Ar  or N$_2$

1. Close all low-pressure valves, including the mass flow controller (using FlowPlot software, set flowrate to `0.0`). ([more info]())

1. Ensure the inlet and outlet valves of the chamber are open.

1. Open the gas bottle.

1. First open the vent valve immediately downstream of the getter.
   ![vent.png](vent.png)

1. Starting from the gas bottle, sequentially open the valves which bypass the getter.

1. Using the FlowPlot software, flow gas to vent valve at the flowrate specified below, in order to flush out any oxygen in the low pressure piping. Flow for 5 minutes. ([more info]())
      - **Ar**: Setpoint = 50% (Flowrate = 5 SLPM)
      - **N$_2$**: Setpoint = 65% (Flowrate = 5 SLPM)

1. Open the valves immediately upstream of the getter, and close those bypassing the getter.

1. Open the round inlet valve of the getter.

1. SLOWLY crack open the round outlet valve of the getter. The getter may hold a high pressure from previous use.

1. Once the pressure in the getter has decreased, and the flow is less violent, close the vent valve. Gas should begin flowing towards the compressor / chamber.

1. Ensure the vent valve of the compressor is closed.

1. Turn on the compressor at a very slow rate in order to flush out any residual oxygen. ([more info]())

1. Close the chamber outlet needle valve and the chamber will begin pressurizing. Pressurize up to 200 psi, then close the chamber inlet needle valve, leaving the ball valve open.

1. Purge the chamber by slowly opening the outlet needle valve. Let the pressure drop to just above zero, but do not allow the pressure to reach exactly zero, because air may backflow into the chamber.

1. Close the chamber outlet needle valve once again, and carefully open the chamber inlet needle valve.

1. Repeat these steps (pressurize to 200 psi and purge) at least 5 times.

1. (Optional) To sinter / dry the feed rod, turn on the laser emission and raise the power until the rod begins to glow, without melting it. Translate the rod through the laser beam to remove any residual moisture. It is recommended to perform another purge cycle on the chamber after this procedure.

1. Bring the feed and seed rods to their starting positions.

1. Close the chamber outlet needle valve and ball valve, and the chamber will begin pressurizing. Allow the chamber to reach the bottle pressure (usually around 1,000 psi), or the desired pressure, whichever is lower.

1. If the desired pressure is higher than the bottle pressure, turn on the compressor by opening the valve to the drive air and slowly increase the drive air pressure (using the regulator attached to the compressor) until the desired pressure is reached. Operate the compressor at a slow rate, such as 2 strokes / second.

1. Set the final pressure by using the high-pressure regulator downstream of the compressor. Also, ensure the compressor does not reach a pressure significantly higher than this by controlling either the drive air pressure (using the drive air regulator) or by controlling the pressure limit switch of the compressor.

1. Optionally close the inlet or outlet valves, depending on whether or not you want to have a constant inlet to maintain pressure or if you want constant venting (gas flow).

### If using 80:20 Ar:O$_2$

1. Close all low-pressure valves, including the mass flow controller (using FlowPlot software, set flowrate to `0.0`). ([more info]())

1. Ensure the outlet valves of the chamber are open.

1. Open the inlet ball valve, but leave the inlet needle valve closed.

1. Open the gas bottle.

1. Open the valves which either (a) pass through the mass flow controller or (b) bypass the mass flow controller.

1. Allow the chamber to reach the bottle pressure (usually around 1,000 psi), or the desired pressure, whichever is lower.

1. If the desired pressure is higher than the bottle pressure, turn on the compressor by opening the valve to the drive air and slowly increase the drive air pressure (using the regulator attached to the compressor) until the desired pressure is reached. Operate the compressor at a slow rate, such as 2 strokes / second.

1. Set the final pressure by using the high-pressure regulator downstream of the compressor. Also, ensure the compressor does not reach a pressure significantly higher than this by controlling either the drive air pressure (using the drive air regulator) or by controlling the pressure limit switch of the compressor.

1. Optionally close the inlet or outlet valves, depending on whether or not you want to have a constant inlet to maintain pressure or if you want constant venting (gas flow).

---

## Section IV: Setup static gas pressure or gas flow
**If using static pressure**, close chamber inlet valves, turn off the compressor (if applicable), and move on to the next section.

**Otherwise, if using gas flow**, leave chamber inlet valves open and the compressor on, and refer to the following steps:

1. Set the high-pressure regulator downstream of the compressor to your desired pressure.

1.

1. Close the inlet needle valve.

1. With the outlet needle valve closed, open the outlet ball valve.

1. Carefully open the outlet needle valve to allow a small flow.

1. Carefully open the inlet needle valve to allow a small flow.

1. Balance the outlet and inlet needle valve until a desired equilibrium is reached.

---
## Section V: Begin growth

1. Bring the feed and seed rods to their starting positions.

1. Focus and align the camera and pyrometer on the seed rod. ([more info]())

1. Place the notch filter in front of the pyrometer. ([more info]())

1. Slide a neutral density filter in front of the camera, if desired. ([more info]())

1. Place the laser safety sign on the outside of the door.

1. Close the laser curtains.

1. Press the green "Start" button on the front of each laser unit to enable emission. ([more info]())

1. Enable communication with all seven lasers in the Laser Controller Software.

1. Start the pyrometer Data Recorder. ([more info]())
   
1. Start the screen recorder. ([more info]())

1. Begin growth! ([more info]())
