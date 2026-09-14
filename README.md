# AutoScan 3D — Car Diagnostic Simulator

An interactive browser-based OBD-II vehicle diagnostic simulation built with Three.js.

## Features

- Interactive 3D vehicle scene with orbit, zoom and clickable diagnostic hotspots
- High-quality GLB vehicle asset loaded from Khronos glTF Sample Assets
- Animated virtual OBD-II scanner connection and cable
- CAN handshake simulation
- Full ECU scan workflow
- Engine, transmission, ABS and BCM module states
- DTC results including P0302, P0171 and U0100
- Animated live telemetry for RPM, coolant temperature, battery voltage, throttle and fuel trim
- Responsive glassmorphism interface for desktop and mobile
- Graceful fallback vehicle if the remote GLB asset cannot load

## Tech

Three.js, WebGL, GLTFLoader, OrbitControls and static HTML/CSS/JavaScript.

## Disclaimer

This is an educational simulation. It does not communicate with a real vehicle or replace professional automotive diagnostic equipment.