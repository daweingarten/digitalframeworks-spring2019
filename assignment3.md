# Assignment 3--Data Cleaning
### By Dwight A. Weingarten

I chose to examine the all-time Baltimore Ravens scoring list with data obtained here. <br>
https://www.pro-football-reference.com/teams/rav/career-scoring.htm

## Original Ravens Scoring File

This document shows the original downloaded file. <br>
https://docs.google.com/spreadsheets/d/1PK3VIWmKZdGsdrCuv-S3_J1RUlLaYHqPQffDAVsa42Y/edit#gid=0

## Steps to Clean
1) I used the comma delimiter for the entire set.
2) I used find and replace for all the blanks with a 0. I deleted the column Pts/G because that was not 0.
3) I inserted the formula W2/E2= and dragged the data down for the Pts/Game column. This was points per game.
4) I inserted a new column Offense, Defense, or Special Teams.<br>
    a) I selected my data from the position row and copied it into the new column and highlighted the column.<br>
    b) If the position was K or P, I did find and replace with ST.<br>
    c) If the position was QB, RB, WR, TE, LT, T, FB, I did find and replace with O.<br>
    d) If the position was FS, S, SS, LB, ROLB, LOLB, LCB, RCB, MLB, CB, DB, LDE, RDE, DE, DT, RDT, LDT did find and replace with D.<br>
5) Chris Matthews did not have a position, nor was he a MSNBC commentator for the Ravens, I manually filled in his data as a WR and O.
6) There were 5 or 6 players still listed as KR or PR, I manually changed their side to either offense or defense depending on what they played predominately.

## Final Ravens Scoring File

This document shows the final version after the steps were followed. <br>
https://docs.google.com/spreadsheets/d/1ndHsCLgcXp3TbrXPdwuDzryaRsWYLCWG3vQvqRTiI14/edit#gid=0
    

