# DiceGame

Created By: Faith Goddard

# Project Description

This project works by creating 5 threads. The first is the dealer and the reaming four are
the players. The dealer waits for the players to get set up before letting the first player(picked at
random) roll the dice. All players are waiting while someone else rolls. That player then picks
the next person (A -> B -> C ->D ->A) to roll the dice. After each roll, the players check with their
team to see if they won. If they win Dealer announces which team won and all threads end and
join. The project is compiled with “g++ DiceMain.cpp -lpthread” command and then executed
with “./a.out”. All numbers used for rolls and start order is generated randomly inside the
program. Log results will be saved to “Project2Log.txt”.
