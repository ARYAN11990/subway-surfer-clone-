# 🏃‍♂️ Subway Rush (Subway Surfers Clone)

A lightweight, browser-based 3D endless runner game inspired by Subway Surfers. Built entirely from scratch using **HTML5 Canvas, CSS, and Vanilla JavaScript**—no external game engines or libraries were used!

<img width="1920" height="1080" alt="Screenshot (1804)" src="https://github.com/user-attachments/assets/4ac1ce07-c246-4fc4-a207-b10c9ea46b97" />
<img width="1920" height="1080" alt="Screenshot (1806)" src="https://github.com/user-attachments/assets/df91c941-8d8a-4a20-a4fd-716aea22ed29" />
<img width="1920" height="1080" alt="Screenshot (1805)" src="https://github.com/user-attachments/assets/60688515-a9a3-432a-8ef8-926ad5a03476" />
<img width="1920" height="1080" alt="Screenshot (1807)" src="https://github.com/user-attachments/assets/40a41bd5-bf9d-4f02-a934-2928e47a502b" />



## ✨ Features

* **Custom Pseudo-3D Engine:** Features a scratch-built 3D math and projection system (`Vector3`, `Camera`) to render the game world dynamically.
* **Responsive & Cross-Platform:** Playable on both desktop and mobile devices.
* **Dynamic Generation:** Procedurally generated tracks, trains, barriers, and overhead obstacles that increase in difficulty as you progress.
* **Smooth Animations:** Includes player running, jumping, and sliding animations, along with spinning collectibles.
* **Particle Effects:** Custom particle system for coin collection and game-over impact[cite: 1].
* **Score Tracking:** Tracks distance, coins collected, and saves your High Score locally in the browser (`localStorage`)[cite: 1].

## 🎮 How to Play

### Controls
**Desktop:**
* `Left Arrow` / `A` : Move Left[cite: 1]
* `Right Arrow` / `D` : Move Right[cite: 1]
* `Up Arrow` / `W` / `Space` : Jump[cite: 1]
* `Down Arrow` / `S` : Slide/Roll[cite: 1]
* `Esc` / `P` : Pause Game[cite: 1]

**Mobile/Touch:**
* `Swipe Left/Right` : Change lanes[cite: 1]
* `Swipe Up` : Jump[cite: 1]
* `Swipe Down` : Slide[cite: 1]
* `Tap` : Quick Jump[cite: 1]


## 🚀 Installation & Running

Since the entire game is contained within a single file[cite: 1], there is no complex setup required:

1. Clone the repository:
```bash
   git clone [https://github.com/yourusername/subway-rush-clone.git](https://github.com/yourusername/subway-rush-clone.git)

2. Navigate to the project directory.

3. Simply open index.html in any modern web browser to start playing!
```


## 🛠️ Technical Architecture

*The game is structured into several modular JavaScript classes within the main file[cite: 1]:

*Renderer & Camera: Handles HTML5 Canvas 2D context and projects 3D coordinates (x, y, z) into 2D screen space (x, y, scale)[cite: 1].

*Player: Manages lane switching, jumping physics, sliding states, and 3D limb rendering[cite: 1].

*TrackSystem: Infinitely generates the environment, including grounds, rails, walls, and decorative buildings[cite: 1].

*ObstacleManager & CoinManager: Spawns and recycles barriers, moving trains, and coins based on distance traveled, utilizing AABB collision detection[cite: 1].

*InputHandler: Normalizes keyboard and touch/swipe inputs for seamless gameplay across devices[cite: 1].

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check issues page if you want to contribute.

## 📝 License
This project is open-source and available under the MIT License.

## 👨‍💻 Author

Aryan Parmar

If you like this project, consider giving it a ⭐ on GitHub.


