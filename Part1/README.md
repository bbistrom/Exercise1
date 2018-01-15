Part1: Thinking about elevators
---------------------------

Not for handing in, just for thinking about. Talk to other groups, assistants, or even people who have taken the course in previous years.

Brainstorm some techniques you could use to prevent a user from being hopelessly stranded, waiting for an elevator that will never arrive. Think about the [worst-case](http://xkcd.com/748/) behaviour of the system.
 - What if the software controlling one of the elevators suddenly crashes?
    - Reboot the systemand return elevator to initial state. (user has to choose destination again) 
 - What if it doesn't crash, but hangs?
    - Reboot the systemand return elevator to initial state. (user has to choose destination again) 
 - What if a message between machines is lost?
    - Keep waiting for message. Light up button for received message. 
 - What if the network cable is suddenly disconnected? Then re-connected?
    - Notify maintenance and ask for reconnecting the cable 
 - What if a user of the system is being a troll?
    - Prevent user from trolling with a state machine that serves requests 
 - What if the elevator car never arrives at its destination?
    - If it never arrives, user has to press button again 

 
