# PiArcade Cabinet
An arcade cabinet for a raspberry Pi as built by Daddy and Bradley Eastbury on 01-Feb-2020

I have had tons of requests for instructions on how to build this on facebook, so I tried to put them down and figured the only thing cooler than a home made retro arcade cabinet, would be an open-source designed home made retro arcade cabinet!

This is from memory, so if I missed or forgot any steps I apologise - but since I was making up as I went along to build this, you'll have to forgive me! Please let me know at willeastbury@gmail.com if you build one of these and how you got on.

## Electronics
- 24" LCD Monitor
- Raspberry Pi 3B + PSU + 128GB SD Card (You'll need a big one for all of the images you licence).
- USB Keyboard and Mouse
- Button and joystick kit - order online, [Here's the one that I used where the buttons have printed text and they light up ]( https://www.amazon.co.uk/dp/B07FYS5M2Q/ref=sspa_dk_detail_3?psc=1&pd_rd_i=B07FYS5M2Q&pd_rd_w=YsjjR&pf_rd_p=1055d8b2-c10c-4d7d-b50d-96300553e15d&pd_rd_wg=EVrRE&pf_rd_r=6XNF3K6NBPTFZ81XA63X&pd_rd_r=acdc2bf2-392b-4a0a-a05f-9219e6366824&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFJWThJWkNNVjZES00mZW5jcnlwdGVkSWQ9QTAyOTAyMTAyUklZQktaVEQxQjRUJmVuY3J5cHRlZEFkSWQ9QTA0NjM4MzcxWFpMRFNDQ0IwV1NDJndpZGdldE5hbWU9c3BfZGV0YWlsJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
- Small self-powered active speaker
- 3-way Extension lead

## Tools Needed
- Drill / Driver
+ 2mm Drill bit for pilot holes
+ 25mm Drill bit / Hole Cutter for button and joystick holes
+ 5mm Drill bit for acrylic fixing holes
+ Pz2 Screwdriver bit 
- Jigsaw and / or circular saw
- Ruler 
- Tape Measure
- Stanley Knife, for cutting the acrylic
- If you can be bothered, a countersink

## Materials needed
- i 2400mm x 600 x 16mm white furniture board
- ii 600mm x 300 x 16mm grey furniture board 
- iii 2400mm x 400mm x 16mm white furniture board (x2)
- iv Untreated timber 2400mm x 38mm x 47mm  (x2)
- v Medium length ~3cm Pz2 wood screws x24 (These are used to build the white cabinet case / frame and to screw the support battens in place inside the cabinet.
- vi Small length ~1cm Pz2 wood screws x14 (These are to fix the Angled Screen supports in place and to attach the joystick to the underside of the console panel)
- vii Long 5cm Pz2 wood screws x2 (These are to screw the grey console panel to the cabinet)

## Cutting List 
- A Rear Panel (16mm White Furniture Board 600mm x 1300mm) cut from (i)
- B 2x Identical Side Panels (16mm White Furniture Board x 1500mm x 400mm ) cut from (iii) ** Additionally cut these panels diagonally from the top right edge down to the 1300mm height on the left edge if facing down on this on the flat.
- C Front Panel (16mm White Furniture Board x 600mm x 1000mm) - cut from (i)
- D Roof Part 1 (16mm White Furniture Board x 600mm x 400mm) - cut from (iii)
- E Roof Part 2 (16mm White Furniture Board x 600mm x 100mm) - cut from (i)
- F 2x Angled Screen Support - Offcuts left from diagonal cut of B above
- G Internal pi shelf (16mm White Furniture Board x 600mm x 400mm) - cut from (iii)
- H Console Panel (16mm Grey Furniture Board) cut from (ii)
- I Clear Acrylic Panel (I used LiteGlaze) cut to the screen aperture size (depends on the exact size of the screen you will be using but should be around 568mm wide and about that deep. To cut this - you score it deeply with the Stanley Knife and apply light pressure with the acrylic sandwiched between 2 pieces of wood.
- J 2x Internal Horizontal Support Battens - cut from (iiii) (Timber 568mm x 38mm x 47mm)
- K 2x Internal Lateral Support Battens - cut from (iiii) (Timber 300mm x 38mm x 47mm)

## Instructions
Get the builders merchant / hardware store to do as much of the cutting as you can get them to and keep the offcuts, they will come in useful as some of the parts are simply offcuts themselves! 

NOTE: Before you start check the *exact* width of the monitor, if it's more than 568mm across, then you will need to adjust the sizes below, or buy a smaller monitor - it just happened that our monitor  was EXACTLY the size of the aperture when accounting for the maximum 600mm width of the furniture board - the width of the 2 sides at 16mm each. If yours is bigger you will need to account for  this in the way you attach the frame and the width of the battens.

Note that when you attach the parts togethe, drilling a pilot hole is a good call with the 2mm drill bit or you will probably crack the furniture board, if you want a flush finish - countersink the screw hole before screwing in the screws.

1. Buy the parts in the materials list from a local hardware / DIY store, if you're in the UK, B&Q stock these exact measurements, they will also cut some of the wood for you for free on their band saw.
2. Cut the wood and acrylic down as described in the cutting list.
3. Go and install retropie on your Rpi3 https://retropie.org.uk/
4. Start with the rear and 2 sides, attach them together with 4x medium length screws (v) for each sid so the interior of the cabinet is 568mm wide to match the exact width of the monitor.
5. Next attach the larger roof panel to the top of the cabinet, right at the front , this will leave you a small gap at the rear, leave that for now, put the screws a little back from the front edge of the side panels though, you don't want them to appear through the front of the cabinet! 
6. You should now have a shell resembling an empty arcade cabinet, put 2x support battens inside the aperture, level at around 1m from the base of the cabinet. One at the front and one at the back.
7. Place 2x extra lateral support battens along the line of the other 2 (so you have a 'square' of 4x supports inside the cabinet, one on each edge)
8. Screw G (the pi shelf) to the bottom of these supports leaving a gap on the right for cables to pass through.
9. Screw the monitor angle supports (F) to the very back of the left and right side panels, pressed against the back of the cabinet. Yuo should have one in each corner with the longest side of the triangle facing towards the front.
10. See how far down your monitor comes when placed on the monitor supports, and mark this point. 
11. Screw another horizontal batten to the point you just marked and put the monitor on top of it and the supports.
12. Connect up the Pi and monitor and power etc. 
13. Use the hole saw / 25mm drill bit to drill out the button markers for your buttons on the grey console panel, which will just drop into the holes (Be careful of the fact that you need to leave space for the faceplates of the joysticks, so  be sure to leave space for them on the underside. Also don't  go too near to the bottom of the console panel as when you attach it there needs to be clearance to the batten height. 
14. Drill 2x holes in the front panel for the coin op buttons. 
15. Mount the buttons to the console and front panel, and connect them to the Pi with the usb controller panel, you can route the cables through the gap next to the pi shelf.
16. Connect the speaker to the pi if you have one. and pop this collection of items on the pi shelf.
17. Run the extension cable in through the roof hole and attach the items to the mains power.
18. Attach the front panel to the cabinet *making sure you route the USB cables for the kbd and mouse up through the hole in the top of the cabinet roof first*.
19. Power on the Pi.
20. Test your setup - once you are happy - we can finish the task.
21. Drill 2 holes in the bottom of the acrylic to screw it to the horizontal batten.
22. Screw the acrylic in place to fix the monitor behind it.
23. Now you can close the hole in the roof by screwing down piece E.
24. Take the long screws and screw in the console panel to the front batten.

25. You're done. Enjoy some retro gaming.



