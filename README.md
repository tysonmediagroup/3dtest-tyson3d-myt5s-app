<p align="center">
  <a href="https://tysonmediagroup.org">
    <img src="https://raw.githubusercontent.com/TYSONMediaGroup/tysonmediagroup.org.myt5s.app/main/assets/LOGOSFORGEMINI/TYSONMediaGroupBanner.png" alt="TYSON Media Group" width="700">
  </a>
</p>

<h1 align="center">TYSON 3D Open World</h1>

<p align="center">
  <a href="https://threejs.org"><img src="https://img.shields.io/badge/Three.js-WebGL-black?logo=threedotjs&logoColor=white" alt="Three.js"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API"><img src="https://img.shields.io/badge/Audio-Web%20Audio%20DSP-blue" alt="Web Audio DSP"></a>
  <a href="https://myt5s.app"><img src="https://img.shields.io/badge/App-myT5S.app-007ACC" alt="myT5S.app"></a>
  <a href="https://tysonmediagroup.org"><img src="https://img.shields.io/badge/TYSON-Media%20Group-007ACC" alt="TYSON Media Group"></a>
</p>

Full 3D open world environment featuring an animated 3D stickman, interactive town, and a drivable sports car with synthesized engine audio.

<p align="center">
  <img src="t5s-project-background.png" alt="T5S Project Background" width="700">
</p>

---

## Features

- **Procedural 3D Stickman**:
  - Full body model with head, expressive eyes, torso, arms, and legs.
  - Procedural walk, sprint, jump, and idle breathing animations.
  - Dynamic contact shadow.
- **Drivable 3D Sports Car**:
  - Sporty red aerodynamic body, tinted glass cabin, and rear spoiler.
  - 4 detailed wheels that spin realistically; front wheels steer with turning angle.
  - Realistic arcade physics: acceleration, braking, reverse, and drifting with handbrake.
  - Dynamic engine sound synthesized via Web Audio API.
  - Vehicle entry and exit mechanics (`[E]` key).
- **3D Town Environment**:
  - Sky with atmospheric fog and directional sun casting real-time soft shadows.
  - Circular asphalt track with center road markings.
  - Low-poly pine and deciduous trees.
  - Modern multi-story colorful town buildings.
  - Stunt jump ramps for launching the car.
- **Dynamic Camera System**:
  - On Foot: Smooth orbital third-person follow camera (mouse drag to rotate).
  - In Car: High-speed dynamic chase camera with distance scaling and speedometer.

---

## Controls

### On Foot (Stickman)
- `W` / `A` / `S` / `D` or `Arrow Keys`: Walk and turn
- `Shift`: Sprint
- `Space`: Jump
- `E`: Enter Car (when standing near it)
- `Mouse Drag`: Orbit camera view

### In Car (Driving)
- `W` / `Up Arrow`: Accelerate
- `S` / `Down Arrow`: Brake / Reverse
- `A` / `Left Arrow`: Steer Left
- `D` / `Right Arrow`: Steer Right
- `Space`: Handbrake / Drift
- `E`: Exit Car
