# Uber 3D Pickup – Mini Prototype

A tiny web page that mimics our team's product: a first-person 3D pickup-navigation view for the
"last 100 meters" of an Uber ride. Instead of a flat map pin, the rider sees the actual curb in 3D,
with a glowing path on the ground leading to the exact spot where the driver is waiting. That helps most
in confusing places like airports, garages, and campuses.

Built with plain HTML and [three.js](https://threejs.org/) (loaded from a CDN).

- **Live page:** https://gml10rice.github.io/mini-prototype/
- **Repo:** https://github.com/gml10rice/mini-prototype

## The button

Click **Start walking**. The camera walks you, in first person, from Door 4 of the terminal
along the blue path, past Zones A and B, to Zone C, where Jordan's black Camry is waiting. The banner at the
top gives turn-by-turn instructions and counts down the meters left. At the end you turn to face
the car. Click **Walk again** to replay it.

## Run locally

Open `index.html` in any browser. It has no build step. It needs an internet connection to load three.js.
