# Banluck

Simple simulation of a the asian blackjack known as "ban luck". 
Rules of Ban Luck can be found: https://en.wikipedia.org/wiki/Chinese_Blackjack

Purpose of this simulation is to find out the odds of drawing different cards (basis total cards on the table) 
when the dealer is faced with a weak hand (16 or 17)  

Packages required to import:
Random
Pandas

Parameters required from users when running file:
Number of players on the table (not including dealer)
Number of simulations (to be recorded) that dealer reaches 16 or 17
Risk profile of players : minimum hand required for players to stop drawing

output of file:
Basis total cards on the table, probability of drawing different cards for the next hand in a DataFrame table
