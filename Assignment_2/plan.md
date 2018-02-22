Plan for assignment 2 

MAS-ter plan
<br><br>

Messages
* What to communicate between buses?
  * List of busstops for this bus (bs-list)
  * Amount of passengers (bus_passengers)
* Message looks like this: [tick sender message]
  *  maybe message = [ bs-list bus_passengers ]
* To achieve what?
  * Only add bus when necessary
* When to send a message?
  * When the bus is full?
  
When to add a bus?
* When other buses are full
* When many people are waiting
* When no bus with empty spaces is going to pick the passengers up
* When the amount of people waiting is much larger than the total amount the current buses can carry
* So are messages really necessary, isn't the last point enough to determine the necessity of an extra bus?

What trajectory to create for a new bus?
* With most people
* When no or not enough buses are going to that location


