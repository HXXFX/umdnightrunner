# https://hxxfx.github.io/umdnightrunner/

The training page for UMD - Ultimate Machine Deathmatch. It trains the game's AI brain inside your browser, on the computer that opens it.

## How to use it

1. Open https://hxxfx.github.io/umdnightrunner/ in Chrome or Edge.
2. **Step 1**: tonight's training is already picked, marked **Tonight**.
3. **Step 2**: wait for the checks to turn green, then click **Check speed**. It says how long the training will take.
4. **Step 3**: click **Start training** and leave the tab open, in front. If it closes, open the page again and click **Carry on**.
5. **Step 4**: each file is saved to your Downloads folder as soon as it is made. If Chrome asks to download multiple files, click
   **Allow**.

Nothing is sent anywhere: the page runs on the computer that opens it, and what it makes are downloads. It trains on the
computer's graphics card when the browser can use one, and on all of its processor threads but one otherwise.

## Tonight

No training is set for tonight.

## The trainings on this build

- **The brain, from stock** - Trains the AI brain, starting from the stock rules. Whole fights against the stock brain, a dice fighter and itself.
- **The sensors alone, onto the game's brain** - Trains only the sensors, on top of the brain the game ships.
- **A quick try (a few minutes)** - A few minutes, to see that this computer can train. Not a brain for the game.

## This build

Built from the game at commit ac1ec1e (2026-09-29). Every file the page gives carries that commit.

## Third-party notice

The robot part shapes in the page are derived from the link meshes of [unitree_ros](https://github.com/unitreerobotics/unitree_ros),
used under the BSD 3-Clause licence: see [LICENSE-unitree_ros.txt](LICENSE-unitree_ros.txt). This project is not affiliated with, nor
endorsed by, Unitree Robotics.
