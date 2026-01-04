# 3D Interactive Jewellery Display – CEVI Assessment

## Overview
This project is a 3D interactive jewellery showcase built using the A-Frame framework.
It simulates a luxury "jewellery box" experience where users can inspect individual rings.

## Features
- Three distinct ring models displayed inside a jewellery box layout
- Physically-inspired lighting for metallic realism
- Click-to-focus interaction with smooth animation
- Drag-to-rotate interaction (Y-axis only)
- State-managed interaction preventing multiple selections
- Close button to restore original layout

## Tech Stack
- A-Frame (Entity Component System)
- HTML / JavaScript
- GLB 3D models

## Interaction Logic
- Custom ECS components handle focus, drag rotation, and state management
- Original position, scale, and rotation are stored and restored accurately
- No third-party interaction libraries were used

## Controls
- Click a ring to focus
- Drag mouse / touch to rotate the ring
- Click CLOSE to return to the jewellery box view

## Live Demo
👉 [Live Demo Link Here]

## Author
Shahida Riyaz Karnul