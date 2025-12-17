🐍 Snake Game in C (Raylib)

A fully-featured Snake Game written in C using the Raylib graphics library, featuring difficulty levels, power-ups, obstacles, sound effects, and a persistent leaderboard.

🚀 Features
- 🎮 Classic Snake gameplay
- 🧠 Difficulty selection (Easy / Medium / Hard)
- 🍎 Normal food, bonus fruit & power (slow-motion) fruit
- 🧱 Random obstacles (walls)
- 🐌 Temporary slow-motion power-up
- 🔊 Sound effects (eat, hit, bonus)
- 🏆 Persistent leaderboard (file-based)
- 👤 Player name input
- 🎨 Clean UI with HUD and live leaderboard panel

🛠️ Technologies Used
- Language: C
- Graphics & Audio: Raylib
- Data Structures
- File Handling

📁 Project Structure

src/
 ├── main.c      # Main game loop, UI, scoring, leaderboard
 ├── snake.c     # Snake movement & collision logic
 └── snake.h     # Snake data structures
sounds/
 ├── eat.wav
 ├── hit.wav
 └── bonus.wav
leaderboard.txt
