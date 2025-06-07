# Waterdrop Life Simulator

**Waterdrop Life Sim** is a browser-based artificial life simulation where simple organisms evolve using Hebbian learning and neural networks. It models an environment where organisms forage for food, communicate through signaling, and reproduce based on fitness. The system uses a stabilized Hebbian learning mechanism and includes memory and vector retrieval for behavior development.

---

## 🌱 Features

- **Organisms with Neural Networks**
  - 3-layer architecture (input, two hidden layers, output).
  - Uses Hebbian learning to adjust internal weights during simulation.
  - Learns from short-term memory and retrieved vector memories.
  - Communicates using simple signal sequences.

- **Breeding & Evolution**
  - Organisms die if they run out of energy.
  - Top-performing organisms are added to a breeding pool.
  - When population drops, offspring are generated via crossover and mutation.

- **Simulation Environment**
  - 400x400 canvas where organisms move and sense.
  - Food items are randomly spawned and consumed.
  - Organisms may mark food to reserve it temporarily.

- **Visual Interface**
  - Real-time organism count, food count, age tracking, and leaderboard.
  - Adjustable food density slider.
  - Live display of organisms' signal output and energy.
  - Leaderboard tracking best organisms by fitness and age.

---

## 📦 Files

- `waterdrop-life-sim.html` — All-in-one HTML file containing the simulation and code.

---

## 🧠 Learning & Memory Model

Organisms:
- Use neural networks with customizable hidden layer sizes.
- Employ a Hebbian learning control signal to selectively trigger internal learning.
- Store short-term memory vectors that can later be retrieved using cosine similarity.
- Learn to balance signaling, energy usage, and foraging strategies.

---

## ⚙️ Usage

1. Open `waterdrop-life-sim.html` in a modern web browser (Chrome or Firefox recommended).
2. Click the **Start/Stop** button to begin or pause the simulation.
3. Adjust **Food Density** with the slider to affect environmental resource availability.
4. Observe how organisms evolve over time via leaderboard stats and visual behaviors.

---

## 📈 Fitness Function

Fitness is calculated based on:
- Age (survival time)
- Total energy accumulated
- Number of food collisions
- Penalty for wall injuries (collisions)

---

## 🧪 Notes

- Organisms are color-coded blue.
- Food is green by default and turns red when marked.
- Signal sequences are shown as colored bars above organisms:
  - Yellow = signal `1`
  - Red = signal `-1`
  - Black = signal `0`
- Hebbian learning activation is indicated by a red or white block next to each organism.

---

## 🪪 License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). 
You are free to share, modify, and adapt the simulator as long as you give appropriate credit.

---

## ✍️ Author & Credits

Designed by an experimental artificial life enthusiast.

Inspired by:
- Hebbian learning principles
- Neuroevolution simulations
- Vector-based memory retrieval

---

## 🛠️ Tech Stack

- Pure JavaScript (no external libraries)
- HTML5 Canvas
- Responsive grid layout for UI

---

## 💡 Future Ideas

- Add persistent memory evolution.
- Enable external vector training via user input.
- Visualize neural activations over time.

---

## 📸 Screenshot


![image](https://github.com/user-attachments/assets/7a497f66-e6c2-498f-a94f-d92f0b02d44c)

---

