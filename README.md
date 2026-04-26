# AI Robotics Curriculum Code Portfolio
This repository organizes supporting source code for a five-lesson AI/ML robotics curriculum developed for the Robotics Education & Competition Foundation (RECF). The lessons use micro:bit-based activities to introduce data collection, optimization, unsupervised learning, supervised learning, and reinforcement learning through hands-on robotics and embedded systems.

## Ownership & Attribution
This work was developed as part of a curriculum project for the Robotics Education & Competition Foundation (RECF). Curriculum materials and associated intellectual property are owned by RECF. This repository is maintained as a portfolio reference to describe and link to supporting technical implementations. It is not an official RECF repository and does not reproduce RECF curriculum materials.

## Reference to Curriculum Resources
These 5 Lessons are designed to be run on a simple and inexpensive micro:bit computer which is well suited for middle school students or others who are getting their first exposure to coding, robotics, machine learning, and artificial intelligence.\
[AI in Robotics Pathway Introduction](https://docs.google.com/document/d/1hIeE0BF7uYozayUHZlpPO_GZatg-Pa8Ucn8uOwtqWZ8/view) 

## Lesson Summary and Supporting Code
Lesson1: Machine Learning Data Primer\
Format: Makecode (block)\
This module introduces the concept that machines learn by observing data. Here we are showing the students how to collect, report, visualize, and interpret sensor data from their micro:bit computers.\
Demo: [https://makecode.microbit.org/S01501-19511-89261-24102](https://makecode.microbit.org/S01501-19511-89261-24102) \
Repo: [https://github.com/kkrave/microbit-data-logger-demo](https://github.com/kkrave/microbit-data-logger-demo)

Lesson2: Optimization\
Format: Makecode (block)\
This module uses the example of teaching a computer to play the classic Pong video game by implementing a simple gradient descent optimization to reduce the observed errors from repeated missed balls during extended gameplay. Using simple block-code, in relatively little time, the micro:bit CPU player masters the game by updating its guess after each miss.\
Demo: [https://makecode.microbit.org/S28516-55497-94576-26826](https://makecode.microbit.org/S28516-55497-94576-26826) \
Repo: [https://github.com/kkrave/microbit_pong_ml](https://github.com/kkrave/microbit_pong_ml)

Lesson3: Unsupervised Learning\
Format: Makecode (block)\
This module uses the example of a step-counter, instructing students in analyzing unstructured micro:bit IMU data to distinguish 'steps' from 'non-steps'.  
Demo: [https://makecode.microbit.org/S38129-11744-88445-38193](https://makecode.microbit.org/S38129-11744-88445-38193) \
Repo: [https://github.com/kkrave/threshold-step-counter-](https://github.com/kkrave/threshold-step-counter-)

Lesson4: Supervised Learning\
Format: Makecode (block)\
This module uses micro:bit create ai platform to instruct students how to collect labeled data using their micro:bit and train their own machine learning model with their own data and then use that model in their own applications. 
Demo:  [https://createai.microbit.org/](https://createai.microbit.org/) \
Repo: n/a

Lesson5: Reinforcement Learning\
Format: Makecode (MicroPython)\
This module introduces students to Python code for the first time and uses the concept of a mazerunner learning to find the optimal path through a maze. The code uses a simple implementation of Q-Learning algorithm which penalizes incorrect or inefficient steps through the maze and rewards correct steps. \
Demo: [https://makecode.microbit.org/S70487-28375-93472-79917](https://makecode.microbit.org/S70487-28375-93472-79917) \
Repo: [https://github.com/kkrave/MazeRunner_RL](https://github.com/kkrave/MazeRunner_RL)
