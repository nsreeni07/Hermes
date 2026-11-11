---
title: "Hermes"
github: "https://github.com/nsreeni07/Hermes/"
description: "A 1.7m dual-deployment rocket for both L1 and L2 certification flights, with two redundant flight computers each able to trigger deployment independently. The custom Polaris board also logs data and GPS, with LoRa telemetry in progress for live ground tracking.\n\n"
created_at: "2026-11-10"
total_time: "9h 48m"
---

# November 10, 2026: OpenRocket
<!-- fabricate:entry 2581 -->

So today I planned out my overall idea for my rocket, I named it Hermes and this rocket will be used for both my L1 and L2 certifications. It is 1.7m in length, has a 34mm motor mount to hold a variety of motors and uses a dual deploy system.

A dual depoly system basically means that instead of releasing just on big parachute at apoggee and letting the rocket drift for that time, there initally is something called a drogue chute which is a small chute that only slow the rocket down adn minimzes drift, and after the rocket reaches a lower altitude it depolys the main parachutes(close to 100-120m).

The parachutes will be deployed using pyrotechnics, and will be timed with an onboard flight computer. Now I already have built a flight computer in the past that I could use for this flight, But that computer is still in the testing stages, so in the coming day’s im going to decide wheter I should just use that flight computer or get another seperate flight computer for redundancy.

The rocket will be made of a cardboard airframe and strengthened with an extra layer of fiberglass, This will probably be only for the main body and not the nose cone but I might also do it for the nose cone in the future. Beside that I’m going to have to figure out the flight computer dilema work more on bringing my stability caliber closer to 0 and beginning the Cad, and ya thats it.

