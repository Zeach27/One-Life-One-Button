One life One Button Game

GitHub repository link
https://github.com/Zeach27/One-Life-One-Button.git


Project Reflection

What was your game idea?

The game is a simple but engaging one-button one life game called Pop Dart. The player’s objective is to pop balloons using a dart. The player can tap anywhere on the screen to launch a dart, but the challenge lies in timing: the balloon moves from left to right of the screen, and the dart can only hit if the balloon reaches a designated attack range in the center. Players must carefully watch the balloon’s movement and tap at the precise moment to succeed.

The gameplay emphasizes timing and precision, making it easy to learn but hard to master. Each balloon score the speed increase, creating natural difficulty progression.

To make the experience more engaging, I included visual and auditory feedback when a balloon is successfully popped, giving the player instant reward and satisfaction. Procedural scaling can increase difficulty over time, introducing faster or multiple balloons, making reflexes and prediction key to achieving high scores. The game is designed for short, fun sessions, perfect for mobile play, while still offering enough challenge to keep players coming back.


What was the most difficult part to implement?

The most challenging part was building the core game logic and functions, especially handling the actions of the game. In Pop Dart, the player must tap at the exact moment when the balloon reaches the attack range, so when the dart hit the ballonit should pop and has an effect of pop and the timing of the pop sound. 

Another difficult aspect was synchronizing the music with gameplay. Each pop needed to line up with sound effects and visual effects, so that the player received immediate feedback when a balloon was successfully hit. This required careful coordination between the game state, the animation, and audio triggers.

What would you improve with more time?

With more time, I would focus on enhancing the UI and adding gameplay twists to make Pop Dart more engaging and visually appealing. For the UI, I’d design a polished main menu, intuitive score displays, and animated overlays for combos or streaks, giving players clear feedback and making the game feel more professional.  I would also implement something that will save the data, so that high scores, progress, and other game states are preserved even when the player exits the game. This ensures that players can return later without losing their best score or achievements, increasing engagement.

---

## Run this project

1. Install dependencies

```bash
npm install
```

2. Start the app

```bash
npx expo start
```

3. Open on device/emulator via Expo instructions.

