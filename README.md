# rack_parts
I'm posting the models I used for my 10" mini-rack project here. With two exceptions* these are all my own designs.


(* The optiplex/thinkcentre shelf is a remix of [a design found on onshape from user "salemz"](https://cad.onshape.com/documents/edc2be91c8a5c8ce739145d0/w/da46e5e176b4d39cc755736e/e/9c80555ae34e66083f173074). The 5.25" brackets are remixed from [this hardwarehaven model](https://www.thingiverse.com/thing:6859441) and intended to be installed inside/over a deskpi 1U rack shelf for support.

The rack:
![an 8U minirack](/PXL_20250305_000510257.MP(1).jpg)

All panel designs conform to this very professional design doc:
![a post-it note](/tab_design.jpg)

I've been running three micro PCs for a while and when I saw all of the initial 10" rack coverage last fall/winter (particularly hardwarehaven's 3d printed setup) I decided to plan my own build. I didn't originally intend to use the Geeekpi rack but it had a price drop around the same time I was getting frustrated pricing out different panel/enclosure options for my rack-rail skeleton.  
So, I transplanted everything into the Deskpi but it's extremely shallow so I reused two rack rails to add about 50mm to the total depth of the setup.  
![close up of the extension being test-fit](/img/extensions.png)  
It was important to me that this thing stay as enclosed and cat-proof as possible, as well as having as few wires leaving it as I could get away with. The rear panel arrangement holds a [4-spot power strip](https://www.amazon.com/dp/B07XXLPNJ7), facing inward, as well as a 120mm exhaust fan.  
![rack from behind](/img/rear.png)  
All 3 PC power bricks live in the bottom 2U along with a [Meanwell RS-50-12](https://www.digikey.com/en/products/detail/mean-well-usa-inc/RS-50-12/7706187) to power the fan, network switch, and the USB adapter for the bluray drive.  
![front view looking into the unsecured pile of power bricks and cables](/img/basement.png)  
![the meanwell PSU screwed down to the shelf. that fan adapter is a custom pcb sorry](/img/meanwell.png)  

The [patch panel](https://www.amazon.com/dp/B0CMGN4X58) sits a few millimeters out from everywhere else because it's got a couple of protruding metal tabs that make it too wide for the Rackpi's rails. I printed little shims to make it fit evenly. It's set up with a network, USB, and HDMI passthrough for each of the 3 computers. The USB passthroughs were completely unnecessary because they all have front panel ports. The Thinkcentre's HDMI jack is not hooked up because that machine only has displayport (😠). The other 3 ports are: 1 blank, 1 custom 5mm dc barrel jack passthrough for the switch's power, and 1 fiber optic passthrough.  
  
All three computers have 2.5Gbit M.2 NICs in them, and the [switch](https://www.amazon.com/dp/B0CFTDLDQL) is 2.5Gbit as well as an SFP+ fiber link to my other 2.5Gbit/SFP+ switch.