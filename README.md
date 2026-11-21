# Titan ROV – Thruster Directions

Interactive page that shows how every thruster of the Titan ROV moves for any joystick input:
whether each motor pushes or pulls water, the value sent to the Arduino, and the resulting motion.

The math is the same as `mix_thrusters()` in the laptop Python code (BlueROV2-style vectored frame:
4 horizontal thrusters at 45° + 2 vertical).

## Deploy on Vercel

Import this repo in Vercel, choose **Framework: Other**, leave the build command empty, and deploy.
It is a single static `index.html`, so nothing needs to be installed or built.

## Run locally

Open `index.html` in any browser.
