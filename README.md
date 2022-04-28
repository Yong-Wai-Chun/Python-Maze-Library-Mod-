# Python Maze Library Modification Study Project

## Introduction and Problem Statement

<p align="justify">
    Hello, this project about mainly about a modification done to an existing Python project called <a href="https://github.com/MAN1986/pyamaze/blob/main/pyamaze/pyamaze.py">Pyamaze</a> with some searching algorithms. Pyamaze library is a library that is developed in Python and can be import to use after downloading on any IDLE tools. This library is about creating a maze and visualizing an agent's route to its goal. Figure 1 shows an example of the output. The maze consists of only one agent and one goal. The route searching technique being used here is Breadth First Search by default.
</p>

<p align="center">
  <img width="45%" src="https://github.com/Yong-Wai-Chun/Python-Maze-Library-Mod/blob/main/components/f1.png?raw=true">
  <br> Figure 1
</p>

## Contributions and Motivations

<p align="justify">
    The modification made here is instead of having just one goal, two more goals are added. The goals will change intervally and when the goal changed, the agent will retrace a new path and keep searching for the new goal until it reached the last goal generated eventually. The main purpose of this modification is to understand an exisiting Python package and learn to modify the codes. Programming does not only need to write original codes but it is also very important to learn from other people's codes and modify them to satisfy with our own's requirements. The other motivation is by creating more goals, we can visualize how the agent moves to different path based on different searching algorithms.
<br><br>
</p>

## Searching Algorithm Used:
- Uninformed:
    - Depth First Search
    - Breadth First Search
- Informed:
    - A Star Search

## !!! INSTRUCTIONS !!!
    1. Only run the contents in the main.ipynb Jupyter Notebook.
    2. pyamazeMod.py is the modified Pyamaze Library, please keep the main.ipynb and pyamazeMod in the same directory while running.
    3. To run the original pyamaze library, please uncomment the first package in the package code block and comment the second package in the package code block.
    4. Vice versa for running the modified pyamaze library.
    5. Only one of the pyamaze or pyamazeMod packages has to be commented, DO NOT comment both or uncomment both.
    6. Pyamaze library has problem with the kernel. The maze window will stop running after closing a previous maze window.
    7. Please close the maze window manually as soon as the agent has reached its last goal to avoid time recording inaccuracy.
    8. Avoid restarting kernel with clearing output so that it's easier to refer back the searching time.
    9. Avoid using restarting kernel and run all option.
    10. Avoid changing or modifying all the code below except running them.
    
