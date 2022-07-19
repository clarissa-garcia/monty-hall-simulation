# Monty Hall Simulation

## Overview
For the uninitiated, the Monty Hall Problem is a famous probability puzzle. The premise sets you as a contestant in a game show similar to "Let's Make a Deal" in which there are three doors, 2 of which have an unfavorable prize (the original problem makes the prize a goat) and one which has a favorable prize (a car in the original problem). If a contestant chooses one door, the host opens one of the unchosen doors to reveal a goat and gives the contestant the option to switch to the last unchosen door before revealing the prizes. Is it to the contestant's advantage to switch their choice of door to receive the car or stick with their original choice?

Most people's knee-jerk assumption is that there is no advantage to switching since the current chosen door and the last unchosen door appear to have a 50/50 probability of having the car prize. But the official consensus among the community is that switching leads to a statsistcally-better probability of garnering the car prize: the door opened by the host and the last unchosen door account for 2/3 probability of hosting the car compared to the 1/3 probability of the door the contestant has chosen. 

## Goal
Even after watching some videos about this problem and the explained solution, it was still confusing to wrap my head around. So I wrote a program to simulate this problem and hopefully help other people see the answer is legitamate for themselves. I want the simulation to have an option for repeating the experiment a maximum number of times, switch to the last unchosen door half the time, and count whether the switching or staying with the original door increased the odds of the car prize. Was there a reliable percentage expected of winning the car during switches? How many times would the experiment need to be repeated to see a trend? Additionally, would the outcome change based on how many doors there are?
