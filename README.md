# Snake Game 🐍

A simple Snake Game built using Python and Tkinter. Control the snake with arrow keys, eat food to grow, and avoid hitting the walls or yourself.

## Features

* Arrow key controls
* Random food generation
* Score tracking
* Game over detection

## Run the Game

```bash id="dfg4k1"
python snake.py
```

## Controls

* ↑ : Up
* ↓ : Down
* ← : Left
* → : Right

## Note

For better controls, replace:

```python id="i1u3xk"
window.bind("<KeyRelease>", change_direction)
```

with:

```python id="r1k8zp"
window.bind("<KeyPress>", change_direction)
```
