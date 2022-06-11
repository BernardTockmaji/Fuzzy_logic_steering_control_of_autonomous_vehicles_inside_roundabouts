# Fuzzy_logic_steering_control_of_autonomous_vehicles_inside_roundabouts
Fuzzy logic steering control of autonomous vehicles inside roundabouts
<h1>Fuzzy logic steering control of autonomous vehicles inside roundabout</h1>
<b>This system is designed to determine how autonomous cars drive while entering roundabout roads</b>

The control of autonomous vehicles on the roundabout can bedivided into three stages: entrance, circulating lane, and exit. 
Different controllers are used at each stage once the roundabout is detected. 
The control of autonomous vehicles on the roundabout can bedivided into three stages: entrance, circulating lane, and exit. 
Different controllers are used at each stage once the roundabout is detected. 
Based on this knowledge, two fuzzy controllers are designed:<br>
<br>
<b>1- Steering wheel position fuzzy controller<br>
2- Angular speed fuzzy controller.</b>
  
The Steering position controller has two inputs, <b>the lateral error (meters) and the angular error (degrees)</b>.
The Angular speed controller are <b>the Distance to the bend (meters) andLongitudinal speed (kilometers per hour (km/h))</b>.

The values of the membership functions are calculated by running several tests with the vehicle driven by a human. Values of the two input variables, position and angular speed, were recorded when the human driver was driving the car at the roundabout.
  
While working on implementing this fuzzy system we have 3 main stages<br>
1- <b>Stage one:</b> Defining the antecedents and consequents of the system and assigning membership functions variables.<br>
<br>
2- <b>Stage two:</b> Defining the rules needed for building the system, since the system has two fuzzy controllers, its going to have two seperate sets of rules.<br>
<br>
3- <b>Stage three:</b> Building the control system for each fuzzy controller and initiating the proper simulation needed.<br>
