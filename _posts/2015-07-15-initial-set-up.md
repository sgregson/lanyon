---
published: false
---


1. *definitely take the props off before doing ANYTHING.*
2. **TAKE THE PROPS OFF**
  - The lumenier motors are standard-threaded, so you hold the outer housing of the motor and rotate the prop nut CCW with a hex key

> It was the first thing I did and I'm SO glad. By the time I finally got the flight controller armed I had forgotten that I'd need to, and the motors just spring to life! The props idle slowly when the FC is armed, but if you bump the throttle, you're going to get a quadcopter-sized-hole in your ceiling.

In order to get the Turnigy 9x talking with the Vortex, you'll need to use the FrSky DJT module (or DXT ) and do a tiny amount of transmitter modding. It's really straightforward and will take about ~30min. Make sure to:
1. desolder the existing antenna
2. cut down the plastic exposed in the JR module bay
3. swap the JR module for the DJT. It should seat easily, don't force it.

With the FrSky module in place, make sure you have a clean profile for your module on your transmitter. For the 9x, that's pretty straightforward once you figure out that "Mode" means "Model" - "Mode 1" on the main screen means "model 1" o_O. Use ACRO mode for the config or at least be sure that the mode you choose doesn't link the throttle and pitch controls (some HELI modes will).

There's an [unboxing and setup video](https://www.youtube.com/watch?v=9xQhi0h5v7c) from a youtuber called flightclub which shows the orientation on how to connect the **FC to the FrSky Rx**. Note the [gnd/+/-] orientation and the jumper plug for cppm+telemetry on CH1.

Initial vTx freq is channel 1 on the FatShark default band, tune your goggles appropriately. Plug in the antennae first, then batteries (copter+video) and you'll be in the configuration Wizard! (*OMG THIS OSD IS SWEET*) Also, **make sure the Quad is on a level surface**, as it'll calibrate the accelerometer once the Wizard completes.

The Wizard did all the configuration I needed (minus the FC mode switch...still working on that). I had to invert the throttle on the turnigy to get the Wizard to read it's input properly. I don't know if that's a general issue - might be related to trim cutoffs. (I think i'd need to connect to cleanflight to check throttle min/max values).

Once done, wiggle the roll/pitch stick (mode 2) and it'll fire up the telemetry OSD. So cool.

The full vortex instruction guide shows how to arm the FC and how to enter configuration mode for the OSD (doc heading "flight controller stick commands"). That's where you go to tweak your **SICK** LED tail-lights. I learned that from an [OSD setup video](https://www.youtube.com/watch?v=G9k92lb-hEg) from UmmaGawd.

I am SO excited to get this guy in the air, there's no perceivable latency to the goggles, and all the OSD modes are cool (HUD mode and it's live artificial horizon....awesome, but ezOSD is probably the most useful), and just the fact that you can control the OSD with the transmitter sticks is CRAZY.