# ACoMoR: Audio Controlled Mobile Robot

"ACoMoR" is an autonomous wheeled mobile robot build ad-hoc for the task of tracking still and moving sound sources in the environment relying only on audio data captured with four microphones and three range finders for obstacle avoidance.

The sound source location is estimated through an algorithm based on the Time Difference of Arrival (TDOA), it is implemented in Python and executed on a Raspberry PI 3 B+. The estimated information is then passed to an Arduino Mega which is in charge of controlling the actuators through an ad hoc digital control law.

This [video](https://www.youtube.com/watch?v=a6fZdroQGE0&ab_channel=FeiXia) highlights the main features of ACoMoR and it will show four experiments:

* Tracking of a sound source emitting white noise at a fixed position.
* Tracking of a sound source emitting white noise at a fixed position in presence of obstacles.
* Tracking of a sound source emitting classical mnusic in a fixed position in presence of obstacles.
* Tracking of a moving sound source emitting white noiise in presence of obstacles.
