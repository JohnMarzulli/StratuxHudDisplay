# Stratux HUD Display

A simple, DIY, Head Up Display for StratuxHUD.

## Summary

This project aims to develop a display for the StratuxHUD. This is born out of a lack of consistently available projectors.

The project includes the 3D printer geometry, bill of materials, and assembly instructions.

## Bill of Materials

What you will need to complete this project:

- [Raspberry Pi 4](https://www.amazon.com/Raspberry-Pi-RPI4-MODBP-4GB-Model-4GB/dp/B09TTNF8BT?ref_=ast_sto_dp)
- [USB, mechanical keypad](https://www.amazon.com/Mechanical-Numeric-Backlit-Desktop-Computer/dp/B07FFLNF5C?ref_=ast_sto_dp)
- Printed housing. (ABS, PETG, or High Temp PLA)
- [6" x 6" 50/50, 3mm thick teleprompter glass](https://telepromptermirror.com/sample/)
- USB A to C or C to C cable
- USB A to Micro B cable
- [HMTECH 7" LCD Screen](https://www.amazon.com/HMTECH-Raspberry-Pi-Monitor-Non-Touch/dp/B09MFNLRQQ?th=1)
- Micro HDMI to HDMI cable

## Printing the Case

You may print the case at any infill from 10% to 100%. Gyroid is the suggested infill type. You will need to enable supports for the main case due to the cable outlet.

Do not enable supports for the lens holder.

The lens holder is designed at different hights to help fit your plane's dashboard. They simply slot into place. When you are comfortable with your choice, gluing the holder onto the main case is recommended.

### Materials

Due to the HUD being in a cockpit, and potentially subjected to the sun for long periods, take care with the printed material.

ABS will have the best UV and heat resistance. PETG may also be suitable. High Temp PLA may work, but has not be tested for this application.

## Assembly

The assemble:

1. Verify a Stratux HUD micro-SD card is inserted into the Pi.
1. Verify the Pi has heat sinks.
1. Attach the HDMI cable to the R-Pi.
1. Attach the USB-C cable to the PI for power.
1. Attach the A end pf the A to B-Micro into one of the blue USB ports of the Pi.
1. Place the Pi with the cables into the main case. The C and HDMI ports will face towards the lens holder attachment sliders.
1. Route the Pi's power cable out of the trapezoidal opening.
1. Pass the USB-A plug from the keypad into the case through the trapezoidal opening. Plug it into any remaining USB port of the Pi.
1. Route the USB-B micro and full sized HDMI ends out of the case through the trapezoidal opening. Wrap and tidy the remaining cable length over top of the PI.
1. Place the LCD screen over top the Pi and the cables. The HDMI and USB micro port will be accessible through the trapezoidal opening.
1. Plug the USB-B micro cable and HDMI cable into the LCD screen.
1. Slide the printed glass-holder onto the main case from the top.
1. Slide the teleprompter glass into the holder. Be aware that you want to check the rotation of the glass. One side will produce a second "ghost" image when reflecting and one side will produce the desired result.

Your HUD display is now ready for mounting. Double sided tape or velcro work well on the dashboard.
