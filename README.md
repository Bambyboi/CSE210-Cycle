# CSE210-Cycle

### Cycle is played according to the following rules.

- Players can move up, down, left and right...
- Player one moves using the W, S, A and D keys.
- Player two moves using the I, K, J and L keys.
- Each player's trail grows as they move.
- Players try to maneuver so the opponent collides with their trail.
- If a player collides with their opponent's trail...
    - A "game over" message is displayed in the middle of the screen.
    - The cycles turn white.
    - Players keep moving and turning but don't run into each other.

## Author
- Samuel
- Alvaro
- Martin
- Gunnar

# Cycle
Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

![image](https://www.google.com/search?q=gems+and+rocks&rlz=1C1ASUM_enWS923WS923&sxsrf=APq-WBuIDApYFDTw1fW6CikIqDGf8QWPiQ:1645847334532&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjJruqNu5z2AhUOUGwGHeO5DusQ_AUoAXoECAEQAw&biw=1366&bih=568&dpr=1#imgrc=nylOM1XzPXS4nM)

## Getting Started

---

## Run the program using Visual studio code. Then open the greed folder and open the _main_.py file and click the run button and see the result.


## Project Structure

---

The project files are organized as follows:

```
+-- Cycle               (It holds all files)
  +-- game              (It holds files that is need to make the game run perfectly)
    +-- casting
      +-- __pycache__   (cache)
      +-- actor.py      (A visible, moving object that takes part in the game. Actor's will maintain track of its identity, location,
                         and speed in two-dimensional space.)
      +-- cast.py       (A gathering of actors, the duty of a cast is to keep on eye of a collection of actors. It does adding, 
                         removing and getting them by a group name.)
      +-- food.py       ()
      +-- score.py      ()
      +-- snake         ()
      +-- snake2        ()
    +-- directing
      +-- __pycache__   (cache)
      +-- director.py   (It receives directional input from the keyboard and implement it to the robot.)
    +-- scripting
      +-- __pycache__   (cache)
      +-- action.py
      +-- control_actors_action.py   ()
      +-- draw_actors_action.py      ()
      +-- handle_collision action.py ()
      +-- move_actors_action.py      ()
      +-- script  ()
    +-- services
      +-- __pycache__   (cache)
      +-- keyboard_service.py (The duty of a KeyboardService is to detect player repond on the keyboard and convert them into a 
                         point representing a direction.)
      +-- video_service.py (Outputs the game state. The duty of the class of objects is to draw the game state on the screen.)
    +-- shared
      +-- __pycache__   (cache)
      +-- color.py      (A color. The duty of Color is to hold and provide information about itself. Color has a few methods for comparing 
                         them and converting to a tuple.)
      +-- point.py      (A distance from a relative origin (0, 0). The responsibility of Point is to hold and provide information 
                         about itself. Point has a few convenience methods for adding, scaling, and comparing them.)
  +-- __main__.py     (The main use to gather all information and make them run together.)
+-- README.md         (general info)
```

## Required Technologies

---

- Python 3.8.0
