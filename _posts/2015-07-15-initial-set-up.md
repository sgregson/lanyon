---
published: false
---

1. *definitely take the props off before doing ANYTHING.*
2. **TAKE THE PROPS OFF**
  - The lumenier motors are standard-threaded, so you hold the outer housing of the motor and rotate the prop nut CCW with a hex key

> It was the first thing I did and I'm SO glad. By the time I finally got the flight controller armed I had forgotten that I'd need to, and the motors just spring to life! The props idle slowly when the FC is armed

There's a [unboxing and setup video](https://www.youtube.com/watch?v=9xQhi0h5v7c) from a youtuber called flightclub which shows the orientation on how to connect the **FC to the FrSky Rx**. Note the [gnd/+/-] orientation and the jumper plug for cppm+telemetry on CH1.

Initial vTx freq is channel 1 on the FatShark default band, so tune ur goggles appropriately first. *OMG THIS OSD IS SWEET*

The wizard did all the configuration I needed (minus the flight mode switch...still working on that). I had to invert the throttle on the turnigy to get the wizard to read it's input properly. I don't know if that's a general issue or unique to me - might be related to a possible trim issue below. (I think i'd need to connect to cleanflight to see if the throttle min/max is set correctly).

Once done, wiggle the roll/pitch stick (mode 2) and it'll fire up the telemetry OSD. So cool.

Something I didn't know before starting was how to arm and disarm the flight controller. Makes sense, but it took me a bit of head-scratching, "why aren't the motors moving" moments. The full vortex instruction guide has you covered, though (doc heading "flight controller stick commands") and how to enter configuration mode for the OSD. I learned that from an [OSD setup video](https://www.youtube.com/watch?v=G9k92lb-hEg) from UmmaGawd.

Anyway, I am SO excited to get this guy in the air, there's no perceivable latency to the goggles, and all the OSD modes are neat (HUD mode and it's live artificial horizon....awesome), and just the fact that you can control the OSD with the transmitter sticks is CRAZY.