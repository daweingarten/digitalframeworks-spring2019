#h1 Assignment 3--Data Cleaning

#h2 Original Ravens Scoring File

This document shows the original downloaded file.

#h2 Steps to Clean
1) I used the comma delimiter for the entire set.
2) I used find and replace for all the blanks with a 0. I deleted the column Pts/G because that was not 0.
3) I inserted the formula W2/E2= and dragged the data down. This was points per game.
4) I inserted a new column Offense, Defense, or Special Teams.
    a)I selected my data from the position row and copied it into the new column and highlighted the column.
    b)If the position was K or P, I did find and replace with ST.
    c)If the position was QB, RB, WR, TE, LT, T, FB, I did find and replace with O.
    d)If the position was FS, S, SS, LB, ROLB, LOLB, LCB, RCB, MLB, CB, DB, LDE, RDE, DE, DT, RDT, LDT did find and replace with D.
5) Chris Matthews did not have a position, nor was he a MSNBC commentator for the Ravens, I manually filled in his data as a WR and O.
6) There were 5 or 6 players still listed as KR or PR, I manually changed their side to either offense or defense depending on what they played predominately.

#h2 Final Ravens Scoring File

This document shows the final version after the steps were followed. 
    

