# Sleep-Wake Robotics

date:  May-Aug 2017

## Description

We try and accelerate the time a machine takes to solve an easy problem such as: reaching a light. We make the robot learn its environment through data it collects, then predict its next movement in its head to find the correct one, and executes it.

This is the thesis for my Master in Intelligent Systems at the University of Sussex. Supervised by Chris Buckley and helped by Efstathios Kagioulis.

## Details

This project consists of applying machine learning to a Braitenberg vehicle to simulate the modelling of its environment through motor commands and sensory information. The robot will go through "sleep-wake" cycles to accelerate the learning of the environment by doing "offline" processing with data gathered in real-time.

The simulated vehicle uses a NARX network (Non-linear AutoRegressive network with eXogenous inputs), which uses past sensory information with present motor information to predict the next sensory outcome.

Below is portrayed the trajectory of the robot after learning and optimisation (in red), the simulated predicted trajectory (in grey) and the control trajectory (in green).

!screenshot of machine trajectories

The code repository is available at github.com/lucasrijllart/Sleep-Wake

!poster

Poster presenting the approach in more detail, with different stages and results. By Efstathios Kagioulis

## Abstract of projcet

Robotics has always faced the issue of adaptability to new environments and new situations. To create an adaptive behaviour, we make the agent create its own model of the environment. We design Sleep-Wake cycles to structure the behaviour of the agent into learning, then problem solving. By using a model of the environment to predict future movement, we can simulate all robotic trial- and-error, decreasing the amount of real time needed to get a solution. Results show one cycle performs nearly as well as the optimal answer, with a generalised behaviour generated from a short prediction, and solving the problem in less time than trial-and-error.

Download Dissertation by clicking here

http://lucasrijllart.com/wp-content/uploads/2017/11/Dissertation_162206.pdf