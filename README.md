# https://hxxfx.github.io/umdnightrunner/

The training page for UMD - Ultimate Machine Deathmatch. It trains the game's AI brain inside your browser, on the computer that opens it.

## How to use it

1. Open https://hxxfx.github.io/umdnightrunner/ in Chrome or Edge.
2. **Step 1**: tonight's training is already picked, marked **Tonight**.
3. **Step 2**: wait for the checks to turn green, then click **Check speed**. It says how long the training will take.
4. **Step 3**: click **Pick a folder** and choose where the files go. Training cannot start without one. To keep a copy in the
   cloud, pick a folder inside Google Drive, OneDrive or Dropbox.
5. **Step 4**: click **Start training** and leave the tab open, in front. If it closes, open the page again and click **Carry on**
   (Chrome asks once to allow the folder again).
6. **Step 5**: each file is saved into the folder as soon as it is made, in a folder of the training's own, with its progress and
   its log.

Nothing is sent anywhere: the page runs on the computer that opens it, and what it makes is written into the folder you picked. It
needs Chrome or Edge, which can save to a folder. It trains on the
computer's graphics card when the browser can use one, and on all of its processor threads but one otherwise.

## Tonight

**The brain, from stock, on the new moves (29 September)** - Trains the AI brain again, starting from the stock rules, on the fight as it is now: the new walk, kicks, grips and getting up. Whole fights against the stock brain, a dice fighter and itself.

## The trainings on this build

- **The brain, from stock** - Trains the AI brain, starting from the stock rules. Whole fights against the stock brain, a dice fighter and itself.
- **The sensors alone, onto the game's brain** - Trains only the sensors, on top of the brain the game ships.
- **A quick try (a few minutes)** - A few minutes, to see that this computer can train. Not a brain for the game.
- **The brain, from stock, on the new moves (29 September)** (tonight) - Trains the AI brain again, starting from the stock rules, on the fight as it is now: the new walk, kicks, grips and getting up. Whole fights against the stock brain, a dice fighter and itself.

## This build

Built from the game at commit 44916a1 (2026-10-01). Every file the page gives carries that commit.

## Third-party notice

The robot part shapes in the page are derived from the link meshes of [unitree_ros](https://github.com/unitreerobotics/unitree_ros),
used under the BSD 3-Clause licence: see [LICENSE-unitree_ros.txt](LICENSE-unitree_ros.txt). This project is not affiliated with, nor
endorsed by, Unitree Robotics.
