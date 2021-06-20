# S5058253_ARP_ASSIGNMENT-2

# How to compile the code

$gcc dp.c -o dp -lpthread

# How to run the code
$ ./dp

# Report

Each philosopher is represented by the following pseudocode:

1.process P[i] 2.while true do 3.ENTER 4.{ THINK; 4. PICKUP(CHOPSTICK[i], CHOPSTICK[i+1 mod 5]); 5. EAT; 6. PUTDOWN(CHOPSTICK[i], CHOPSTICK[i+1 mod 5]) }

There are three states of philosopher: THINKING, HUNGRY and EATING END LESSLY.

