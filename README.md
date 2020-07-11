# Conway's Game of Life

The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970.
It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.
One interacts with the Game of Life by creating an initial configuration and observing how it evolves.
It is Turing complete and can simulate a universal constructor or any other Turing machine.

### Conway’s game has very simple rules:

1.) underpopulation: any live cell with less than 2 live neighbors dies

2.) overcrowding: any live cell with more than 3 live neighbors dies

3.) Any live cell with exactly 2 or 3 live neighbors lives on	to the next generation

4.) Any dead cell with exactly 3 live neighbors becomes a live cell

The initial pattern constitutes the seed of the system.
The first generation is created by applying the above rules simultaneously to every cell in the seed; births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick. 
Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.

![Conway Gif](https://github.com/i-Rony/Conways-Life-Game-Sim/blob/master/conway.gif)


### What is the conclusion of Conway’s life game?

With so simple rules, quite complex structures and patterns can emerge and evolve
Many patterns in the Game of Life eventually become a combination of still lifes, oscillators, and spaceships; other patterns may be called chaotic.
A pattern may stay chaotic for a very long time until it eventually settles to such a combination.
The Game of Life is undecidable, which means that given an initial pattern and a later pattern, no algorithm exists that can tell whether the later pattern is ever going to appear.
This is a corollary of the halting problem: the problem of determining whether a given program will finish running or continue to run forever from an initial input.
Indeed, since the Game of Life includes a pattern that is equivalent to a universal Turing machine (UTM), this deciding algorithm, if it existed, could be used to solve the halting problem by taking the initial pattern as the one corresponding to a UTM plus an input, and the later pattern as the one corresponding to a halting state of the UTM.
It also follows that some patterns exist that remain chaotic forever. 
If this were not the case, one could progress the game sequentially until a non-chaotic pattern emerged, then compute whether a later pattern was going to appear.

