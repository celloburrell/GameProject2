# Mini-Project 2 Report

## Responsibilities:

- Nick Murphy:
    - Wigets for main menu and game
    - Music and sound effects
    - Life counter
    - Enemy bullet fire
    - Actor materials
- Nick Burrell:
    - Character and enemy movement
    - Camera placement
    - Models for player and enemies

## Expected Grade Earned
- A
## Criteria:
- [x] D-1: The camera is placed so that the player can see the ship and the waves of enemies.
- [x] D-2: Correctly configured on the depot so that a new client provides a runnable game.
- [x] C-1: WASD, arrow keys, or gamepad controls move the ship appropriately.
- [x] C-2: Z, space, or gamepad controls fire a projectile.
- [x] C-3: Projectiles are removed when they are off-screen.
- [x] C-4: Projectiles damage enemies and are removed after striking them.
- [x] C-5: Collision with an enemy damages or destroys the player.
- [x] C-6: Enemies appear and move in a single direction.
- [x] C-7: Start with a title screen that, on input, transitions into the game.
- [x] C-8: Loop background music.
- [x] C-9: Play sounds upon firing and upon projectiles striking an enemy.
- [x] C-10: Runs without errors
- [x] C-11: All raw referenced assets are in the **ToImport** folder.
- [x] C-12: Demonstrated during the associated showcase day.
- [x] C-13: Complies with an http://www.esrb.org/ratings/ rating of M or lower.
- [x] C-14: All assets are in a folder named after the project [GUSG 2.2] https://github.com/Allar/ue4-style-guide#structure-top-level.
- [x] C-15: Report, in MD or HTML, is included in the depot, listing all contributors' names and responsibilities.
- [x] C-16: Report includes licensing information on all included third-party assets.
- [x] C-17: Report includes self-evaluation that states the grade earned along with a list of all criteria, marking those that are met.
- [x] B-1: Input controls are properly configured through the editor's Input settings.
- [x] B-2: Incorporate weapon cool-down that (a) allows the player to hold
         the attack button for periodic firing and/or (b) limits the rate of fire.
- [x] B-3: Enemy ships demonstrate more advanced behavior than single-direction movement,
          such as circular or periodic movement.
- [x] B-4: Enemies emit projectiles that damage the player on collision.
- [x] B-5: Compiles without warnings.
- [x] B-6: Assets and directories follow naming conventions [GUSG&nbsp;<a href="https://github.com/Allar/ue4-style-guide#anc">1</a>, <a href="https://github.com/Allar/ue4-style-guide#21-folder-names-">2.1</a>].
- [x] B-7: Variables and methods follow naming conventions [GUSG&nbsp;<a href="https://github.com/Allar/ue4-style-guide#321-naming-">3.2.1</a>, <a href="https://github.com/Allar/ue4-style-guide#321-naming-">3.3.1</a>].
- [x] B-8: Contains no assets not used in the build.
- [x] B-9: Commit messages follow established standards.
- [x] B-10: Uses timers and tasks appropriately rather than abusing the <code>Tick</code> event.
- [x] A-1: Player input is managed in a <code>PlayerController</code> subclass while 
         motion is handled in the <code>Pawn</code> subclass that is possessed by
         the <code>PlayerController</code>.
- [x] A-2: Correctly handle multiple simultaneous inputs (for example, the player
         does not move twice as fast when holding W and Up).
- [x] A-3: Enemy ship movement is controlled with an <code>AIPlayerController</code>.
- [x] A-4: Complies with an <a href="http://www.esrb.org/ratings/">ESRB rating</a> of &ldquo;T&rdquo; or lower.

## Licenses
Music from https://filmmusic.io
"Inspired" by Kevin MacLeod (https://incompetech.com)
License: CC BY (http://creativecommons.org/licenses/by/4.0/)

Sound from http://soundbible.com/1785-Skorpion.html
"Scorpion Sound" by Kibblesbob 
License: Public Domain

Sound from http://soundbible.com/682-Swoosh-1.html
"Swoosh 1 Sound" by man
License: Sampling Plus 1.0