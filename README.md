# Miner Simulator

A 2D mining game built with **Godot 4** that doubles as an interactive
demonstration of two classic CPU scheduling algorithms used to process mined
ore:

- **First-Come, First-Served (FCFS)** — ore is processed in the order it arrives
- **Non-preemptive Priority Scheduling** — higher-priority ore jumps the queue

Mine ore, upgrade your equipment, and watch the warehouse process your haul
through the scheduling queue.

## Get the game

| File | What it is |
|---|---|
| `OS_GAME_FINAL.console.exe` | Prebuilt executable (console export) |
| `Final_source.zip` | The complete Godot project source |

To run from source: extract `Final_source.zip`, open its `project.godot` in
Godot 4.4 or newer, and press F5.

## Controls

| Input | Action |
|---|---|
| `W` `A` `S` `D` / arrow keys | move |
| `Space` | attack / mine |

## What it demonstrates

The warehouse keeps an ore processing queue. **FCFS** processes ore in the
order it was mined, while **non-preemptive priority scheduling** sorts the
queue by ore rarity (legend → epic → rare → common) before each run — so you
can watch the difference in waiting time and throughput instead of just
reading about it.

---

*Built as an educational project. Source and game assets are bundled in
`Final_source.zip`.*
