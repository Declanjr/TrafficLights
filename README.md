"#This is a Traffic Lights State machine diagram  ID 24747" 

1.	Initial State - "North and South Red": 
•	Traffic lights on North-South roads are RED
•	Vehicles on North-South roads must stop
•	This is the starting point of the system

2.	First Transition: 
•	When in North-South Red, system transitions to "East and West Green"
•	This allows East-West traffic to flow while North-South remains stopped
•	East-West traffic gets a GREEN signal

3.	Timer Expiration & Yellow Warning: 
•	After the green timer expires for East-West
•	System transitions to "East and West Yellow"
•	Yellow light warns East-West traffic to prepare to stop

4.	Complete Stop Phase: 
•	After yellow timer expires
•	System moves to "East and West Red"
•	All East-West traffic must stop completely

5.	Directional Switch: 
•	System then gives "North and South Green"
•	Now North-South traffic can flow
•	East-West remains stopped

6.	Final Transition: 
•	North-South green timer expires
•	Changes to "North and South Yellow"
•	Warning for North-South traffic to prepare to stop

7.	Back to Start: 
•	After yellow timer expires
•	Returns to initial state "North and South Red"
•	Cycle begins again


