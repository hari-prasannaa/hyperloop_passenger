# hyperloop_passenger
This project is to program a passenger booking system for a hyperloop transport of Aparticular station.
This complete project is coded using python language.
main advantage is that changes are made in a text file at every step.

Assumptions
1. All the hyperloop routes & the starting station will be given as input.
2. Assumptions is that, the distance and time taken travel a route is constant.
3. A pod can travel from one connection to another in any direction in the given route. (i.e both A to B and B to A)
4. One pod can accommodate only one passenger at a time.
5. Passengers will be booked to their pods one by one.
a. All passengers will start from the given starting station.
b. Whenever a pod is started, the oldest person in the queue will boarding pod first.
6. Passengers can arrive at any time as well as pods can start at any time.
7. Assume infinite supply of pods and collision will never happen.

I have used 5 functions:
1.INIT Command  - Initializes with Number of interconnecting routes (N) and the Starting station. Next N lines denotes connection between two interconnections.
2.ADD_PASSENGER X adds X number of passengers to the line. 
3.START_POD starts pod with a passenger having highest age to his destination following the minimum interconnection points. Print the passenger name and route.
4.PRINT_Q command prints the number of passengers and their details who are
remaining in the queue.
5.BFS_SP to find the shortest points.
