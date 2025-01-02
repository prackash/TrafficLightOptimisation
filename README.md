# TrafficLightOptimisation

The goal of this repositroy is to optmise the traffic light timings such that traffic jams can be minimised.

Every Traffic Light junction is treated as a node in a directed graph.

Assign weights to edges (roads) based on the traffic congestion data, special vehicles like ambulance, fire truck, etc. 
Assign atmost importance to edges with vehicles in emergency mode.
Optimise the traffic lights reduce the indegree weights.
Classify the weights into low, mid, and high and toggle the timings correspondingly ( minimum 10 seconds and maximum 5 minutes).

Recalculate edge weights again and repeat the process till all the in degree weights are miniscule (Typically late night).


Additional Notes:

Consider the highways leading outside the city as node with in degree and out degree as 1. 
Allow manual override of weights and light timers.
ML can be used to predict weights for future events like a match in a stadium, christmas, school timings etc.
