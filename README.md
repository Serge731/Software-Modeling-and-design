# Software-Modeling-and-design
This design provides coverage for all four major directions (NS, EW, NE, SW) with specified durations and transitions for each traffic movement, ensuring controlled traffic flow in multiple directions.

Direction(NS)
Initial State (Start)
Purpose: Begin the traffic light cycle.
Transition: Proceeds to "NS Green Light."
NS Green Light
Purpose: Allows north-south traffic movement.
Duration: 60 seconds.
Transition: After 60 seconds, proceeds to "NS Yellow Light."
NS Yellow Light
Purpose: Warns that north-south traffic will stop soon.
Duration: 5 seconds.
Transition: After 5 seconds, moves to "NS Red Light."
NS Red Light
Purpose: Stops north-south traffic to allow east-west traffic.
Transition: Advances to "EW Green Light."

Direction(EW)
EW Green Light
Purpose: Allows east-west traffic movement.
Duration: 60 seconds.
Transition: After 60 seconds, moves to "EW Yellow Light."
EW Yellow Light
Purpose: Warns that east-west traffic will stop soon.
Duration: 5 seconds.
Transition: After 5 seconds, changes to "EW Red Light."
EW Red Light
Purpose: Stops east-west traffic, initiating north-east or south-west directions.
Transition: Alternates between NE and SW traffic cycles.

Direction(NE)
NE Green Light
Purpose: Allows north-east traffic movement.
Duration: 60 seconds.
Transition: Switches to "NE Yellow Light" after 60 seconds.
NE Yellow Light
Purpose: Indicates an imminent stop for NE traffic.
Duration: 5 seconds.
Transition: After 5 seconds, proceeds to "NE Red Light."
NE Red Light
Purpose: Stops NE traffic, allowing SW traffic.
Transition: Proceeds to "SW Green Light."

Direction(SW)
SW Green Light
Purpose: Allows south-west traffic movement.
Duration: 65 seconds.
Transition: After 65 seconds, changes to "SW Yellow Light."
SW Yellow Light
Purpose: Warns that SW traffic will stop soon.
Duration: 5 seconds.
Transition: After 5 seconds, switches to "SW Red Light."
SW Red Light
Purpose: Stops SW traffic, allowing the cycle to restart with NS Green Light
