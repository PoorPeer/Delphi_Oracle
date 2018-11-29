# Delphi_Oracle
Improving an Ouija board to provide Collective Intelligence

I attach a nice one player Ouija board, but the answers are now given by the program. This project is to develop it into a multi-user version, where the answers are given jointly by the users.
The idea is to let a moderator ask the questions and let the users move the planchette together by the mean from the user's mouse input. The purpose is to create a tool for collective (unconscious) intelligence.

REQUIREMENTS:<br>
Make the program read response from the board instead of write to the board. <br>
Moderator login -- name & password required. <br>
Only moderator can put questions. <br>
User login -- only name required. <br>
Only users can move the planchette. <br>
Algorithm: Add all the users mouse movements (except moderator) and divide it by the number of users. Round off and move the planchette by the mean.
The algorith must be able to handle at least 100 simultanteous users.
The program should be impossible to tamper.
