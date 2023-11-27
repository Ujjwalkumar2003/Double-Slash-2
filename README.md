<p align="center">
<h1 align="center">Double-Slash-2.0-Team Crypto_Coders</h1>
<p align="center">
 

<h3 align="center">Traffic Management System and Adaptive Traffic Signal Timer</h3>

<div align="center">

[![Python version](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)

<h4>This Adaptive Traffic Signal Timer reduces traffic congestion on highways, provides faster travel for people, and consumes less fuel by utilising live pictures from the cameras at traffic intersections to calculate traffic density using YOLO object identification and setting the signal timers appropriately.</h4>

</div>

-----------------------------------------
### Introduction

* With the growing number of people and cars in cities, traffic congestion is one of the most pressing problems. In addition to adding to driver stress and delay, traffic bottlenecks also result in higher fuel usage and air pollution.

* According to studies, Mumbai, Bengaluru, and New Delhi are three of the top 10 cities in the world with the worst traffic congestion. People are forced to lose hours of valuable commute time by getting caught in traffic. The current system of traffic signal controllers uses a set timeframe and does not adjust to the flow of vehicles on the road in real time.

* We created a better traffic management system using a computer vision-based traffic light controller that can automatically adjust to the volume of vehicles at the traffic signal in an effort to lessen traffic congestion. The suggested approach guarantees that the direction with more traffic is given a green signal for a longer period of time than the direction with less traffic by setting the green signal time adaptively according to the traffic density at the signal.

------------------------------------------
### Implementation Details

This project can be broken down into 3 modules:

1. `Vehicle Detection Module` - This module counts the number of cars in the image that the camera sends as input. More precisely, it will output the quantity of each type of vehicle, including cars, bikes, buses, trucks, and rickshaws.

2. `Signal Switching Method` - This algorithm changes the timing for all signals that are red, green, and yellow. These timings are determined based on numerous variables, including the number of lanes, the average speed of each class of vehicle, and the vehicle detection module's count of each class of cars.

3. `Simulation Module` - A simulation is developed from scratch using [Pygame](https://www.pygame.org/news) library to simulate traffic signals and vehicles moving across a traffic intersection.


------------------------------------------
### Demo

* `Vehicle Detection`

![WhatsApp Image 2023-01-22 at 1 27 03 PM](https://user-images.githubusercontent.com/85414445/213906121-045f9fdc-d15e-4fbc-9eea-d7ba06817b2a.jpeg)


<br> 

* `Signal Switching Algorithm and Simulation`

<p align="center">
    <img src="./Demo.gif">
</p>

------------------------------------------


### Contributors

 

Soumyo Nath Tripathy 

Shubham Kumar Singh

Ujjwal Kumar

Aayush Kumar Singh 



------------------------------------------
