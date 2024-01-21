<a name="br1"></a> 

1

Dual Heater Temperature Control using PID

Controller

Aravindhan Thaninayagam, Arizona State University

Abstract—This document presents a project report on the

implementation of a PID controller for dual heater temperature

control. The project explores two approaches, one using a A. Simulink Model

Simulink model and the other utilizing Python. The objectives

include developing a control system, tuning PID parameters, and

comparing the effectiveness of the two implementations.

III. RESULTS

I. INTRODUCTION

A. Background

In the realm of temperature control systems, maintaining a

stable room temperature is essential for various applications.

This project explores the utilization of a PID (Proportional-

Integral-Derivative) controller to regulate two heaters and

achieve a target room temperature of 23.33 degrees Celsius.

B. Python Implementation

B. Objectives

\1) Develop a control system using a PID controller\.

\2) Implement the control system in two different environ-

ments: Simulink and Python.

\3) Compare the effectiveness and efﬁciency of the Simulink

and Python implementations.

II. METHODOLOGY

A. Simulink Model

\1) Create a Simulink model for the dual heater control

system.

\2) Integrate a PID controller into the model\.

\3) Tune the PID parameters for optimal performance\.

\4) Simulate the system and record results\.

IV. DISCUSSION

A. Advantages of Python Implementation

The Python implementation using the PID controller code

from the apmonitor site exhibited the following advantages:

• Ease of Tuning: Tuning the PID controller parameters in

the Python environment proved to be more straightfor-

ward. The ﬂexibility of Python libraries and the ability to

quickly modify parameters allowed for efﬁcient tuning.

• Computational Efﬁciency: The Python code demonstrated

faster compilation times and consumed less RAM mem-

ory on the computer. This efﬁciency is crucial, especially

in real-time applications where quick responses are re-

quired.

B. Python Implementation

\1) Utilize Python code for PID control from the apmonitor

site.

\2) Adapt the code to control two heaters\.

\3) Perform tuning of PID parameters using Python\.

\4) Run simulations and capture relevant data\.



<a name="br2"></a> 

2

B. Advantages of Simulink Implementation

On the other hand, the Simulink model showcased its

strengths in certain aspects:

• Intuitiveness: Simulink’s graphical interface provides an

intuitive representation of the control system. Compo-

nents are visually connected, making it easier for users,

especially beginners, to understand the model’s structure.

• Learning Purposes: Simulink serves as a valuable tool

for educational purposes. It allows users to grasp control

system concepts in a visual manner, aiding in the learning

process.

C. Challenges and Solutions

• Python Implementation Challenges: While the Python

model offers computational advantages, it lacks the in-

tuitive visual representation present in Simulink. Under-

standing the components of the control system may be

challenging, especially for individuals less familiar with

coding.

• Solution: Developing thorough documentation and com-

ments within the Python code can mitigate the lack of

visual clarity. This ensures that future users can easily

comprehend the code structure and functionality.

• Simulink Challenges: Simulink, being a graphical tool,

can be resource-intensive, requiring more computing

power and memory.

• Solution: Optimizing the Simulink model and running

simulations on a computer with sufﬁcient resources can

alleviate the computational burden.

V. FUTURE WORK

Considering the strengths of both the Simulink and Python

approaches, a promising avenue for future work is the de-

velopment of an integrated program. This program could

combine the intuitive visual representation of Simulink with

the computational efﬁciency and ﬂexibility of Python. Such

an integration could provide users with a comprehensive tool

that leverages the strengths of both environments, offering

a seamless and efﬁcient control system design and analysis

experience.

VI. ACKNOWLEDGMENTS

Sincere thanks to Professor Thomas Sugar for his kind and

patient approach to teaching EGR 550: Mechatronics Systems

Course.

Sincere thanks to Harsh for assisting with assignments and

UR-5 Lab.


