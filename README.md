# Titan ROV – Thruster Directions

Interactive 3D simulation (plus a 2D view) that shows how every thruster of the Titan ROV moves for any joystick input:
whether each motor pushes or pulls water, the value sent to the Arduino, and the resulting motion.

The math is the same as `mix_thrusters()` in the laptop Python code (BlueROV2-style vectored frame:
4 horizontal thrusters at 45° + 2 vertical).

## Deploy on Vercel

Import this repo in Vercel, choose **Framework: Other**, leave the build command empty, and deploy.
It is a single static `index.html`, so nothing needs to be installed or built.

## Run locally

Open `index.html` in any browser.

## Joystick

Plug a PS4 / Xbox controller into the computer and press any button: the page reads it with the browser
Gamepad API (left stick = forward/back + turn, right stick = up/down + slide sideways), same as the ROV.
