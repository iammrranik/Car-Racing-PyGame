# 🚗 Car Racing Game (Python Midterm Project)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,25:FF7F00,50:FFFF00,75:00FF00,100:0000FF&height=200&section=header&text=Car%20Racing%20PyGame&fontSize=40&fontColor=ffffff&animation=fadeIn"/>
</p>

<p align="center"> <a href="https://github.com/iammrranik"> <img src="https://img.shields.io/badge/_Click_Here_to_Explore_My_GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white"/> </a> </p>


---


## ✨ Status
🚧 **Completed**  
🧠 Built with Python 3.14.3  
🎮 Uses [pygame-ce](https://github.com/pygame-community/pygame-ce)  
🎯 Designed for Midterm Evaluation  

---


## 🎮 Game Overview

This is a classic car racing game built for a Python midterm project. The player controls a car, avoids obstacles, and tries to achieve the highest score possible. The game features modular code, a clean UI, and persistent high scores.

---

## 🔥 Features

- 🧩 Clean & Modular Code (OOP, separate modules for entities, utils, settings)
- ⚡ Optimized Performance (uses efficient game loop and asset loading)
- 🖥️ User-Friendly Interface (simple controls, clear visuals)
- 📊 High Score Tracking (CSV-based, persistent)
- 🎵 Sound & Graphics (custom assets, background music, icons)
- 📁 Well-Structured Project Architecture

---


## 📌 Tech Stack

- Python 3.14.3
- pygame-ce
- Git & GitHub
- VS Code
---


## 🗂️ Project Structure

```
├── Main.py
├── Game.py
├── Settings.py
├── Utils.py
├── requirements.txt
├── README.md
├── Entities/
│   ├── Car.py
│   ├── CarObstacle.py
│   └── CarPlayer.py
├── Db/
│   ├── FileLoader.py
│   ├── Paths.py
│   └── Hiscore.csv
├── Assets/
│   ├── Background/
│   │   ├── Image/
│   │   │   ├── bg_game_over.png
│   │   │   ├── bg_hiscore.png
│   │   │   └── bg_home.png
│   │   └── Sound/
│   │       ├── beep.ogg
│   │       ├── charmer.mp3
│   │       └── explosion.wav
│   ├── CarModels/
│   │   ├── bike.png
│   │   ├── bike2.png
│   │   ├── bmw.png
│   │   ├── bmw2.png
│   │   ├── bmw3.png
│   │   ├── camaro.png
│   │   ├── camaro2.png
│   │   ├── challenger2.png
│   │   ├── challenger3.png
│   │   ├── convertible.png
│   │   ├── dumptruck.png
│   │   ├── figo.png
│   │   ├── figo2.png
│   │   ├── gwagon.png
│   │   ├── gwagon2.png
│   │   ├── lambo.png
│   │   ├── lambo2.png
│   │   ├── lancer.png
│   │   ├── lancer2.png
│   │   ├── landcruiser.png
│   │   ├── landcruiser2.png
│   │   ├── landcruiser3.png
│   │   ├── lexus.png
│   │   ├── lexus2.png
│   │   ├── lexus3.png
│   │   ├── mini.png
│   │   ├── mustang2.png
│   │   ├── mustang3.png
│   │   ├── patrol.png
│   │   ├── patrol2.png
│   │   ├── pickup.png
│   │   ├── pickup2.png
│   │   ├── pickup3.png
│   │   ├── porsche.png
│   │   ├── raptor.png
│   │   ├── raptor2.png
│   │   ├── sunny.png
│   │   ├── suv.png
│   │   ├── suv2.png
│   │   ├── taxi.png
│   │   ├── taxi2.png
│   │   ├── tida.png
│   │   ├── tida2.png
│   │   ├── tida3.png
│   │   ├── tow_truck.png
│   │   ├── tow_truck2.png
│   │   ├── tow_truck3.png
│   │   ├── truck2.png
│   │   ├── truck3.png
│   │   ├── van.png
│   │   ├── van2.png
│   │   ├── van3.png
│   │   ├── wrangler.png
│   │   ├── wrangler2.png
│   │   ├── wrangler3.png
│   │   └── wrangler4.png
│   ├── Icon/
│   │   └── icon.ico
│   ├── Road/
│   │   └── road1.png
└───|
```

---

## 🚦 How to Run

1. Install Python 3.14.3 and [pygame-ce](https://github.com/pygame-community/pygame-ce)
2. Clone this repository
3. pip install -r requirements.txt
3. Run `Main.py`:
  ```bash
  python Main.py
  ```

---

## 📝 Design

The game is designed using object-oriented principles:

- **Game loop**: Managed in `Game.py`, handles events, updates, and rendering.
- **Entities**: Player and obstacle cars are separate classes in `Entities/`.
- **Settings**: All constants and configuration in `Settings.py`.
- **Utils**: High score management, randomization, and display helpers.
- **Assets**: Images and sounds are loaded dynamically from the `Assets/` folder.
- **Persistence**: High scores are saved in a CSV file for replayability.

---

## 📦 Requirements

- Python 3.14.3
- pygame-ce

Install dependencies:
```bash
Python 3.x (x>10)
pip install pygame-ce
```

---

## 🙏 Credits

Developed by [iammrranik](https://github.com/iammrranik) for a Python midterm project.

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0000,20:FF7F00,40:FFFF00,60:00FF00,80:0000FF,100:8B00FF&height=4" width="80%"/> </p>
