# < QopyCat | Schrödinger's Quantum Cats >
Quantum leap in teleportation: Schrödinger's cat is both alive and dead.
Womanium Quantum Hackathon 2022

<div>
  
  [![Status](https://img.shields.io/badge/status-work--in--progress-success.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat.svg)](https://github.com/lucylow/Deep-Learning-Mahjong---/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat.svg)](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/pulls)
  [![License](https://img.shields.io/bower/l/bootstrap)]()

</div>

---
![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/Screen%20Shot%202022-08-23%20at%207.54.19%20PM.png?raw=true)


* Name of Team: Qubit
* Name of team member: Lucy Low low.lucyy@gmail.com, lucylow github, ! LowIQ#5208 discord
* Name of pitch presenter: Lucy Low
* Name of Challenge: Humans-vs-Quantum-Computers


---

# Humans-vs-Quantum-Computers


"Create a working interactive ‘program’ (it can be a website, game, app, etc.) in which a human user is facing off against a quantum computer. This is broad on purpose - the program can be built in many different ways. Your program should implement strategies that seriously challenge the human player. The implementation must utilize more than just probabilities related to measuring quantum states. You must use Qiskit to program the computer’s gameplay strategy, and as much as possible, the strategy should be implemented with quantum circuits and quantum gates on real quantum hardware (although using the Simulator is understandable given the time limit)."

---

# Staying Alive: Game Storyline


Professor X was testing a quantum experiment on his digital cat Schrödinger when his quantum computer started glitching. By entangling his cat into two copies, she seperated the cat's dark and light energy. Bad cat is controlled by the Quantum Computer and is an obnoxious cat who, sickly, gets off on copying, imitating, emulating, simulating and miming all your actions and is just another individual who copies you in everything you do. *He wants to steal the diamond quantum computer running Professor X's lab experiment and destroy the world.*

This is a quantum circuit game in which you have to save both the good and bad cat in the screen at the same time, in order to earn quantum gates to complete the quantum circuit. Here, the good cat = the Classical Computer, and the bad cat is the Quantum computer.  Save the world with quantum circuits.

This is a quantum circuit puzzle game with a quantum physics twist. You control a cat in a superposition through a bizarre world. Your mission as Professor X to use your genius skills to solve circuits to help the good cat defeat the bad cat and demonstrate "quantum supremacy" for the first time in human history. This is done by comparing the results by running the same circuit on a simulator and real quantum hardware at IBM.


![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/Screen%20Shot%202022-08-23%20at%207.56.55%20PM.png?raw=true)

---

# Qiskit Quantum Circuit

IBM Quantum Lab QopyCat NotebooK:

https://lab.quantum-computing.ibm.com/user/5e28b707e36ac8001898c192/files/qiskit-textbook/content/ch-demos/QOPYCAT%20GAME.ipynb?_xsrf=2%7Ce2d55dc0%7C09405a382bf20eccea0c2fe339a4ea4e%7C1659201756


Quantum Teleportation built using IBM's QisKit SDK to create quantum computing circuits work on  IBM's  5 qubit quantum computers IBMQ Quito and IBMQ Manila: 

IBM Quantum Experience https://quantum-computing.ibm.com/ Qiskit Simulators https://qiskit.org/overview/#simulators


![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/Screen%20Shot%202022-08-23%20at%209.46.05%20PM.png?raw=true)



Save the world with quantum circuits. You win by solving quantum circuit puzzles. What is a quantum circuit? https://www.youtube.com/playlist?list=PL1826E60FD05B44E4 


A game for exploring and understanding quantum teleportation using quantum circuits with a drag-and-drop quantum circuit simulator and consists, starting from a multi-qubit circuit initialized at |+>|->|+>|->|+>|-> to measure as many |0> or |1> depending on which player you are. The game needs a good understanding of how various probabilities interact, to be able to comprehend how the state collapses upon observation, which happens when the piece is either capturing or being captured, and decides the position of a piece in superposition. 


Quantum Gates and Quantum Circuit Level Systems with increasing difficulty for the player from 1. Normal 2. Medium 3. Standard 4. Average 5. Intermediate. Gate cards will consist of either single qubit gates or two qubit gates, and each gate is assigned a rarity that determines how frequently it is drawn like measurements, Swaps, RX, RY, RZ for teleportation. This is done by collecting Gates is allowed to use H, X, Z, and the controlled version of this last two gates to achieve the quantum teleportation goal composed of the two classical and quantum bits: Quantum teleportation circuit with Bloch sphere displays. Game is a great way to demonstrate and understand quantum properties. 

Includes educational quantum elements from https://qiskit.org/textbook/preface.html.



![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/qiskit/Screen%20Shot%202022-08-23%20at%2010.54.33%20PM.png?raw=true)
![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/qiskit/Screen%20Shot%202022-08-23%20at%2010.54.43%20PM.png?raw=true)
![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/qiskit/Screen%20Shot%202022-08-23%20at%2010.54.58%20PM.png?raw=true)





----

## QopyCat Front-End Game 

![Alt Text](https://github.com/lucylow/IBM-QopyCat/blob/main/data/ezgif.com-gif-maker%20(15).gif?raw=true)

https://youtu.be/NE1nJmxRHLY

### Menu Options
* Play Qopycat
* Circuits (6 levels)
* Teleport (Final Circuit Build)

### How to Play


The good and bad cats are quantumly entangled such that any action performed by one of us must also be performed by the other. 


1. Move the two cats in superpositioned with keyboard WASD or arrow keys. 
2. Move both cats into the final quantum state without harm.
3. Player completes 6 QopyCat map to unlock Quantum Gate Cards
4. The players drag and drops the Quantum Gate Cards to make a correct quantum circuit for the problem. 
5.  Select a gate or tool from the popup menu (that appears when pressing E). Place H gates on an empty white block in the circuit (using the X key or button)
6. The user circuit converter transforms the user input circuit into a Qiskit quantum circuit.
7. At the end of the round, measurements are taken of the quantum circuit. (The “constant” player wins if the measurement turns out to be 00 or 11, and the “balanced” player wins if the measurement turns out to be 01 or 10. )
8. The first player who gets the correct quantum circuit in the shortest amount of time wins!




---

# Installing 


Install the Prerequsites

> Git
> Node.JS
> Python 3
> Qiskit
> IBMQ API token

Clone the repository.

> git clone https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/edit/main/README.md.git

Install the dev dependencies.

> cd QopyCat

Build the output.

> npm run build

> npm install

Install Jupyter (https://github.com/IBM/qiskit-sdk-py/blob/master/tutorial/sections/tutorial4developer.ipynb)

---

## QopyCat End Game 

Example of the Quantum Computer (bad cat) winning significantly over the Classical Computer (good cat) with a 10% error margin

![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/qiskit/Screen%20Shot%202022-08-23%20at%2010.55.13%20PM.png?raw=true)

![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/qiskit/Screen%20Shot%202022-08-23%20at%2010.55.24%20PM.png?raw=true)

---

# Future Plans
* Add game mechanics like portals and powerups
* Add quantum wall barrier to change good/bad cat relative positions
* Collapsing the superposition part of game
* Compare circuit execution on a classical computer vs real quantum device
* https://github.com/mxgmn/WaveFunctionCollapse
* Add different circuits like quantum error correction for the cat to get rid of quantum errors to keep our quantum state alive
* Add a timer and leadership board 
* Procedural generation like terrain, levels, puzzles, etc) for game content using quantum computing 

---
