### Math Notebooks
When learning about new mathematical concepts, I find it helpful for pedagogical
reasons to implement them in a Python notebook to check my understanding and get a more intuitive understanding of what is going on. I've started organizing them
in this repo for my own reference and to share in case they are helpful to others.

So far most of the notebooks are related to solving ode systems using numerical methods, but there's also a few other random things thrown in there.

## Clone and Run via UV
You can clone this repository and run the notebooks using [UV](https://docs.astral.sh/uv/):

```bash
git clone https://github.com/wbrannock/mathnotebooks.git
cd mathnotebooks
python pip install uv (if you don't have it already)
uv sync
```
## Ideas for future notebooks
- Numerical integration methods (Midpoint, Trapezoid, Simpson's, Monte Carlo)
- optimization algorithms (gradient descent, Newton's method)
- cellular automata (Conway's Game of Life, Wolfram's 1D automata)
- fractals (Mandelbrot, Julia sets)