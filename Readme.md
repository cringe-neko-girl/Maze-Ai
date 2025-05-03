# Maze Ai

A real-time terminal bot that watches a file-based maze (`maze.txt`) and moves step-by-step toward a goal using **Breadth-First Search (BFS)**.

## How It Works

1. Place your maze in a file named `maze.txt`.
2. The bot (`x`) will look for the nearest goal (`:` or `T`) and move toward it one step at a time.
3. Walls (`o`, `|`, `-`) are considered impassable.
4. The path taken is marked with `#` as a trail.
5. The program runs indefinitely and adapts to live updates.

## Maze Symbols

| Symbol | Meaning          |
|--------|------------------|
| `x`    | Bot         |
| `:`/`T`| Target/goal      |
| 'o' '-' | Walls/barriers |
| (space) | Empty path     |
| `#`    | Bot trail        |

---

## Sample Maze

Here's a basic sample of how your maze could look in `maze.txt`:

```txt
+---+---+---+---+---+
|    | :  |     :      
------   ------      
:
--------------  -----
    :                 
---  -------------   
x                                         
```
