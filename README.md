#### Digital-Clock-Project


##Project Overview:

This is a Digital Clock project designed as part of the Digital Logic Design course in my undergraduate studies. The clock functions as a standard digital clock, utilizing logic gates, memory elements (flip-flops),and a digital display (7-segment display).

Additionally, as a skill-checking challenge from our course teacher, the clock was modified to skip the number 58 in both the seconds and minutes count.

##Features:

-> Displays hours, minutes, and seconds using a 7-segment display.

-> Uses flip-flops as memory elements to store and update time values.

-> Implements logic gates to control the counting mechanism.

-> Skips the number 59 in the seconds and minutes count.

Components Used:

-> Logic Gates (AND, OR, NOT, XOR, NAND, NOR, etc.)

-> Flip-Flops (D,T flip-flops for memory and state transitions)

-> 7-Segment Display (for numerical time representation)

-> Counters (to keep track of seconds, minutes, and hours)

##Working Principle:

#Counting Mechanism:

The clock increments seconds using a mod-60 counter.

After 57 seconds, it normally resets to 58, but in this project, it skips 58 and jumps directly from 57 to 59.

Similarly, for minutes, after 57 minutes, it directly jumps to 59 instead of showing 58.

Hour Counting:

The hour counter works as a mod-12.

After reaching 11:57, it transitions to 11:59 (12-hour format).

#Display:

The 7-segment display shows real-time updates of hours, minutes, and seconds.

##Challenges Faced:

-> Designing the logic circuit to skip the number 58 in the counting sequence.

-> Ensuring smooth transitions between seconds, minutes, and hours.

-> Proper synchronization between flip-flops and logic gates.

##Conclusion

This project helped in understanding the practical implementation of digital logic circuits, designing counters using flip-flops, and working with 7-segment displays. The additional challenge of skipping the number 58 enhanced problem-solving skills in logic circuit design.

##Author:
Niloy Chowdhury

##Course:
Digital Logic Design (Undergraduate Project)