![](https://fabricate.hackclub-assets.com/c171ee21af117faec43fee2a1d5aa649268d9650546fe25a48133f41b38223f8/image-png/image.png)

**Total time spent: 1h 12m**

# November 10, 2026 (entry 2): Cad
<!-- fabricate:entry 2582 -->

So today I mainly worked on the CAD model, I modeled all the body tubes centering rings and started work on the avionics bay , I’m going to use around 1/4in wood as bulkheads and use 3/8th threaded rods that hold everything together + 2x 3/8 steel u bolt to attach the parachute lines too. The main avionics sled will be 3d printed and will hold the flight computer. Now After though I decided to make a new flight computer for this rocket because the previous one is more tailored toward my TVC rocket and doesnt have things like telemetry which I need. I main reused a lot of the schematic from the first version of the computer but I switched to an STM32H743VIT6 which was a bunch more gpio pins which I need, I also added a Ra-02 for telemtry, and has an ATGM336 gps, the imu and barometer is still the same as my old one, and it has multiple pyro and servo channels. Other than that I’m going to start doing to routing tmrw and I might do some to today maybe?
Other than that I’m going to start making the BOM and finalizing the Cad.

![](https://fabricate.hackclub-assets.com/14007270adb2735c06c6b295dffdbbc3a3f6796d06e3bbc11f54dcf0da20b48f/image-png/image.png)

![](https://fabricate.hackclub-assets.com/a6fac85979b84e37a72b8d1bd77eecd40b42580c4d65b18ea42c9a9266e7cd08/image-png/image.png)

![](https://fabricate.hackclub-assets.com/31c96abe8e6aa990ebd3fdf87ce332a6302b0dc1b3154c385adbf7d6de3fb76f/image-png/image.png)

**Total time spent: 2h**

# November 10, 2026 (entry 3): Bom and cad
<!-- fabricate:entry 2583 -->

I did work on my cad and layed out how everything will work. I’m going to use u bolts to hold all the parachute lines together, and for the avionics bay I’m going to use 3/8 threaded rods and 0.5in bulkhead made of wood. Other than that I just have to finalize the BOM for the project and then submit and hopefully fix the whole pcb issue.

![](https://fabricate.hackclub-assets.com/d0ca0623c66b6007d79b3cb09857beaf26454c3ed6de6366607f234d029cee6d/image-png/image.png)

![](https://fabricate.hackclub-assets.com/810aa744ebcec0917bb6e918051b6af428c353bff1266d59f69ef7ccf290ecf6/image-png/image.png)

![](https://fabricate.hackclub-assets.com/069f308977ebb6c1a4df587c47726254b6c6d9aec4db380b719d79c03526a993/image-png/image.png)

![](https://fabricate.hackclub-assets.com/9c3fa0fae6c4a5b3a4fa6096be828f74892b50bfa7400923c81da1572f606904/image-png/image.png)

**Total time spent: 1h 30m**

# November 10, 2026 (entry 4): BOM
<!-- fabricate:entry 2584 -->

So today I mainly worked on my pcb and Bom, I first started by making the BOM for the project and finding the cost of everything I would need, The main cost for this project are for the main flight computer which is around $400 which is crazy but I have someone who works at jlcpcb who sponsored an old project of mine and could help me with this, Other than that I need around $270 for the main rocket but I think I can bring that cost down. Also after asking for help in a reddit rocketry channel I was recomended to use an off the shelf flight computer because it wouldn’t be a good idea to put a brand new flight computer in charge of pyrotechnics. For that I chose the Eggtimer Quantum which is a cheap $40 flight computer which will control the pyro charges. I also worked on the pcb and solved some drc errors, and finished routing some small resistors and whatnot, I still havent heard anything about the missing lapse for the pcb but we will see, For now the final things will be to finalize the BOM wrap everything up.

![](https://fabricate.hackclub-assets.com/7f747a45e87968c391ea7cd3ac791ede5a7056f61a679dca82643a93b91ce2d9/image-png/image.png)

**Total time spent: 2h**

# November 10, 2026 (entry 5): Finalizing
<!-- fabricate:entry 2585 -->

So Today I finalized my BOM and my cad, I tried out blender for a while and realized that I was just not made for it, I’ll try and learn it but it will take a while probably, for the pcb I was able to bring the cost down to around $250 which puts me within the budget and I also made a stencil on google slides which I will paint onto the rocket as like a livery to make it look nicer, Other than that I finished some small drc errors on the pcb and thats it I’m going to be submitting and hoping!

![](https://fabricate.hackclub-assets.com/40e639207f54e276d3e0734fc7401d0ad8e39b35e770bf01c38561d4412f4699/image-png/image.png)
![](https://fabricate.hackclub-assets.com/b33ecef1fa671de929fbc869658362945ee12f17d11746a69cc05a0e38d68a37/image-png/image.png)

![](https://fabricate.hackclub-assets.com/424ba64c58d3ca2e3576d82490d3b62fb353db58024620e4714a646c8163547b/image-png/image.png)

**Total time spent: 2h**

# November 10, 2026 (entry 6): Note to Reviewer
<!-- fabricate:entry 2586 -->

You may see that I have also made a flight computer for this project, I am not requesting funding for that. The funding requested is solely for The rocket and the structural components.
![](https://fabricate.hackclub-assets.com/ae9672457b4e9b618f6cc1a56e049ff4bb28fac9cce052931bba881f1cf2f695/image-png/image.png)

**Total time spent: 6m**

# November 10, 2026 (entry 7): Sled Update
<!-- fabricate:entry 2598 -->

so today I updated my bom because I'm only asking funding for the rocket as previously said also i asked in the help channel wheter i could buy this runcam as part of my grant and hopefully I can because there is this used one for a really good price and if I cant thats fine too, my total right now is 400 and with the runcam would go to 485 other than that I updated the cad model and the onshape and after i get the confirmation for the runcam i'm gonna submit. 

![](https://fabricate.hackclub-assets.com/d4d5e188c19998043f9bc12d30c0785ba4e53bf64d451ba5b4d8a21971be0841/image-png/image.png)

**Total time spent: 1h**
