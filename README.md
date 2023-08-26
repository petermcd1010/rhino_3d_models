# Rhino Robots 3D Models

This repository contains 3D models for use with Rhino Robots. They are free for any and all use.

## Rhino Robots

[![Arduino Robot Control](https://user-images.githubusercontent.com/39977360/208218280-c486106f-3dde-4b0c-94fe-75af42436de9.gif)](https://www.youtube.com/watch?v=jSTG7T9-4lo&feature=youtu.be)

Sandhu Machine Design Inc. of Champaign, Illinois produced a [series](http://www.theoldrobots.com/rhinoarm.html) of servo-controlled Rhino Robots in the 1980s. These robots were scaled down versions of their industrial counterparts (less expensive and less poweful). They were created for education, research, and industrial training.

Today you may find them at government auctions, on eBay, or collecting dust in a closet at your local university's engineering lab.

### Raspberry Pi 4 with PoE or PoE+ Hat

![Raspberry Pi 4 and hat stacked](rpi4_hat_stacked.png)

These 3D-printed Raspberry Pi 4 enclosures fit a Raspberry Pi 4 with a PoE or PoE+ hat. By default, the hats do not make the GPIO pins accessible. To address this, these designs require you to sandwich two extra tall 40-pin and 4-pin header blocks between the Raspberry Pi and the hat. You can purchase the "4 & 40 Pin Extra Tall Header (Push Fit Version) - POE HAT Set" from PiShop.us. You will need to clip the 4-pin header pins for the PoE+ hat to the correct length (I guessed and was lucky). The older PoE hat does not require clipping.

Also print the four Raspberry Pi 4 Spacer Pins below and insert them between the Raspberry Pi 4 and the hat. These pins provide stability to the boards and also lock them into the enclosure once it's closed.

![Raspberry Pi 4 base inset nuts](rpi4_base_inset_nuts.png)

To insert the hexagonal M3 nuts into the base, do not try to press them in by hand. Instead, slide an M3 screw through from the other side, attach the nut, then tighten the screw to pull the nut into the hole.

### Raspberry Pi 4 base for XR-1

![Raspberry Pi 4 base for XR-1](rpi4_base_xr1.png)
![Blender .blend](rpi4_base.blend), ![.stl](rpi4_base_xr1.stl)

For the XR-1's RPi4 base, replace the two #6-32x3/8” fasteners along bottom plate of the robot shoulder with longer ones. Bolt Depot 22746 stainless steel 18-8 black oxide finish #6-32x1/2" socket caps work well. Also replace the #6-32x1/2” fastener located at center of the XR-1 shoulder joint with a #6-32x3/4” fastener (Bolt Depot 22748). For best strength, place a steel washer (Bolt Depot 22027) between the top of the fastener and the top of the printed plastic mount for additional strength.

### Raspberry Pi 4 base for XR-1 with Google Coral USB TPU mount

![Raspberry Pi 4 base with TPU for XR-1](rpi4_base_xr1_with_tpu.png)
![Blender .blend](rpi4_base.blend), ![.stl](rpi4_base_xr1_with_tpu.stl)

Follow the same instructions as the mount without the TPU, but insert four additional M3 hex nuts into the back of the base below the TPU. Then fasten the TPU to the base with four M3x12 fasteners.

### Raspberry Pi 4 base for XR-2

![Raspberry Pi 4 base for XR-2](rpi4_base_xr2.png)
![Blender .blend](rpi4_base.blend), ![.stl](rpi4_base_xr2.stl)

For the XR-2's RPi4 base, replace the two #6-32x3/8” fasteners along bottom plate of the robot shoulder with longer ones. Bolt Depot 22746 stainless steel 18-8 black oxide finish #6-32x1/2" socket caps work well. Also replace the #10-24x3/8” fastener located at the top left of the enclosure base with a #10-24x5/8” fastener (Bolt Depot 22757).

### Raspberry Pi 4 base for XR-2 with Google Coral USB mount

![Raspberry Pi 4 base with TPU for XR-2](rpi4_base_xr2_with_tpu.png)
![Raspberry Pi 4 base with TPU for XR-2 printed](rpi4_base_xr2_with_tpu_printed.png)
![Raspberry Pi 4 base with TPU for XR-2 mounted](rpi4_base_xr2_mounted.png)
![Blender .blend](rpi4_base.blend), ![.stl](rpi4_base_xr2_with_tpu.stl)

Follow the same instructions as the mount without the TPU, but insert four additional M3 hex nuts into the back of the base below the TPU. Then fasten the TPU to the base with four M3x12 fasteners.

### Raspberry Pi Base (Plain)

![Raspberry Pi 4 base plain](rpi4_base_plain.png)
![Blender .blend](rpi4_base.blend), ![.stl](rpi4_base_plain.stl)

This base without Rhino Robot mount points is provided here for reference.

### Raspberry Pi 4 Spacer Pins

![Raspberry Pi 4 spacer pins](rpi4_spacer_pins.png)
![Blender .blend](rpi4_spacer_pins.blend), ![.stl](rpi4_spacer_pins.stl)

Print one set of four spacer pins for each RPi 4. Sandwich them between the RPi 4's base PCB and the PoE or PoE+ hat's PCB. The pins on the end of the spacer lock the PCBs into the base and top of the Raspberry Pi 4 enclosure.

### Raspberry Pi 4 PoE Hat Top

![Raspberry Pi 4 PoE top](rpi4_poe_hat_top.png)
![Blender .blend](rpi4_top.blend), ![.stl](rpi4_poe_hat_top.stl)

Fasten the top to the base with four M3x16 fasteners.

### Raspberry Pi 4 PoE+ Hat Top

![Raspberry Pi 4 PoE+ top](rpi4_poe+_hat_top.png)
![Blender .blend](rpi4_top.blend), ![.stl](rpi4_poe+_hat_top.stl)

Fasten the top to the base with four M3x16 fasteners.

### Arduino Base for XR-1

![Arduino base for XR-1](arduino_base_xr1.png)

![Blender .blend](arduino_base.blend), ![.stl](arduino_base_xr1.stl)

For the XR-1's arduino base, you should replace four socket caps (hex bolts) with longer ones. Bolt Depot part number 22746 stainless steel 18-8 black oxide finish, #6-32 x 1/2" socket caps work well.

### Arduino Base for XR-2

![Arduino base for XR-2](arduino_base_xr2.png)

![Blender .blend](arduino_base.blend), ![.stl](arduino_base_xr2.stl), [YouTube video](https://www.youtube.com/watch?v=4HOXKobwqGA)

For the XR-2's arduino base, you should replace six socket caps (hex bolts) with longer ones. Bolt Depot part number 22746 stainless steel 18-8 black oxide finish, #6-32 x 1/2" socket caps work well.

### Arduino Base for SCARA Arm
![Arduino base for SCARA Arm](arduino_base_scara.png)

![Blender .blend](arduino_base.blend), ![.stl](arduino_base_scara.stl), [YouTube video](https://www.youtube.com/watch?v=ZgXrVDasyXI)

The geometry of the SCARA Arm's base required printing with 100% infill and tree supports.

### Arduino Base for XR-4

![Arduino base for XR-4](arduino_base_xr4.png)

![Blender .blend](arduino_base.blend), ![.stl](arduino_base_xr4.stl)

For the XR-4's arduino base, you should replace five socket caps (hex bolts) with longer ones.
For the top left socket cap, you can use a Bolt Depot part number 22746 stainless steel 18-8 black oxide finish, #6-32 x 1/2" socket cap.
For the other four, you can use Bolt Depot part number 22757 stainless steel 18-8 black oxide finish, #10-24 x 5/8" socket caps.

### Arduino MegaMotor6 Arches

![Arduino MM6 arches](arduino_mm6_arches.png)

![Blender .blend](arduino_mm6_arches_and_plug.blend), ![arches .stl](arduino_mm6_arches.stl), [YouTube video](https://www.youtube.com/watch?v=22EeDbbwtAY)

Each arch (together with a plug from below) holds the motor ribbon cables into their sockets and provides a channel to route the ribbon cable to the back of the board. Print three for each MM6 PCB. No fasteners required.

### Arduino MM6 Plug for XR-1

![Arduino MM6 plug for XR-1](arduino_mm6_plug_xr1.png)

![Blender .blend](arduino_mm6_arches_and_plug.blend), ![plug .stl](arduino_mm6_plug_xr1.stl)

This plug is sized for the shorter ribbon cable plugs on the XR-1. Print three for each MM6 PCB. No fasteners required.

### Arduino MM6 Plug for XR-1, XR-4, and SCARA

![Arduino MM6 plug not XR-1](arduino_mm6_plug_not_xr1.png)

![Blender .blend](arduino_mm6_arches_and_plug.blend), ![plug .stl](arduino_mm6_plug_not_xr1.stl)

This plug is sized for the longer ribbon cable plugs on models after the XR-1. Print three for each MM6 PCB. No fasteners required.

## Software 

See [Rhino Arduino MM6](https://github.com/petermcd1010/rhino_arduino_mm6) for the robot control software running on the arduino.

Have fun!

