# Genetic Programming 
<p  align="center">
    <img src="https://github.com/blackvitriol/github/blob/master/images/GA.png?raw=true"/>
</p>

*Welcome !* This repository contains work related to programming using [Genetic](https://en.wikipedia.org/wiki/Genetic_programming) and Evolutionary Strategies.  Check it out if you are new to this concept.

---

Need info? Check the [Wiki (GP)](https://en.wikipedia.org/wiki/Genetic_programming) | or [Create an issue](https://github.com/blackvitriol/Genetic_Programming/issues/new) | [Ask me on Twitter](https://twitter.com/ahmadovich_)

[![OSS](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

---

## Table of Contents

- [Getting Started](https://github.com/blackvitriol/Genetic_Programming#getting-started)
  - [Introduction](https://github.com/blackvitriol/Genetic_Programming#introduction)
- [Working](https://github.com/blackvitriol/Genetic_Programming#working)
  - [Terminal](https://github.com/blackvitriol/Genetic_Programming#terminal)
- [Requirements](https://github.com/blackvitriol/Genetic_Programming#requirements)
- [License](https://github.com/blackvitriol/Genetic_Programming#license)
- [Credits](https://github.com/blackvitriol/Genetic_Programming#credits)

## Getting Started




### Introduction



code:

```groovy
blah bla blah
```

## Working

- Generate an initial, stochastic population.
- Iteratively perform selection, genetic operation, and evaluation:
    - Evaluate each program (hypothesis) in the current population against the given dataset and determine how well it performed, the value recorded as a fitness score.
    - Randomly select programs and compare their fitness scores.
    - Apply one of three genetic operators to a copy of the leading program: reproduction; mutation; crossover… then move the program into the subsequent generation.
    - Evaluate all programs (hypotheses) in each new generation.
- Repeat until the user-defined termination criteria are met.

### Hello World Terminal:
This is a tree based genetic algorithm that accepts a string from a user. This string is parsed and a fitness goal is defined for evaluation. The initial population is defined as all ASCII characters including numbers, alphabets and symbols in a sequential manner. The program then performs genetic operations on the first generation, with the fitness score as its function. After several evolutions of the generations, where the strings with the highest fitness are allowed to exist, the program converges on a generation that resembles the goal.

<p  align="center">
    <img src="https://github.com/blackvitriol/github/blob/master/images/HW.gif"/>
</p>

## Requirements


## License
This project is made available under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

## Credits

*We're open to suggestions, feel free to message me or open an issue.*
*Pull requests are also welcome!*

This project is powered by:

<a href="https://github.com/TASVideos/BizHawk">
    <img src="http://adelikat.tasvideos.org/corphawk_logo.jpg" width="40" height="40">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/Lua-logo-nolabel.svg/1200px-Lua-logo-nolabel.svg.png" width="40" height="40">
    <img src="https://www.python.org/static/opengraph-icon-200x200.png" width="40" height="40">
 <img src="http://johfrael.nl/wiki/images/1/12/Ubuntu_16.04_Logo.jpg" width="140" height="40">   
</a>
