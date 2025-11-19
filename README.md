🔥Interactive Wildfire Simulation — p5.js + ml5.js + micro:bit + Flask

This project is an interactive wildfire simulation game built using p5.js, ml5.js, micro:bit hardware, and a lightweight Flask backend.
Players interact with dynamic fire behavior using voice commands, blowing into a mic, and micro:bit touch sensors—creating a multimodal, playful demonstration of AI + hardware + real-time simulation.

🎮 Features

 Wildfire Simulation

      Fires appear in small, medium, and large sizes.

      Fires grow, spread, burn out, or turn to scorched earth.

      Player movement affects nearby fires.

Extinguishing Mechanics

      Interact in multiple ways:

      micro:bit P0 → small water spray

      micro:bit P1 → larger spray

      P0 + P1 → heavy water

      Microphone blowing → wind gusts that push fires or clear smoke

      Speech Recognition (ml5.js) → say “up”, “down”, “left”, “right” to move your player

Environmental Effects

      Smoke clouds (💨) appear over large fires.

      Blowing toward smoke will clear it.

      Droplets, wind puffs, and fire particles animate the scene.

Frontend

      p5.js — Rendering, animation, game logic

      ml5.js (SpeechCommands18w) — Voice command classifier

      Web Serial API — Real-time micro:bit data reading

Backend

      Flask — Serves index.html and static assets

      Hardware

      micro:bit v1/v2

      Touch pins P0 & P1

      Microphone sound level
