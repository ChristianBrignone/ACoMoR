# ACoMoR: Audio Controlled Mobile Robot

Authors: Christian Brignone, Gioia Mancini.

<img src="https://github.com/ChristianBrignone/ACoMoR/blob/main/Images/ACoMoR1.0.jpg" width="300" >

"ACoMoR" is an autonomous wheeled mobile robot build ad-hoc for the task of tracking still and moving sound sources in the environment relying only on audio data captured with four microphones and three range finders for obstacle avoidance.

The sound source location is estimated through an algorithm based on the Time Difference of Arrival (TDOA), it is implemented in Python and executed on a Raspberry PI 3 B+. The estimated information is then passed to an Arduino Mega which is in charge of controlling the actuators through an ad hoc digital control law.

This [video](https://youtu.be/DSioZE_8FHM) highlights the main features of ACoMoR and it will show four experiments:

* Tracking of a sound source emitting white noise at a fixed position.
![](https://github.com/ChristianBrignone/ACoMoR/blob/main/GIFs/ACoMoR__Experiment%201.gif)
* Tracking of a sound source emitting white noise at a fixed position in presence of obstacles.
![](https://github.com/ChristianBrignone/ACoMoR/blob/main/GIFs/ACoMoR__Experiment%202.gif)
* Tracking of a sound source emitting classical music at a fixed position in presence of obstacles.
![](https://github.com/ChristianBrignone/ACoMoR/blob/main/GIFs/ACoMoR__Experiment%203.gif)
* Tracking of a moving sound source emitting white noise in presence of obstacles.
![](https://github.com/ChristianBrignone/ACoMoR/blob/main/GIFs/ACoMoR__Experiment%204.gif)

Stay tuned, a new entirely redisigned version of ACoMoR is coming soon! 

<img src="https://github.com/ChristianBrignone/ACoMoR/blob/main/Images/ACoMoR2.0.png" width="300" >
