# Snake Playing AI

> an artificial intelligence agent which learns to play the game snake with deep Q learning

---

### Table of Contents
- [Description](#description)
- [How To Use](#how-to-use)
- [Author Info](#author-info)

---

## Description

Snake is a video game idea in which the player controls a line that increases in length, with the line itself serving as a key barrier. This type of game environment, where the rewards to the player are well defined beforehand is perfect for training an agent with the help of reinforcement learning. This project provides the basic code for an agent which starts off with a random strategy and slowly becomes better by playing many games.

#### Requirements

- python
- pygame
- pytorch package
- Ipython package
- matplotlib

---

## How To Use




#### Installing the necessary packages
Pytorch
```bash
   pip install torch torchvision
```
Pygame
```bash
   pip install pygame
```
Ipython
```bash
   pip install ipython
```
Matplotlib
```bash
   pip install matplotlib
```
This project was created on Scrapy python 3.9.5, but any subsequent versions will also work.

#### Running the project
To train the agent you just need to navigate to the project folder where the file agent.py is located and then simply run the file on the terminal
```bash
   python agent.py
```
Two displays will open up on running this file. One is the environment where the game is played in real time and you can watch as the agent learns to play the game. The other display shows us how the agent is improving over time with statistics like the highest score, most recent score and the average score of all the games played upto that point. 

#### Modifying the agent
If you want to experiment with the behaviour of the agent, you can open the agent.py file in any editor and you will find some variables listed whose values, if changed will have an impact on the performance of the agent. This can be used to eventually find the optimum values for these parameteres.

---



## Author Info

- Instagram - [@AnishMulay](https://www.instagram.com/_Anish_Mulay_/)
- Email - f20180907@goa.bits-pilani.ac.in

