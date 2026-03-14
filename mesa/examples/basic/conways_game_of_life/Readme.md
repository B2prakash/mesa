# Conway's Game Of "Life"

## Summary

[The Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), also known simply as "Life", is a cellular automaton devised by the British mathematician John Horton Conway in 1970.

The "game" is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input by a human. One interacts with the Game of "Life" by creating an initial configuration and observing how it evolves, or, for advanced "players", by creating patterns with particular properties.


## Installation

Make sure Mesa is installed with visualization support:

```bash
pip install mesa[rec]
```

## How to Run

Navigate to this directory and run the interactive visualization:

```bash
cd mesa/examples/basic/conways_game_of_life
solara run app.py
```

Then open your browser to the URL shown in the terminal (typically `http://localhost:8765`).

## Files

* ``agents.py``: Defines the behavior of an individual cell, which can be in two states: DEAD or ALIVE.
* ``model.py``: Defines the model itself, initialized with a random configuration of alive and dead cells.
* ``app.py``: Defines an interactive visualization using solara.
* ``st_app.py``: Defines an interactive visualization using Streamlit.

## Optional: Streamlit Visualization

An alternative Streamlit-based visualization is also available. Install Streamlit first:

```bash
pip install streamlit
```

Then run:

```bash
streamlit run st_app.py
```


## Further Reading
[Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
